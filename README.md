# MIUI Theme Studio

## Redmi Note 15 5G Optimized Theme Development Suite

MIUI Theme Studio is a professional, browser-based toolkit designed specifically for MIUI theme developers working with Redmi Note 15 5G and other Xiaomi devices. This complete suite provides **six powerful tools** to streamline your theme creation workflow.

## 🚀 Live Demo

Access the full toolkit at: [MIUI Theme Studio](#)

## 📱 Device Optimization

This toolkit is specifically optimized for:

- **Redmi Note 15 5G** (FHD+ display, 120Hz touch response)
- All Xiaomi MIUI devices running Android 12+
- Desktop browsers (Chrome, Firefox, Edge)

## 🛠️ Tools Overview

### 1. Drawable Studio Pro

Professional vector drawable processor for MIUI themes.

**Features:**

- Upload XML/PNG/ZIP drawable files
- Batch convert vector XML to PNG/9.png format
- Extract and resolve relative colors
- Generate `theme_fallback.xml` automatically
- Extract background and button drawables
- ZIP batch processing with preview

---

### 2. IconForge Pro

Dual-color icon replacement studio with live preview.

**Features:**

- Real-time icon preview with zoom controls
- Primary/secondary color replacement with thresholds
- Edge smoothing and blur effects
- Trace HD mode for crisp results
- Batch processing with ZIP export
- Preset color palettes

---

### 3. XML Merger Pro

Intelligent XML color and dimension merger.

**Features:**

- Merge master/target XML files
- Resolve dynamic colors (Material 3 + Android)
- Extract non-system colors only
- BG/BTN color classifier
- Auto-format to MIUI_Theme_Values structure
- Color resolution visualization

---

### 4. Color Replacer Tool

Advanced XML color editor with hex replacement.

**Features:**

- Undo/Redo support for safe editing
- Root tag changer
- Live color search with filtering
- Batch replace selected or all colors
- Sort colors alphabetically
- Serial navigation for large files
- Multiple format downloads
- Extract non-system colors

---

### 5. Name Merger Tool

Drag-and-drop filename management tool.

**Features:**

- Directional name copying (Left → Right mode)
- ZIP archive extraction support
- Alphabetical scroll navigation
- Instant search filtering
- Smart paste functionality
- Sort by name or date

---

### 6. Icon Maker Pro ✨ **NEW**

Professional icon creation tool with background overlay.

**Features:**

- **Background + Icon overlay** system
- Upload single/multiple images or ZIP archives
- **Live preview** with real-time updates
- **Position controls** (move, center)
- **Size adjustment** with presets (64-256px)
- **Batch processing** - all icons with same settings
- **Original filename preservation** on download
- **Single download** or **ZIP export**
- **Transparent background support**
- **Smart file chooser** - handles images and ZIPs

**Workflow:**
```
Upload Background → Upload Front Icons → Select Icon → Adjust Position/Size → Apply → Download Single/ZIP
```

---

## 📦 Installation

No installation required! This is a pure HTML/CSS/JavaScript toolkit that runs entirely in your browser.

### Local Setup

1. Clone this repository:

```bash
git clone https://github.com/yourusername/miui-theme-studio.git
```

2. Open `index.html` in your browser

3. All tools are accessible from the main dashboard

## 🎯 Usage Guide

### Getting Started

1. Launch `index.html` on your Redmi Note 15 5G or desktop
2. Click any tool card to access its functionality
3. Upload your theme assets (XML, PNG, or ZIP files)
4. Process, edit, and download your themed resources

### Tool-Specific Workflows

#### Drawable Studio Pro Workflow
```
Upload XML/PNG → Resolve Colors → Convert Vector → Generate Fallback → Download ZIP
```

#### IconForge Pro Workflow
```
Upload Icons → Select Color Mode → Adjust Thresholds → Apply Effects → Preview → Export ZIP
```

#### XML Merger Workflow
```
Load Master XML → Load Target XML → Click Merge → Download Merged File
```

#### Color Replacer Workflow
```
Load XML → Show Colors → Select Target Colors → Choose New Hex → Replace → Download
```

#### Name Merger Workflow
```
Upload Images → Toggle Directional Mode → Tap Left Filename → Tap Right Filename → Download
```

#### Icon Maker Pro Workflow ✨
```
Upload Background → Upload Front Icons (Image/ZIP) → Select Icon → Adjust Position & Size → Apply → Download (Single/ZIP)
```

## 🎨 Color Resolution Support

The toolkit supports resolution of:

- Android dynamic colors (`@android:color/*`)
- Material 3 dynamic colors (`m3_ref_palette_dynamic_*`)
- MIUI specific colors (`miuix_color_*`)
- Relative color references (`@color/*`)
- Direct hex values

## 📁 File Format Support

| Format   | Upload | Export |
| -------- | ------ | ------ |
| XML      | ✓      | ✓      |
| PNG      | ✓      | ✓      |
| 9.png    | ✓      | ✓      |
| ZIP      | ✓      | ✓      |
| JPG/JPEG | ✓      | -      |
| WEBP     | ✓      | -      |
| BMP      | ✓      | -      |
| GIF      | ✓      | -      |
| ICO      | ✓      | -      |
| AVIF     | ✓      | -      |

## 💡 Keyboard Shortcuts

| Shortcut       | Action                     |
| -------------- | -------------------------- |
| `Ctrl + Z`     | Undo (Color Replacer)      |
| `Ctrl + Y`     | Redo (Color Replacer)      |
| `Ctrl + M`     | Merge (XML Merger)         |
| `Ctrl + S`     | Download (XML Merger)      |
| `Ctrl + R`     | Reset (XML Merger)         |
| `Ctrl + Enter` | Apply (Icon Maker)         |
| `Ctrl + S`     | Download Single (Icon Maker) |
| `Ctrl + Shift + S` | Download ZIP (Icon Maker) |
| `Escape`       | Blur focus (Icon Maker)    |

## 🔧 System Requirements

- **Browser:** Modern browser with JavaScript enabled
- **RAM:** 2GB minimum (4GB recommended for large ZIP files)
- **Storage:** Local storage for file processing
- **Internet:** Required only for CDN assets (Font Awesome, Google Fonts, JSZip, FileSaver)

## 📂 Project Structure

```
miui-theme-studio/
├── index.html              # Main dashboard
├── icon_maker.html         # Icon Maker Pro ✨ NEW
├── merger_color.html       # Color Replacer Tool
├── merger_drawable.html    # Drawable Studio Pro
├── merger_icon.html        # IconForge Pro
├── merger_name.html        # Name Merger Tool
├── merger_xml.html         # XML Merger Pro
└── README.md               # Documentation
```

## 🌟 Key Features Summary

- ✅ **Zero dependencies** - Works offline after initial load
- ✅ **Touch-optimized** - Perfect for Redmi Note 15 5G
- ✅ **Material Design** - Modern, dark-themed UI
- ✅ **Batch processing** - Handle multiple files at once
- ✅ **ZIP support** - Upload and extract archives
- ✅ **Live preview** - Real-time visual feedback
- ✅ **Undo/Redo** - Safe editing workflow
- ✅ **Color resolution** - Automatic relative color resolution
- ✅ **MIUI format** - Native `MIUI_Theme_Values` support
- ✅ **Icon creation** - Background + overlay system ✨

## 🆕 What's New in v3.1

- ✅ **Icon Maker Pro** - New tool for creating custom icons
- ✅ **Smart file chooser** - Handles images and ZIPs in both upload sections
- ✅ **Preview grid** - Shows all icons with background preview
- ✅ **Original filename preservation** - Downloads keep original names
- ✅ **Transparent background support** - Perfect for launcher icons

## 🐛 Known Issues

- ZIP files with password protection are not supported
- Very large XML files (>10MB) may cause performance issues
- RAR format requires conversion to ZIP for full support

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for Inter typeface
- JSZip for ZIP file handling
- FileSaver.js for download functionality

## 📞 Support

For issues or feature requests, please open an issue on GitHub or contact the maintainer.

---

**Made with ❤️ for MIUI Theme Developers | Optimized for Redmi Note 15 5G**

---

## 📊 **Quick Reference Table**

| Tool | Purpose | Key Feature |
|------|---------|-------------|
| **Drawable Studio** | Vector → PNG conversion | Batch processing |
| **IconForge** | Color replacement | Dual-color editing |
| **XML Merger** | Color/dimension merge | Dynamic color resolution |
| **Color Replacer** | XML color editing | Undo/Redo support |
| **Name Merger** | Filename management | Drag & drop |
| **Launcher Icon** ✨ | Icon creation | BG + overlay system |
