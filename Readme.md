# VideoJS Resume

A VideoJS plugin to resume playback of a video at the point in time it was left.

## Usage

Requires [store.js](https://github.com/marcuswestin/store.js/) &amp; jQuery.

Include:
* `jquery.js`
* `store.js`
* `videojs-resume.min.css`
* `videojs-resume.min.js`

```js
  var player = videojs('example-video');
  player.Resume({
    uuid: 'UNIQUE_VIDEO_IDENTIFIER',
    playbackOffset: 5 // begin playing video this number of seconds before it otherwise would.
  });
```

## Example

[Example using Video.js 5](https://sprice.github.io/videojs-resume/)

## Support

Browser testing for this project has been graciously donated by [BrowserStack](https://www.browserstack.com).

## License

Licesned MIT. See LICENSE file.
