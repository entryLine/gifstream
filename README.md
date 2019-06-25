gifStream is a JavaScript tool for creating large animated graphics on the web.

## Install

`npm i -S @entryline/gifstream`

## Example Usage

```javascript
  import GifStream from '@entryline/gifstream';

  const gifStream = new GifStream();

  const promise = gifStream.createGIF({
    'gifWidth': 100, // (Number in pixels) required
    'gifHeight': 100, // (Number in pixels) required
    'images': [
      {src:'someURL', text:'some frame text'}, Frame-specific text
      {src:'someURL', delay: 2000}, // An src is required
      {src:'someURL', delay: 1000} // delay ms
    ],
    'waterMarkXCoordinate': 10 // (Number in pixels) required if using watermark
    'waterMarkYCoordinate': 100, // (Number in pixels) required if using watermark
    'waterMarkHeight': 100, // (Number in pixels) required if using watermark
    'waterMark': image, // A javascript image
    'waterMarkWidth': 100, // (Number in pixels) required if using watermark
    'fontSize': someSize + 'px', // currently required
    'textXCoordinate': 0,
    'textYCoordinate': 0,
    'fontColor': '#fff',
    'fontWeight': '300',
    'fontFamily': 'Open Sans',
    'showFrameText': true, // Hide or show frame text
    'extraLastFrameDelay': 1000, // ...
    'text': '', // Text to show throughout
    'stroke': {
      'color': '#000',
      'pixels': 1
    },
    'pause': 1
    }, onGifComplete);
  };
```
## Cancel requests
Tested in chrome, Edge, and Firefox

```javascript
createGif() {
  gifStream.createGIF({this.options})
  this.isDownloading = true;
}
componentWillUnmount() {
  if (this.isDownloading) {
    gifStream.cancel();
  }
}
  ```
## Credits

gifstream would like to thank the following individuals and origanization for whom this project would not have been possible without:

@benJaki2, @ZachTRice, @nasa-gibs, Worldview, @jimmywarting, @gfranko, @ChaseWest
