<div align="center">

# 🚀 AB-Downloader

![AB-Downloader Logo](https://files.catbox.moe/5msbx0.png)

### 🎯 **Universal Media Downloader**
*Download content from Instagram, TikTok, Facebook, YouTube, and more!*

[![npm version](https://img.shields.io/npm/v/ab-downloader.svg?style=for-the-badge&color=00d4aa)](https://www.npmjs.com/package/ab-downloader)
[![downloads](https://img.shields.io/npm/dm/ab-downloader.svg?style=for-the-badge&color=00d4aa)](https://www.npmjs.com/package/ab-downloader)
[![license](https://img.shields.io/npm/l/ab-downloader.svg?style=for-the-badge&color=00d4aa)](https://github.com/abrotech001/ab-downloader/blob/main/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/abrotech001/ab-downloader.svg?style=for-the-badge&color=00d4aa)](https://github.com/abrotech001/ab-downloader/stargazers)

---

</div>

## 📦 Installation

### Node.js
```bash
npm install ab-downloader
```

### Python
```bash
pip install ab-downloader
```

> 📚 **Python Documentation**: [Complete Python Setup Guide](https://github.com/abrotech001/ab-downloader-py/tree/main#usage)

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

[![GitHub Issues](https://img.shields.io/github/issues/abrotech001/ab-downloader.svg?style=for-the-badge&color=red)](https://github.com/abrotech001/ab-downloader/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/abrotech001/ab-downloader.svg?style=for-the-badge&color=blue)](https://github.com/abrotech001/ab-downloader/pulls)

</div>

### 🐛 Found a Bug?
1. Check existing [issues](https://github.com/abrotech001/ab-downloader/issues)
2. Create a new issue with detailed description
3. Include error logs and reproduction steps

### 💡 Want to Contribute?
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

<div align="center">

**AB-Downloader** is licensed under the [MIT License](https://github.com/abrotech001/ab-downloader/blob/main/LICENSE)

*Feel free to use, modify, and distribute this software*

---

### 🌟 **Star this repo if you found it helpful!**

[![GitHub stars](https://img.shields.io/github/stars/abrotech001/ab-downloader.svg?style=social&label=Star)](https://github.com/abrotech001/ab-downloader/stargazers)

---

<sub>Made with ❤️ by [AbroTech](https://github.com/abrotech001)</sub>

</div>
```

This enhanced README.md features:

🎨 **Visual Enhancements:**
- Modern badges and shields
- Organized sections with emojis
- Professional table layouts
- Centered alignments for key sections

🚀 **Improved Structure:**
- Clear feature matrix table
- Enhanced code examples with success messages
- Better organized platform sections
- Professional contributing guidelines

📱 **Modern Styling:**
- Consistent emoji usage
- Color-coded badges
- Professional disclaimer section
- Enhanced documentation links

The markdown uses modern GitHub-flavored markdown features while maintaining readability and professional appearance!
