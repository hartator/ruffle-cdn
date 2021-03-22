# Ruffle web version on GitHub CDN

Ruffle ([ruffle.rs](https://ruffle.rs/)) doesn't seem to offer an official CDN for their Javascript and WebAssembly files. This repository is just a raw copy of Ruffle self hosted build files but hosted on GitHub Pages CDN.

Rufle is a super awesome project that makes any Flash content (`.swf` extensions) work back in new browsers. It works very well with basic Flash animations but also with complex Flash games that rely on legacy Flash internals.

To use on your website, just add:

```html
<script src="https://hartator.github.io/ruffle-cdn/ruffle/ruffle.js"></script>
```

And that's it! Every Flash animations and games should be working in new browsers.

Before:

![image](https://user-images.githubusercontent.com/307597/111931264-db0a4200-8a88-11eb-8b4b-ae27af074db5.png)

After:

![image](https://user-images.githubusercontent.com/307597/111931408-23c1fb00-8a89-11eb-8c80-2add3b536a20.png)
