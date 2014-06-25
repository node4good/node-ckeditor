node-ckeditor
=============

Simple npm module to load the statics of CKEditor


Usage
=====

```js
var app = express();
var ckStaticsPath = require('node-ckeditor');

//...

app.use(express.statics(ckStaticsPath));
```
