# Guggy Publisher SDK
-------------------

Embed Guggy's GIF/Memes editor in your website with a super-small and simple SDK.

### What do you need?

1. Obtain a publisher ID from us (contact us at registration@guggy.com).
2. Embed the JS file in your website.
 
    Dev - ```https://rawgit.com/Guggyco/publishersdk/master/guggy-publisher-sdk.min.dev.js
    Prod - ```TBD

3. Initialize the SDK on a button in your site - see example below

### Usage

```js
  <script type="text/javascript" src="https://rawgit.com/Guggyco/publishersdk/master/guggy-publisher-sdk.min.dev.js"></script>
  ...
  
  function yourOnLoadFunction() {
  
    Guggy.init(
            'openGuggyButtonId' // An ID of a button on your website which will trigger Guggy to open,
            'yourPublisherId',
            function (post) {
  
                // Receive the created content JSON here, do whatever you'd like with it.
  
            },
            false, // Is Right-To-Left layout
            'he' // Language (either 'en' or 'he')
    );
  
  }

```


# License of usage and code
---------------------------
This SDK is Guggy's property and may not be distributed or modified without written consent.
Usage of the SDK is permitted only for approved publishers who have obtained a publisher ID from Guggy.
