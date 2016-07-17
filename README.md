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
        <div angular-youtube-upload access-token="VALID ACCESS TOKEN" data-video-title="{{name}}" data-video-desc="{{desc}}" > </div>
```

## License

The GPLv3 License

Copyright (c) 2010-2015 Pankaj Anupam, http://pankajanupam.com