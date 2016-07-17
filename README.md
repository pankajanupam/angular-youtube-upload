# angular-youtube-upload
This is a angular directive to upload file / blob to youtube channel.

Angular implementation of [YouTube v3 API](https://developers.google.com/youtube/v3/docs/)

## Installation

You can install this package with `bower`.

### bower

```shell
bower install angular-youtube-upload
```

Add a `<script>` to your `index.html`:

```html
<script src="/bower_components/angular-youtube-upload/angular-youtube-upload.js"></script>
```

Then add `ngpYoutubeUpload` as a dependency for your app:

```javascript
angular.module('myApp', ['ngpYoutubeUpload']);
```

##Uses

Simply use the directive in a template. 
```html
<div angular-youtube-upload access-token="VALID ACCESS TOKEN" data-video-title="{{name}}" data-video-desc="{{desc}}" ></div>
```

## License

The MIT License (MIT)

Copyright (c) 2016 Pankaj Anupam, http://pankajanupam.com

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.