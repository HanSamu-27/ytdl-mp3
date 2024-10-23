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

            
