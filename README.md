# MIUI Theme Studio

## Complete Theme Development Suite — v4.3

**MIUI Theme Studio** is a browser-based toolkit for MIUI/HyperOS theme development on Xiaomi and Redmi devices. The dashboard currently includes **13 tools** for processing drawables, editing and resolving XML resources, recoloring and creating icons, generating 9-patch images, and organizing theme files.

All tools run in the browser. Files are processed locally by the tools; no project backend is required.

## 🚀 Launch

Open `index.html` in a modern browser, then select any tool card.

## 📱 Device & Browser Optimization

The dashboard is designed with these devices and environments in mind:

- **Redmi Note 15 5G** — touch-first interaction and mobile layout
- **Dell Latitude E5450** — 1366×768 laptop display
- Other Xiaomi/Redmi devices and desktop browsers
- Modern Chrome, Firefox, Edge, and Safari

> Actual performance depends on browser capabilities, available RAM, and the size of the files being processed.

## 🛠️ Tools Overview

### 1. MIUI Studio Pro — `miui_studio_pro.html`

All-in-one drawable and color processing workspace.

**Dashboard features:**
- Process drawables and colors in one place
- Extract, merge, and resolve resources
- Randomize colors
- Download processed output

### 2. Color Picker Pro — `color_picker_pro.html`

XML resource editor for common Android values.

**Dashboard features:**
- Upload XML and edit colors, strings, and dimensions
- Quick color picker and replace mode
- Search and go-to-serial navigation
- Undo/redo and download

### 3. Color Randomizer Pro — `color_randomizer_pro.html`

Inspect and randomize colors in theme XML.

**Dashboard features:**
- Upload `theme_values.xml` or `colors.xml`
- Inspect colors and search by name or HEX
- Randomize colors
- Download edited XML

### 4. Color Palette — `color_palette.html`

Tap-to-copy palette with multiple output formats.

**Dashboard features:**
- 16 ready-to-use colors
- Copy HEX with `#`, HEX without `#`, or 8-digit ARGB
- Live format preview
- Touch-friendly swatches

### 5. Color Replacer Pro — `color_replacer_pro.html`

Smart XML color editor with replacement and formatting tools.

**Dashboard features:**
- Undo/redo and sorting
- Live search
- Batch color replacement
- Root-tag changer
- Multiple download formats

### 6. XML Merger Pro — `xml_merger_pro.html`

Merge and resolve XML resources for theme workflows.

**Dashboard features:**
- Merge master and target XML
- Resolve dynamic colors
- Extract non-system colors
- BG/BTN color classifier
- Statistics and clean formatting

### 7. Icon Recolor Pro — `icon_recolor_pro.html`

Icon recoloring workspace with preview and batch processing.

**Dashboard features:**
- Live preview
- Primary and secondary color replacement
- Threshold controls
- Edge smoothing and blur
- HD tracing and ZIP batch export

### 8. Icon Maker Pro — `icon_maker_pro.html`

Create icons from a background and foreground overlay.

**Dashboard features:**
- Upload images or ZIP archives
- Background + overlay composition
- Adjust size and position
- Live preview
- Bulk output

### 9. HD Glossy Icons — `hd_glossy_icons.html`

Generate crisp launcher icons from package lists.

**Dashboard features:**
- Multi-list manager
- Glossy, flat, and no-shadow styles
- Live phone preview
- 12 color options
- 150×150 HD ZIP export

### 10. Drawable Studio Pro — `drawable_studio_pro.html`

Drawable processing and conversion workspace.

**Dashboard features:**
- Upload XML, PNG, or ZIP
- Resolve relative colors
- Batch vector conversion
- Fallback generation
- BG/BTN extraction

### 11. 9-Patch Maker Pro — `nine_patch_maker_pro.html`

Create Android `.9.png` assets and theme-ready bundles.

**Dashboard features:**
- 24 shapes
- Draggable guides
- Gradient and border controls
- Inner and outer shadows
- MIUI MTZ bundle export

### 12. Item Merger Pro — `item_merger_pro.html`

Directional filename/item copier.

**Dashboard features:**
- Left-to-right copy/paste workflow
- ZIP extraction
- Alphabetical A–Z navigation
- Instant search
- Paste names while keeping the image unchanged

### 13. Folder Generator Pro — `folder_generator_pro.html`

Generate multiple folder structures for theme projects.

**Dashboard features:**
- Set package name and subfolders
- Create multiple structures
- Copy structure as text
- Export structures as ZIP

## 📦 Installation & File Structure

No conventional installation is required. Download or clone the project and open `index.html`.

```text
miui-theme-studio/
├── index.html                  # Dashboard — 13 tools
├── miui_studio_pro.html        # 1. MIUI Studio Pro
├── color_picker_pro.html       # 2. Color Picker Pro
├── color_randomizer_pro.html   # 3. Color Randomizer Pro
├── color_palette.html          # 4. Color Palette
├── color_replacer_pro.html     # 5. Color Replacer Pro
├── xml_merger_pro.html         # 6. XML Merger Pro
├── icon_recolor_pro.html       # 7. Icon Recolor Pro
├── icon_maker_pro.html         # 8. Icon Maker Pro
├── hd_glossy_icons.html        # 9. HD Glossy Icons
├── drawable_studio_pro.html    # 10. Drawable Studio Pro
├── nine_patch_maker_pro.html   # 11. 9-Patch Maker Pro
├── item_merger_pro.html        # 12. Item Merger Pro
├── folder_generator_pro.html   # 13. Folder Generator Pro
└── README.md                   # Project documentation
```

**Important:** Keep the tool filenames unchanged unless you also update the corresponding `data-url` in `index.html`.

## 🎯 Usage Guide

### Getting Started

1. Open `index.html`.
2. Select a tool card or its launch button.
3. Upload the supported XML, image, or ZIP files.
4. Process or edit the content.
5. Export/download the result from that tool.

### Common Workflows

| Task | Tool | Typical workflow |
|---|---|---|
| Process drawable and color resources | MIUI Studio Pro | Upload → Process/Resolve → Download |
| Edit XML resources | Color Picker Pro | Upload → Search/Edit → Download |
| Randomize XML colors | Color Randomizer Pro | Upload → Randomize → Download |
| Copy a color code | Color Palette | Choose format → Tap swatch |
| Replace XML colors | Color Replacer Pro | Import → Search/Replace → Export |
| Merge XML resources | XML Merger Pro | Master + Target → Merge/Resolve → Export |
| Recolor icons | Icon Recolor Pro | Upload → Set colors → Apply/Export |
| Compose launcher icons | Icon Maker Pro | Background + Overlay → Position/Size → Export |
| Generate glossy icons | HD Glossy Icons | Package list → Style/Preview → ZIP |
| Convert/process drawables | Drawable Studio Pro | Upload → Convert/Resolve → Export |
| Create `.9.png` assets | 9-Patch Maker Pro | Select shape → Adjust guides/style → Export |
| Match item names | Item Merger Pro | Load files → Copy left → Paste right |
| Build folder scaffolding | Folder Generator Pro | Set package/subfolders → Generate → ZIP |

## 🎨 XML & Color Workflows

The dashboard includes dedicated tools for:
- XML resource editing and batch replacement
- Master/target XML merging
- Dynamic and relative color resolution
- Non-system color extraction
- Color randomization and palette copying

Supported resolution behavior depends on the individual tool and the XML references supplied.

## 📁 File Format Notes

The dashboard advertises support across tools for XML, PNG, ZIP, and selected image/archive formats. Exact input and output formats vary by tool.

| Format | Notes |
|---|---|
| XML | Resource editing, merging, and processing |
| PNG | Icon/drawable workflows |
| `.9.png` | 9-patch creation/export |
| ZIP | Batch input/output where supported |
| WEBP | Supported by applicable icon tools |
| JPG/JPEG, BMP | Supported by selected tools |
| CBZ | Supported by Item Merger Pro |

Do not assume every format is accepted by every tool; check the relevant tool's upload interface.

## 🖥️ System Requirements

- Modern browser with JavaScript enabled
- Recommended: 4 GB RAM or more for large ZIP/XML workloads
- Local storage/filesystem access for selecting and downloading files
- Internet may be required for external CDN assets on first load, depending on the tool

## ✨ Dashboard Features

- 13 tool cards in 5 dashboard categories
- Touch-friendly card and launch-button interaction
- Keyboard activation for cards
- Responsive layout for mobile and laptop screens
- Smooth press feedback
- Viewport-height adjustment for mobile browser UI

## 🆕 Dashboard v4.3

- 13 tools linked from the dashboard
- All dashboard `data-url` entries use the current tool filenames
- XML & Color Editors section ordering updated
- Dashboard optimized for Redmi Note 15 5G and Dell Latitude E5450
- Touch feedback and viewport-height handling included

## 🐛 Notes & Limitations

- Password-protected ZIP files may not be supported by the relevant tools.
- Very large XML/ZIP files can slow down processing, especially on low-RAM devices.
- Archive and image format support varies by tool.
- CDN-dependent assets may require an internet connection on first load.

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push the branch: `git push`
5. Open a Pull Request.

## 📄 License

Add or retain the project's applicable license file. If the project uses MIT, include the MIT License text in `LICENSE`.

## 🙏 Acknowledgments

The project may use the following libraries/assets where included by individual tools:

- [Font Awesome](https://fontawesome.com/) — icons
- [Google Fonts](https://fonts.google.com/) — typography
- [JSZip](https://stuk.github.io/jszip/) — ZIP handling
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) — file downloads

## 📊 Quick Reference

| # | Tool | Purpose | File |
|---:|---|---|---|
| 1 | **MIUI Studio Pro** | Drawable + color processing | `miui_studio_pro.html` |
| 2 | **Color Picker Pro** | XML resource editor | `color_picker_pro.html` |
| 3 | **Color Randomizer Pro** | XML color randomization | `color_randomizer_pro.html` |
| 4 | **Color Palette** | Copy HEX/ARGB codes | `color_palette.html` |
| 5 | **Color Replacer Pro** | XML color replacement | `color_replacer_pro.html` |
| 6 | **XML Merger Pro** | Merge/resolve XML | `xml_merger_pro.html` |
| 7 | **Icon Recolor Pro** | Icon recoloring | `icon_recolor_pro.html` |
| 8 | **Icon Maker Pro** | Background + overlay icons | `icon_maker_pro.html` |
| 9 | **HD Glossy Icons** | HD launcher icon generation | `hd_glossy_icons.html` |
| 10 | **Drawable Studio Pro** | Drawable conversion/processing | `drawable_studio_pro.html` |
| 11 | **9-Patch Maker Pro** | Android 9-patch assets | `nine_patch_maker_pro.html` |
| 12 | **Item Merger Pro** | Directional item copying | `item_merger_pro.html` |
| 13 | **Folder Generator Pro** | Folder structure generation | `folder_generator_pro.html` |

---

**Made with ❤️ for MIUI/HyperOS Theme Developers**  
*Dashboard version: v4.3 · 13 tools · Redmi Note 15 5G & Dell Latitude E5450*
