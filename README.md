Here's the fully updated `README.md` reflecting all **11 tools** currently in the dashboard.

```markdown
# MIUI Theme Studio

## 🎨 Complete Theme Development Suite — v3.5

**MIUI Theme Studio** is a professional, browser-based toolkit designed specifically for MIUI theme developers working with Xiaomi/Redmi devices. This complete suite provides **11 powerful tools** to streamline your theme creation workflow — all running 100% offline in your browser.

## 🚀 Live Demo

Access the full toolkit by opening `index.html` in any modern browser.

## 📱 Device Optimization

Specifically optimized for:

- **Redmi Note 15 5G** (FHD+, 120Hz touch)
- **Dell Latitude E5450** (1366×768) and other laptops
- All Xiaomi MIUI devices running Android 12+
- Desktop browsers (Chrome, Firefox, Edge, Safari)

## 🛠️ Tools Overview

### 1. MIUI Studio Pro — `miui_studio.html`

All-in-one drawable + color processor with Smart Convert and Icon Recolor integration.

**Features:**

- Upload XML/PNG/ZIP drawables with auto-type detection
- **Smart Convert All** — batch vector → PNG/9.png with cached preview reuse
- Extract colors from drawables automatically
- Merge with `colors.xml` + auto-download
- `theme_fallback.xml` generator
- **Built-in Icon Recolor engine** — Smart Convert output auto-loads here
- Dark/Light mode toggle
- Force Stop button for long operations

---

### 2. Color Picker Pro — `color_picker.html`

Advanced XML resource editor with quick color tools.

**Features:**

- Edit Colors, Strings, Booleans, Integers, Dimensions
- Quick Color mode (single-tap color picker)
- **Replace Mode** — apply one target color to many items
- Live search with debounce filtering
- Go-to-serial navigation
- Undo/Redo history (50 steps)
- Add new resources (color/string/bool/int/dimen)
- Download edited XML with timestamp comment

---

### 3. Icon Recolor Pro — `merger_icon.html`

Dual-color icon replacement studio with live preview and effects.

**Features:**

- **Live preview** with zoom controls (0.5× – 10×)
- **Dual Color mode** — primary + secondary dominant colors
- Adjustable thresholds for both colors
- **Edge Smoothing**, **Blur**, and **Edge Detect** effects
- WebP auto-conversion (edit as PNG, save back as WebP)
- Select All / Deselect / Invert selection
- Progress bar for Apply All + Compress ZIP
- 12 preset colors + custom picker

---

### 4. XML Merger Pro — `merger_xml.html`

Intelligent XML color/dimension merger with Material 3 resolution.

**Features:**

- Merge Master + Target XML (MIUI_Theme_Values format)
- **Smart Target Merge** — new colors up, existing colors from master down
- Resolve dynamic colors (Material 3, Android system, MIUI)
- Extract non-system colors only
- BG/BTN color classifier
- Multiple XML batch merge
- Color analysis with unique color summary
- Export BG / Export Text / Non-System quick actions
- Auto-format to MIUI_Theme_Values structure

---

### 5. Drawable Studio Pro — `merger_drawable.html`

Professional vector drawable → PNG converter.

**Features:**

- Auto-detect: Vector, Shape, Layer-List, Selector, Ripple, Inset, Clip, Scale, Rotate, Translate
- Batch convert to PNG/9.png with SVG rendering
- Extract @color/@android:color references
- Resolve relative colors from `colors.xml`
- **Advanced Folder** — recursively finds `drawable.zip` + `colors.xml`
- Auto-extract & auto-download workflow
- Fallback XML generator + Fallback Images ZIP

---

### 6. Icon Maker Pro — `merger_launcher.html`

Create custom launcher icons with background + overlay.

**Features:**

- **Background + Icon overlay** system
- Upload images or ZIP archives
- **Live preview** canvas (160×160)
- Move/center/position controls (X/Y offsets)
- Size presets (64, 72, 80, 96, 128, 192, 256)
- Custom width/height inputs
- Apply settings, then download **single PNG** or **ZIP batch**
- Original filename preservation
- Auto-saves state to localStorage

---

### 7. Color Replacer Pro — `merger_color.html`

Smart XML hex color editor with 8-digit ARGB support.

**Features:**

- Import XML → format & resolve colors automatically
- **Replace Selected** or **Replace All** with target hex
- Delete selected / Delete all colors
- Sort colors alphabetically
- Undo / Redo / Restore original
- **Convert all to 8-digit ARGB** (`#RRGGBBAA`)
- FAB navigation: Top / Bottom / Go-to-serial
- 12 preset colors + custom color picker
- Download resolved `theme_values_resolved.xml`

---

### 8. Color Randomizer Pro — `color_randomizer.html`

Randomize every color in XML with guaranteed unique values.

**Features:**

- Upload `theme_values.xml` or `colors.xml`
- ARGB-safe parsing (6-digit, 8-digit, 3-digit, shorthand)
- Search by name or hex value
- **Unique random generation** — no duplicates (up to 16.7M colors)
- Usage context detection (background, text, icon, etc.)
- Per-color copy buttons (exact + resolved)
- View raw XML inline
- Reset to originals
- Toast notification system

---

### 9. Item Merger Pro — `merger_name.html`

Directional filename merger with drag-and-drop.

**Features:**

- **Left → Right directional mode** (toggle)
- Tap LEFT filename = copy, tap RIGHT filename = paste name (image unchanged)
- Upload images or ZIP/CBZ archives
- Alphabetical scroll bar (A–Z, 0–9, #)
- Instant search filtering
- Sort by name / date (asc/desc)
- Per-item copy/paste buttons
- Download pane as ZIP

---

### 10. Folder Generator Pro — `merger_folder.html`

Create multiple folder structures at once with ZIP export.

**Features:**

- Define package name + subfolders (one per line)
- **Stepper control** — 1 to 20 structures
- Each structure named `package-name-1`, `package-name-2`, etc.
- Preset: `drawable`, `values-color`, `values-night`, `merge-color`, `backup-color`
- Color-coded folder tags (backup, theme, drawable)
- Copy structure as text
- Download all as single ZIP
- Responsive dark UI

---

### 11. Color Palette — `color_pallate.html`

Tap-to-copy color palette with 3 copy formats.

**Features:**

- 16 ready colors (editable array)
- **Two toggles → three modes:**
  - ✅ ARGB ON → `#FF1686D0` (8-digit)
  - ✅ Hex ON → `#1686D0` (with #)
  - ⬜ Hex OFF → `1686D0` (without #)
- Live preview of what will be copied
- Tap any swatch → instant copy to clipboard
- Checkmark animation + toast confirmation
- Haptic vibration on mobile
- Works offline · fallback clipboard for `file://`

---

## 📦 Installation

No installation required! Pure HTML/CSS/JavaScript — runs entirely in the browser.

### Local Setup

1. Clone or download this repository
2. Open `index.html` in your browser
3. All tools accessible from the main dashboard

### File Structure
```

miui-theme-studio/
├── index.html # Main dashboard (11 tools)
├── miui_studio.html # 1. MIUI Studio Pro
├── color_picker.html # 2. Color Picker Pro
├── merger_icon.html # 3. Icon Recolor Pro
├── merger_xml.html # 4. XML Merger Pro
├── merger_drawable.html # 5. Drawable Studio Pro
├── merger_launcher.html # 6. Icon Maker Pro
├── merger_color.html # 7. Color Replacer Pro
├── color_randomizer.html # 8. Color Randomizer Pro
├── merger_name.html # 9. Item Merger Pro
├── merger_folder.html # 10. Folder Generator Pro
├── color_pallate.html # 11. Color Palette
└── README.md # Documentation

```

## 🎯 Usage Guide

### Getting Started
1. Open `index.html`
2. Tap any tool card to launch it
3. Upload your theme assets (XML, PNG, ZIP)
4. Process, edit, and download

### Common Workflows

| Task | Tool | Workflow |
|------|------|----------|
| Vector → PNG | Drawable Studio | Upload → Smart Convert All → ZIP |
| Icon recolor | Icon Recolor | Upload → Set colors → Apply All → ZIP |
| Merge XMLs | XML Merger | Master + Target → Merge → Download |
| Edit XML | Color Picker | Upload → Tap item → Edit → Download |
| Random colors | Color Randomizer | Upload → Randomize All → Download |
| Find & replace | Color Replacer | Import → Replace Selected → Download |
| Match filenames | Item Merger | Enable directional → Tap pairs |
| Make folders | Folder Generator | Set package → Stepper → ZIP |
| Make icons | Icon Maker | BG + Overlay → Position → ZIP |
| Copy hex codes | Color Palette | Tap swatch → auto-copy |

## 🎨 Color Resolution Support

- ✅ Android dynamic colors (`@android:color/*`)
- ✅ Material 3 (`m3_ref_palette_dynamic_*`)
- ✅ MIUI specific (`miuix_color_*`)
- ✅ Relative references (`@color/*`)
- ✅ Direct hex (3, 6, or 8 digit)

## 📁 File Format Support

| Format | Upload | Export |
|--------|:------:|:------:|
| XML | ✓ | ✓ |
| PNG | ✓ | ✓ |
| 9.png | ✓ | ✓ |
| ZIP | ✓ | ✓ |
| JPG / JPEG | ✓ | – |
| WEBP | ✓ | ✓ (round-trip) |
| BMP | ✓ | – |
| CBZ | ✓ | – |

## ⌨️ Keyboard Shortcuts

| Shortcut | Action | Tool |
|----------|--------|------|
| `Ctrl + Z` | Undo | Color Picker, Color Replacer |
| `Ctrl + Y` | Redo | Color Picker, Color Replacer |
| `Ctrl + M` | Merge | XML Merger |
| `Ctrl + S` | Download | XML Merger |
| `Ctrl + R` | Reset | XML Merger |
| `Alt + T` | Scroll to Top | Color Replacer |
| `Alt + B` | Scroll to Bottom | Color Replacer |
| `Alt + G` | Go to Serial | Color Replacer |
| `Enter` | Submit / Go | Various modals |

## 🔧 System Requirements

- **Browser:** Modern Chromium/Firefox/Safari with JS enabled
- **RAM:** 2 GB minimum (4 GB for large ZIPs)
- **Storage:** Local only (no uploads)
- **Internet:** Only for CDN assets on first load (Font Awesome, JSZip, FileSaver)

## 🌟 Key Features

- ✅ **Zero dependencies** after first CDN load
- ✅ **Touch-optimized** for Redmi Note 15 5G
- ✅ **Dark-themed UI** across all tools
- ✅ **Batch processing** with progress bars
- ✅ **Force Stop** button for long operations
- ✅ **ZIP support** for upload & download
- ✅ **Live preview** with zoom
- ✅ **Undo/Redo** in editors
- ✅ **MIUI_Theme_Values** native format
- ✅ **100% private** — no server uploads

## 🆕 What's New in v3.5

- ✅ **Color Palette** tool added (tap-to-copy, 3 formats)
- ✅ **11 Pro Tools** in unified dashboard
- ✅ **Smart Convert caching** — no duplicate rendering
- ✅ **Force Stop** overlay in MIUI Studio & Drawable Studio
- ✅ Responsive layouts for Dell Latitude E5450 + Redmi Note 15 5G
- ✅ Safe-area insets for modern notched phones

## 🐛 Known Issues

- Password-protected ZIPs not supported
- XML >10 MB may lag on low-RAM devices
- RAR requires conversion to ZIP
- WebP editing auto-converts (round-trips back on save)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push (`git push origin feature/my-feature`)
5. Open a Pull Request

## 📄 License

MIT License — see `LICENSE` for details.

## 🙏 Acknowledgments

- [Font Awesome](https://fontawesome.com/) — Icons
- [Google Fonts](https://fonts.google.com/) — Inter typeface
- [JSZip](https://stuk.github.io/jszip/) — ZIP handling
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) — Downloads

---

## 📊 Quick Reference

| # | Tool | Purpose | File |
|---|------|---------|------|
| 1 | **MIUI Studio Pro** | All-in-one processor | `miui_studio.html` |
| 2 | **Color Picker Pro** | XML resource editor | `color_picker.html` |
| 3 | **Icon Recolor Pro** | Dual-color icons | `merger_icon.html` |
| 4 | **XML Merger Pro** | Merge + resolve XML | `merger_xml.html` |
| 5 | **Drawable Studio Pro** | Vector → PNG | `merger_drawable.html` |
| 6 | **Icon Maker Pro** | BG + overlay icons | `merger_launcher.html` |
| 7 | **Color Replacer Pro** | Hex find & replace | `merger_color.html` |
| 8 | **Color Randomizer Pro** | Unique random colors | `color_randomizer.html` |
| 9 | **Item Merger Pro** | Directional file copy | `merger_name.html` |
| 10 | **Folder Generator Pro** | Multi-structure creator | `merger_folder.html` |
| 11 | **Color Palette** | Tap-to-copy hex/ARGB | `color_pallate.html` |

---

**Made with ❤️ for MIUI Theme Developers | Optimized for Redmi Note 15 5G**
```

### ✅ Summary of Changes

| Section                 | What Changed                                                                            |
| ----------------------- | --------------------------------------------------------------------------------------- |
| **Header**              | Updated to v3.5, "11 tools"                                                             |
| **Device Optimization** | Added Dell Latitude E5450                                                               |
| **Tools Overview**      | All 11 tools documented (was 6)                                                         |
| **File names**          | Corrected to match actual filenames (`color_picker.html`, `merger_launcher.html`, etc.) |
| **File Structure**      | Complete tree with all 12 HTML files                                                    |
| **Workflows**           | Added common workflow table for all 11 tools                                            |
| **Keyboard Shortcuts**  | Added missing shortcuts from Color Replacer                                             |
| **File Format Support** | Confirmed WEBP round-trip support                                                       |
| **What's New**          | New v3.5 changelog                                                                      |
| **Quick Reference**     | Complete 11-tool table with exact filenames                                             |

All filenames in the README now exactly match the tools present in your `index.html`, so every `data-url` link will resolve correctly.
