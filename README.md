# mediaIcons
A centralized repository for logos, icons, images, and other media assets — optimized, organized, and ready for cross-repository use.

This repository serves as a centralized collection for media files (logos, icons, images, etc.), allowing you to easily link to them from other projects via direct links or as a submodule. All images are optimized for fast loading and compatibility.

## Features

**Automatic Image Optimization** — Reduces file size without compromising quality.

**Conversion to Modern Formats:**
* **`.webp`** — for maximum compression, as well as support for animations and transparency.
* **`.ico`** — for favicons and browser compatibility.

**Support for Multi-sized Icons** — Different sizes for various devices (16x16, 32x32, 64x64, 256x256, etc.).

**Ready-to-use CDN Links** — You can directly embed them into HTML, Markdown, or CMS platforms.

Easy Updates and Versioning — Use Git tags for stable versions of media files.

## Repository Structure

```
mediaIcons/
├── icons/              # Icons for communities, gaming communities and applications/programs
├── media/              # Stickers, logos and other media files
└── README.md           # This file
```

## How to Use

Simply copy the direct link to the file you need from GitHub and paste it into your project:

```html
<img src="https://raw.githubusercontent.com/Morunka/mediaIcons/refs/heads/main/media/logos/studio/icon.ico">
```

Or add it as a Git submodule:

```bash
git submodule add [https://github.com/Morunka/mediaIcons.git](https://github.com/Morunka/mediaIcons.git) assets/mediaIcons
```

## Contribution
PRs with new images, optimization improvements, or structural changes are welcome. When adding files, please:
* Convert to `.webp` and `.ico` (if applicable).
* Adhere to the folder structure.
* Optimize the size (use tools like picflow.com, Squoosh or ImageOptim).

## License
Unless otherwise specified, the contents of this repository are distributed under the MIT License. Please check individual files for their specific licenses, as some images may have their own restrictions.