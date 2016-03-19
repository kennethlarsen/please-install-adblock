## Please install AdBlock!
An open source script for telling your readers to please install AdBlock.

## How to use
All you need is adframe.js. AdBlock blocks all js-stuff named adframe.

`<script src="adframe.js"></script>`

Now you're able to tell your users to install AdBlock

``````

if(adblock) {
  //adblock is installed and enabled on this site
  alert("Thanks for using AdBlock!");
} else {
  alert("Please install AdBlock!");
}
```
## Demo
http://kennethlarsen.github.io/pleaseinstalladblock/
