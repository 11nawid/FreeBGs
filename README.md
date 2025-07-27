# 🌌 FreeBGs 

*A curated collection of free-to-use aesthetic videos, GIFs, and images for developers, designers, and creators.*  

[![GitHub Pages](https://img.shields.io/badge/🚀_Live_Preview-GitHub_Pages-blue?style=flat-square)](https://11nawid.github.io/FreeBGs/)
[![License](https://img.shields.io/badge/📄_License-Public_Domain-green?style=flat-square)](#license)
[![Contributions Welcome](https://img.shields.io/badge/✨_Contributions-Welcome-brightgreen?style=flat-square)](#contributing)

---


---

## 📦 Features

| Feature          | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| 🎥 **Media Preview**   | Live previews for videos, GIFs, and images                            |
| 📋 **One-Click Copy**  | Instantly copy media URLs to clipboard                                |
| 🎨 **Dark UI**         | Clean, eye-friendly interface with Tailwind CSS                       |
| 🎨 **Lighk UI**        | Clean, eye-friendly interface with Tailwind CSS                       |
| ⚡ **Zero Backend**    | Fully static site — fast loading, no dependencies                     |

---

## 🛠️ How to Use

### For Developers:
```html
<!-- Video Background -->
<video autoplay muted loop class="fixed w-full h-full object-cover z-0">
  <source src="[[https://11nawid.github.io/FreeBGs/media/videos/example.mp4](https://11nawid.github.io/FreeBGs/media/digital-art-isolated-house.jpg)](https://11nawid.github.io/FreeBGs/media/coffee-shop.1920x1080.mp4)" type="video/mp4">
</video>

<!-- CSS Background -->
<style>
  .hero-section {
    background: url('[https://11nawid.github.io/FreeBGs/media/images/abstract-wave.jpg](https://11nawid.github.io/FreeBGs/media/digital-art-isolated-house.jpg)') center/cover;
  }
</style>
```

### For Designers:
1. Visit [Live Preview](https://11nawid.github.io/FreeBGs/)
2. Browse media
3. Click "📋 Copy URL" on any asset
4. Paste into Figma/Photoshop or download directly

---

## 📂 Project Structure
```bash
FreeBGs/
├── index.html            # Main page with all js logic for fetching and displaying from media/ directory.
├── media/                # All assets
│   ├── index.html        # inside media for easy listing
│   ├── videos/           # .mp4/.webm/.ogg
│   ├── gifs/             # .gif
│   └── images/           # .jpg/.png/.webp
```


## 📜 License
All content is released under [Creative Commons Zero (CC0)](https://creativecommons.org/publicdomain/zero/1.0/) unless otherwise specified in file metadata. This means you can use, modify, and distribute the assets freely for any purpose.

---

*Made with ♥ by [@11nawid](https://github.com/11nawid) • [Report an Issue](https://github.com/11nawid/FreeBGs/issues)*
