# RetinaSDKNodeJS

## Installation

```sh
npm install retinasdk
```

## API

```js
var retinaSDK = require('retinasdk')
```


## INFO

Designed for the Retina API from www.cortical.io. 
This is the javascript SDK made to be accessible for server-side requests. The XMLRequests have been replaced with the request package. All functionality with the original SDK remains the same.

For a list of possible calls, see https://github.com/cortical-io/RetinaSDK.js
Register for a free api key at http://www.cortical.io/product_retina_api.html

Example:

```js
var retinaSDK = require('retinasdk');
var liteClient = retinaSDK.LiteClient(your_api_key);

/* Retrieve similar terms */
liteClient.getSimilarTerms("javascript");
> ["javascript", "browser", "html", "browsers", "api", "xml", "functionality", "microsoft", "runtime", "perl", "implementations", "css", "software", "unix", "files", "gui", "server", "plugin", "internet explorer", "linux"]



```