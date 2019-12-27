<h1 align="center">
  <a href="https://mpv.io/">
    <img src="https://i.imgur.com/qQFg0aI.png" alt="mpv" width="200">
  </a>
  <br>mpv.js<br><br>
</h1>

<h4 align="center">
  All format embeddable player for Electron/NW.js applications.
  <br>Powered by marvelous <a href="https://mpv.io/">mpv</a>.
</h4>

<p align="center">
  <a href="https://travis-ci.org/Kagami/mpv.js">
    <img src="https://img.shields.io/travis/Kagami/mpv.js.svg" alt="Travis">
  </a>
  <a href="https://npmjs.org/package/mpv.js">
    <img src="https://img.shields.io/npm/v/mpv.js.svg" alt="NPM">
  </a>
</p>

## Get libmpv

In order to try mpv.js you need to install mpv library first.

* Windows: download [mpv-dev](https://mpv.srsfckn.biz/mpv-dev-latest.7z), unpack, put corresponding `mpv-1.dll` to `C:\Windows\system32`
* macOS: `brew install mpv`
* Linux: `apt-get install libmpv1 libavformat-dev`

## Example

![](https://i.imgur.com/tLFkATs.png)

```bash
git clone https://github.com/pavladan/mpv.js-on-react.git && cd mpv.js-on-react
npm install
# Only on Linux: npm run use-system-ffmpeg
npm start
```
