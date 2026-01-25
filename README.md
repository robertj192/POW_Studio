# POW! Studio 💥

<div align="center">

**Professional Comic Layout Tool**

*Where Comics Come to Life!*

![POW! Studio Interface](docs/images/interface-overview.png?v=2)

[![Version](https://img.shields.io/badge/version-1.079-blue.svg)](https://github.com/robertj192/POW_Studio)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Made with Love](https://img.shields.io/badge/made%20with-❤️-red.svg)](https://github.com/robertj192/POW_Studio)

[Features](#-features) • [Getting Started](#-getting-started) • [Usage](#-usage) • [About](#-about) • [Contributing](#-contributing)

</div>

---

## 📖 About

**POW! Studio** was born from a lifelong passion for comics and a simple need: creating professional comic book layouts shouldn't require expensive software or a steep learning curve.

I've been a huge comic fan since I was a kid - the art, the storytelling, the way panels guide your eye through the narrative. When I started working on my "Fire and Ice" series, I found myself frustrated with existing tools. They were either:
- Too complex (full illustration suites when I just needed layout)
- Too expensive (subscription-based tools)
- Too limited (basic templates with no flexibility)

So I did what any developer would do: I built my own tool. But I didn't do it alone.

### 🤖 Building with Big C

This project was created through "vibe coding" with Claude (affectionately known as Big C) - an AI assistant from Anthropic. Together, we iterated on features, solved problems, and built something that actually works the way comic creators think. Big C became more than just a coding partner; he became the mascot and spirit of POW! Studio.

The result? A **free, open-source, browser-based** comic layout tool that focuses on what matters most: **creating professional panel layouts, organizing your story, and exporting pitch-ready scripts**.

No installation. No subscription. No bloat. Just you and your comic.

### 🤖 Meet Big C

Our mascot and tutorial guide! Big C is a heroic robot who believes in one thing: **YOU CAN CREATE COMICS TOO!**

---

## ✨ Features

### 🎨 Panel Creation
- **Rectangle Panels** - Quick, precise panel creation
- **Freeform Polygons** - Custom shapes for dynamic layouts
- **Panel Templates** - 9 pre-built layouts (grids, vertical, horizontal, widescreen, splash, manga, Z-layout)
- **Custom Templates** - Save your own layouts for reuse
- **Grid Snapping** - Perfect alignment every time
- **Auto-Numbering** - Organize your panel flow
- **Lock Panels** - Prevent accidental moves

### 💬 Text & Captions
- **Text Wrapping** - Automatic text flow
- **Caption Boxes** - Professional narration boxes
- **14 Google Fonts** - From comic to professional
- **Full Formatting** - Size, color, alignment
- **Smart Editing** - Double-click to edit, auto-regroup

### 💥 Badges & Effects
- **9 Built-in Badges** - POW!, BAM!, ZAP!, BOOM!, SPLAT!, KAPOW!, WHOOSH!, CRASH!, THUD!
- **Custom Badge Upload** - Use your own action graphics
- **Drag & Rotate** - Perfect positioning
- **Scalable** - Resize without quality loss

### 📄 Page Management
- **Multi-Page Support** - Create entire comics
- **Page Properties** - Number, notes, background per page
- **Page Navigation** - Easy switching between pages
- **Page Thumbnails** - Visual overview

### 📝 Professional Script Export
- **Comic Script Format** - Industry-standard export
- **Page-by-Page** - Organized by page and panel
- **Panel Notes** - Action, dialogue, descriptions
- **Page Notes** - Plot, setting, mood
- **Ready to Pitch** - Perfect for publisher submissions

### 🎨 Customization
- **3 Themes** - Dark, Light, High Contrast
- **Custom Keyboard Shortcuts** - Work your way
- **Custom Badges** - Replace built-ins with your style
- **Settings Persistence** - Saves automatically

### 📤 Export Options
- **PNG Export** - High-quality image output
- **PDF Export** - Single page or full comic
- **ZIP Projects** - Save and resume anytime
- **Comic Script** - Text format for pitching

### 🔧 Professional Tools
- **Undo/Redo** - 50-step history
- **Zoom & Pan** - Precision control (10%-500%)
- **Dimension Overlay** - Real-time panel measurements
- **Layer Management** - Organize your elements
- **Grid & Guides** - Perfect alignment

---

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Edge, Firefox, Safari)
- That's it! No installation required.

### Quick Start

**Option 1: Clone the Repository** (Recommended)
```bash
# Clone the repository
git clone https://github.com/robertj192/POW_Studio.git

# Navigate to the directory
cd POW_Studio

# Open the HTML file in your browser
# (Double-click POW_Studio-v1.079.html or use your browser's File → Open)
```

**Option 2: Direct Download**
1. Click the green **"Code"** button on GitHub
2. Select **"Download ZIP"**
3. Extract the ZIP file
4. Open `POW_Studio-v1.079.html` in your browser

**Then:**
- Accept the legal disclaimer
- Start creating comics!

**Note:** Cloning creates the full directory structure including `docs/images/` for screenshots.

---

## 💻 Usage

### Creating Your First Comic

1. **Create Panels**
   - Click "Create Panel (Rectangle)" or "Create Panel (Freeform)"
   - Click and drag to draw panels
   - Use grid snapping for alignment

2. **Add Images**
   - Upload your artwork
   - Drag onto panels
   - Images automatically clip to panel shapes

3. **Add Text**
   - Use "Add Text" for dialogue
   - Use "Caption Box" for narration
   - Text wraps automatically

4. **Add Impact**
   - Click badge buttons to add sound effects
   - Rotate and scale for dynamic effect
   - Upload custom badges in Settings

5. **Organize Your Story**
   - Set page numbers in Page Properties
   - Add page notes (plot, setting, mood)
   - Add panel notes (action, dialogue)
   - Auto-number panels for workflow

6. **Export**
   - **Tools → Export Comic Script** - For pitching
   - **Tools → Export Comic PDF** - For sharing
   - **Tools → Save Project** - To continue later

### Keyboard Shortcuts (Customizable!)

| Action | Shortcut |
|--------|----------|
| Undo | `Ctrl/Cmd + Z` |
| Redo | `Ctrl/Cmd + Y` |
| Zoom In | `Ctrl/Cmd + =` |
| Zoom Out | `Ctrl/Cmd + -` |
| Reset Zoom | `Ctrl/Cmd + 0` |
| Pan Canvas | `Space + Drag` |

*All shortcuts can be customized in Settings!*

---

## 🎯 Use Cases

### For Comic Creators
- Layout entire comic books
- Plan panel flow and composition
- Export professional scripts for pitching
- Organize multi-page stories

### For Writers
- Visualize comic scripts
- Plan page layouts
- Export formatted scripts
- Pitch to artists with visual layouts

### For Educators
- Teach comic structure
- Visual storytelling lessons
- Sequential art principles
- Free tool for students

### For Hobbyists
- Create webcomics
- Make fan comics
- Design graphic novels
- Experiment with layouts

---

## 🛠️ Technical Details

### Built With
- **Fabric.js** - Canvas manipulation
- **jsPDF** - PDF generation
- **JSZip** - Project packaging
- **Vanilla JavaScript** - No frameworks, no dependencies
- **HTML5 Canvas** - High-performance rendering

### Browser Support
- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ❌ Internet Explorer (Not supported)

### File Formats
- **Import**: PNG, JPG, SVG, GIF (images and badges)
- **Export**: PNG, PDF, ZIP, TXT (comic scripts)

---

## 📚 Documentation

- **This README** - Complete guide and feature overview
- **Tutorial Comic** - Visual guide with Big C (🎨 *in progress!*)
- **GitHub Wiki** - In-depth documentation (coming soon!)
- **Video Tutorials** - Step-by-step guides (coming soon!)

---

## 💡 Usage & Modifications

**POW! Studio is open source under the MIT License.**

You're welcome to:
- ✅ Download and use it
- ✅ Fork and modify for your own use
- ✅ Create your own version
- ✅ Learn from the code

**⚠️ Security Notice:** This repository does not accept pull requests or code contributions. All code modifications are made exclusively by the repository owner to ensure security and quality control. If you modify the code, you are responsible for your own version's security.

**This repository is maintained as a personal project.** If you have suggestions or find bugs:
- 🐛 **Report Issues** - Use GitHub Issues for bug reports
- 💡 **Feature Requests** - Share ideas through GitHub Discussions
- 🌟 **Show Support** - Star the repo if you find it useful!

For major modifications or derivative works, please create your own repository.

---

## 🗺️ Roadmap

### v1.1 (Coming Soon)
- [ ] **Big C Tutorial Comic** - Complete visual guide featuring our heroic robot mascot
- [ ] Speech bubble tool (redesigned)
- [ ] Collaborative features
- [ ] Cloud save options

### v1.2 (Future)
- [ ] Animation export (GIF)
- [ ] More badge packs
- [ ] AI-assisted layout suggestions
- [ ] Mobile app version

### Community Requests
Vote for features by starring issues labeled `enhancement`!

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Note**: While the software is open source, you are responsible for all content you create with it. See the disclaimer in the application for full terms.

---

## 🙏 Acknowledgments

- **Claude (Anthropic)** - Development partner and Big C's inspiration
- **Fabric.js Team** - Amazing canvas library
- **Comic Community** - Feedback and inspiration
- **You!** - For believing in POW! Studio

---

## 🌟 Show Your Support

If POW! Studio helps you create comics, please:

- ⭐ Star this repository
- 🐛 Report bugs through GitHub Issues
- 💡 Suggest features
- 📢 Share with fellow creators

---

<div align="center">

### 🤖 Big C Says: "YOU CAN CREATE COMICS TOO!" 💥

Made with ❤️ for the comic creation community

**POW! Studio** - Where Comics Come to Life

[⬆ Back to Top](#pow-studio-)

</div>
