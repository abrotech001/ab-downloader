<div align="center">

# 🚀 AB-DOWNLOADER
<img src="https://i.imgur.com/LyHic3i.gif" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=000000&background=60F8FF&center=true&vCenter=true&width=500&height=100&lines=THIS+IS+AB-DOWNLOADER;A+PROJECT+BY+ABRODEVTEAM;POWERFUL+MEDIA+TOOL)](https://git.io/typing-svg)

<br>

<img src="https://files.catbox.moe/d66kll.jpeg" width="180" alt="AB-Downloader Logo"/>

### 🎯 **Universal Media Downloader**
*Download content from Instagram, TikTok, Facebook, YouTube, and more!*

<br>

<a href="https://whatsapp.com/channel/0029VaidGkA6hENhcPlyuu1e">
  <img src="https://img.shields.io/badge/WhatsApp-Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp Channel">
</a>

<br>
<br>

[![npm version](https://img.shields.io/npm/v/ab-downloader.svg?style=for-the-badge&color=00d4aa)](https://www.npmjs.com/package/ab-downloader)
[![downloads](https://img.shields.io/npm/dm/ab-downloader.svg?style=for-the-badge&color=00d4aa)](https://www.npmjs.com/package/ab-downloader)
[![license](https://img.shields.io/npm/l/ab-downloader.svg?style=for-the-badge&color=00d4aa)](https://github.com/abrotech001/ab-downloader/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/abrotech001/ab-downloader.svg?style=for-the-badge&color=00d4aa)](https://github.com/abrotech001/ab-downloader/stargazers)

<img src="https://i.imgur.com/LyHic3i.gif" width="100%"/>

---

</div>

## 📦 Installation

### Node.js
```bash
npm install ab-downloader
```

### No more Python Config


---

## 🎨 Features

<div align="center">

| Platform | Status | Features |
|----------|--------|----------|
| 📸 **Instagram** | ✅ Active | Posts, Stories, Reels |
| 🎵 **TikTok** | ✅ Active | Videos, No Watermark |
| 📘 **Facebook** | ✅ Active | Videos, Posts |
| 🐦 **Twitter** | ✅ Active | Videos, Images |
| 🎬 **YouTube** | ✅ Active | Videos, Audio |
| 📁 **MediaFire** | ✅ Active | Direct Downloads |
| 🎬 **CapCut** | ✅ Active | Templates |
| 💾 **Google Drive** | ✅ Active | Public Files |
| 📌 **Pinterest** | ✅ Active | Images, Search |
| 🔄 **AIO** | 🔧 Maintenance | Universal Downloader |

</div>

---

## 🚀 Quick Start

### 🌟 AIO - All in One *(Under Maintenance)*
```javascript
const { aio } = require('ab-downloader');

const url = 'https://www.instagram.com/p/ByxKbUSnubS/';
aio(url)
  .then(data => console.log(data))
  .catch(err => console.error(err));
```

---

## 📱 Platform Examples

### 📸 Instagram
```javascript
const { igdl } = require('ab-downloader');

const url = 'https://www.instagram.com/p/ByxKbUSnubS/';
igdl(url)
  .then(data => {
    console.log('✅ Instagram content downloaded!');
    console.log(data);
  })
  .catch(err => console.error('❌ Error:', err));
```

<details>
<summary><b>View Sample Response</b></summary>

```json
[
 {
  developer: 'AbroCodes',
  contactme: 'Telegram: abrocodes',
  thumbnail: '...',
  url: '...'
  resolution: undefined,
  shouldRender: undefined
 }
]
```
</details>

### 🎵 TikTok
```javascript
const { ttdl } = require('ab-downloader');

const url = 'https://www.tiktok.com/@username/video/1234567890';
ttdl(url)
  .then(data => {
    console.log('✅ TikTok video downloaded!');
    console.log(data);
  })
  .catch(err => console.error('❌ Error:', err));
```
<details>
<summary><b>View Sample Response</b></summary>
  
```json
[
  {
    developer: 'AbroCodes',
    contactme: 'Telegram: abrocodes',
    title: ...,
    title_audio: ...,
    thumbnail: ...,
    video：［],
    audio: []
  }
]
```
</details>

### 📘 Facebook
```javascript
const { fbdown } = require('ab-downloader');

const url = 'https://www.facebook.com/watch/?v=1393572814172251';
fbdown(url)
  .then(data => {
    console.log('✅ Facebook video downloaded!');
    console.log(data);
  })
  .catch(err => console.error('❌ Error:', err));
```

<details>
<summary><b>View Sample Response</b></summary>
  
```json
[
  {
    developer: 'AbroCodes',
    contactme: 'Telegram: abrocodes',
    Normal_video: ...,
    HD: ...
  }
]
```
</details>

### 🐦 Twitter
```javascript
const { twitter } = require('ab-downloader');

const url = 'https://twitter.com/username/status/1229369819511709697';
twitter(url)
  .then(data => {
    console.log('✅ Twitter media downloaded!');
    console.log(data);
  })
  .catch(err => console.error('❌ Error:', err));
```

<details>
<summary><b>View Sample Response</b></summary>
  
```json
{
  developer: 'AbroCodes',
  contactme: 'Telegram: abrocodes',
  title: '...',
  url: [
  {
   hd: '...'
   },
   {
   sd: '...'
   }
]
}
```
</details>

### 🎬 YouTube
```javascript
const { youtube } = require('ab-downloader');

const url = 'https://youtube.com/watch?v=C8mJ8943X80';
youtube(url)
  .then(data => {
    console.log('✅ YouTube video downloaded!');
    console.log(data);
  })
  .catch(err => console.error('❌ Error:', err));
```

<details>
<summary><b>View Sample Response</b></summary>
  
```json
CHECK IT OUT YOURSELF ❤️
```
</details>

### 📁 MediaFire
```javascript
const { mediafire } = require('ab-downloader');

const url = 'https://www.mediafire.com/file/941xczxhn27qbby/file.apk/file';
mediafire(url)
  .then(data => {
    console.log('✅ MediaFire file downloaded!');
    console.log(data);
  })
  .catch(err => console.error('❌ Error:', err));
```
<details>
<summary><b>View Sample Response</b></summary>
  
```json
CHECK IT OUT YOURSELF ❤️
```
</details>

### 🎬 CapCut
```javascript
const { capcut } = require('ab-downloader');

const url = 'https://www.capcut.com/template-detail/7299286607478181121';
capcut(url)
  .then(data => {
    console.log('✅ CapCut template downloaded!');
    console.log(data);
  })
  .catch(err => console.error('❌ Error:', err));
```
<details>
<summary><b>View Sample Response</b></summary>
  
```json
CHECK IT OUT YOURSELF ❤️
```
</details>

### 💾 Google Drive
```javascript
const { gdrive } = require('ab-downloader');

const url = 'https://drive.google.com/file/d/1thDYWcS5p5FFhzTpTev7RUv0VFnNQyZ4/view';
gdrive(url)
  .then(data => {
    console.log('✅ Google Drive file downloaded!');
    console.log(data);
  })
  .catch(err => console.error('❌ Error:', err));
```

<details>
<summary><b>View Sample Response</b></summary>
  
```json
CHECK IT OUT YOURSELF ❤️
```
</details>

### 📌 Pinterest
```javascript
const { pinterest } = require('ab-downloader');

// Download by URL
const url = 'https://pin.it/4CVodSq';
pinterest(url)
  .then(data => {
    console.log('✅ Pinterest image downloaded!');
    console.log(data);
  })
  .catch(err => console.error('❌ Error:', err));

// Search Pinterest
pinterest('Nature Photography')
  .then(data => {
    console.log('✅ Pinterest search results!');
    console.log(data);
  })
  .catch(err => console.error('❌ Error:', err));
```

<details>
<summary><b>View Sample Response</b></summary>
  
```json
CHECK IT OUT YOURSELF ❤️
```
</details>

---

## 📖 Documentation

<div align="center">

### 🔗 **[Complete API Documentation](https://abrotech001.github.io/ab-downloader/)**

*Detailed guides, examples, and API references*

</div>

---

## ⚠️ Important Notes

> ### 🔒 **Legal & Ethical Use**
> - ✅ Only download **public** or **accessible** content
> - ✅ Ensure you have **permission** or **copyright** to download media
> - ✅ Respect **platform terms of service**
> - ❌ This application is **not affiliated** with any social media platform

> ### 🛡️ **Disclaimer**
> Users are responsible for complying with applicable laws and platform policies when using this downloader.

---

## 🤝 Contributing

<div align="center">

### We welcome contributions! 🎉


</div>

### 🐛 Found a Bug?
1. Contact Developer on Telegram: https://t.me/abrocodes
2. Submit an issue with detailed description
3. Include error logs and reproduction steps

---

## 📄 License

<div align="center">

**AB-Downloader** is licensed under the [MIT License](https://github.com/abrotech001/ab-downloader/blob/main/LICENSE)

*Feel free to use, modify, and distribute this software*

---

### 🌟 **Star this repo if you found it helpful!**

[![GitHub stars](https://img.shields.io/github/stars/abrotech001/ab-downloader.svg?style=social&label=Star)](https://github.com/abrotech001/ab-downloader/stargazers)

---

<sub>Made with ❤️ by [AbroCodes](https://github.com/abrotech001)</sub>

</div>
