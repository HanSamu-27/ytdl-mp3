# YoutubeDL

[![Descarga](https://i.postimg.cc/LXWmBnHM/images.png)](https://github.com/HanSamu-27/ytdl-mp3/releases/latest)

## Instalación

```bash
npm install github:HanSamu-27/ytdl-mp3

```

## Uso

```javascript
var han = require('ytdl-mp3')

var url = 'https://youtu.be/i1Tzb4-J-_k?feature=shared'
han.ytdl(url).then(info => {
console.log("💮 Titulo:", info.title)
console.log("💮 Thumbnail:", info.thumbnail)
console.log("💮 Quality:", info.quality)
console.log("💮 ID:", info.id)
console.log("💮 Url:", info.url)
console.log("💮 Audio:", info.dl_url)
}).catch(error => {
console.error("Error ://")
})
```

# Creador

[![Owner](https://i.postimg.cc/zBW1Pjj6/c596864f-25dd-425c-b9df-8fe84e3c3860.jpg)](https://wa.me/+5491168239750?text=Hola+Samu)

```html
<style>
@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}
@keyframes underline {
  from { width: 0; }
  to { width: 100%; }
}
.signature {
  font-family: 'Courier New', monospace;
  white-space: nowrap;
  overflow: hidden;
  border-right: 2px solid;
  width: 100%;
  animation: typing 3s steps(40, end), blink-caret 0.75s step-end infinite;
}
.underline {
  display: inline-block;
  height: 2px;
  background-color: #000;
  animation: underline 3s ease-in-out;
}
</style>

<div>
  <span class="signature">By @Samush$_</span>
  <div class="underline"></div>
</div>
