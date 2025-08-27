# WebNav Hub 🇺🇦

[🇺🇸 English](README_EN.md) | [🇨🇳 中文](README.md) | [🇺🇦 Українська](README_UA.md)

A modern navigation website featuring Ukrainian flag color elements, with circular card design and responsive layout.

## ✨ Project Features

### 🎨 Design Highlights
- **Ukrainian Color Theme**: Deep integration of Ukrainian flag colors - blue (#005BBB) and yellow (#FFD700)
- **Circular Card Design**: Modern circular card layout abandoning traditional rectangles
- **Dynamic Visual Effects**: Rotating border animations, gradient backgrounds and glow effects
- **Responsive Layout**: Perfect adaptation for desktop, tablet and mobile devices

### 🌟 Functional Features
- **6 Navigation Categories**: AI Search, Social Media, Utilities, Tech News, Cloud Storage, Email
- **Smooth Scrolling**: Click navigation to auto-scroll to corresponding categories
- **URL Hash Support**: Direct navigation to specific categories via URL
- **Sticky Navigation**: Navigation bar remains fixed at top during scrolling
- **Font Awesome Icons**: Beautiful icons for each website

## 🚀 Quick Start

### Local Development

#### Method 1: Using Python
```bash
# Navigate to project directory
cd ge

# Start HTTP server
python -m http.server 8000

# Access in browser
http://localhost:8000
```

#### Method 2: Using Node.js
```bash
# Navigate to project directory
cd ge

# Start server
npx serve .

# Access the displayed URL
```

#### Method 3: Using VS Code Live Server
1. Install Live Server extension
2. Right-click `index.html` and select "Open with Live Server"

### Online Deployment

#### GitHub Pages Deployment
1. Push project to GitHub repository
2. Go to repository Settings → Pages
3. Select deployment branch (usually main)
4. Wait for deployment to complete

#### Vercel Deployment
1. Visit [Vercel](https://vercel.com)
2. Connect GitHub repository
3. One-click deployment

#### Netlify Deployment
1. Visit [Netlify](https://netlify.com)
2. Drag project folder to deployment area
3. Automatic deployment complete

## 📁 Project Structure

```
ge/
│
├── index.html          # Main page file (includes HTML, CSS, JS)
├── README.md          # Project documentation (Chinese)
├── README_EN.md       # Project documentation (English)
└── Other resources...
```

## 🎯 Category Content

### 🤖 AI Search
Contains 40+ AI tools and search platforms:
- **Mainstream AI**: ChatGPT, Claude, Gemini, Kimi, etc.
- **Chinese AI**: Qwen, Wenxin Yiyan, Doubao, Tencent Yuanbao, etc.
- **Development Tools**: OpenRouter, Websim, v0, etc.

### 📱 Social Media
Social platforms and related tools:
- **Social Platforms**: Facebook, Twitter, Instagram, Reddit, etc.
- **Video Download**: Y2mate, Cobalt, Savefrom, etc.
- **Deployment Platforms**: Vercel, Netlify, Railway, etc.

### 🛠️ Utilities
50+ online tools:
- **Domain Services**: Cloudflare, dynv6, free domains, etc.
- **Development Tools**: Cursor, PicGo, image processing, etc.
- **Network Tools**: Proxy services, IP lookup, DNS tools, etc.

### 📰 Tech News
Authoritative tech news sources:
- TechCrunch, Wired, The Verge, etc.

### ☁️ Cloud Storage
Mainstream cloud storage services:
- Google Drive, Dropbox, OneDrive, MEGA, etc.

### 📧 Email
Email service providers:
- Gmail, Outlook, ProtonMail, temporary email, etc.

## 🎨 Customization

### Modify Color Theme
Edit these variables in CSS:
```css
:root {
  --ukraine-blue: #005BBB;        /* Primary blue */
  --ukraine-yellow: #FFD700;      /* Primary yellow */
  --ukraine-light-blue: #0066cc;  /* Light blue */
  --ukraine-dark-blue: #003d82;   /* Dark blue */
}
```

### Add New Website Links
Copy existing card structure in HTML:
```html
<div class="link-card">
  <a href="Website URL" target="_blank"></a>
  <i class="fa-solid fa-icon-name"></i>
  <h3>Website Name</h3>
</div>
```

### Modify Categories
1. Update links in navigation bar
2. Add corresponding category titles
3. Create new link-grid areas

## 🔧 Technology Stack

- **HTML5**: Page structure
- **CSS3**: Style design (including responsive layout)
- **Vanilla JavaScript**: Interactive functionality
- **Font Awesome**: Icon library
- **Framework-free**: Pure static pages, easy to deploy

## 📱 Responsive Design

### Breakpoint Settings
- **Desktop**: > 1200px
- **Tablet**: 768px - 1200px
- **Mobile**: 480px - 768px
- **Small Mobile**: < 480px

### Card Size Adaptation
- **Desktop**: 7.5rem × 7.5rem
- **Tablet**: 6.5rem × 6.5rem
- **Mobile**: 5.5rem × 5.5rem
- **Small Screen**: 5rem × 5rem

## 🚀 Performance Optimization

- **Pure Static**: No server dependencies, fast loading
- **CDN Icons**: Using Font Awesome CDN
- **CSS Optimization**: Reasonable use of gradients and animations
- **Responsive Images**: Adapted for different screen densities

## 🇺🇦 Ukraine Support Statement

This project deeply integrates the classic color elements of the Ukrainian flag—blue representing the azure sky, yellow symbolizing golden wheat fields.

**We strongly condemn Russia's illegal aggression against Ukraine**, this military invasion violating international law has brought immense suffering to innocent civilians and disrupted international peace and stability.

**We hereby express our firm support for the Ukrainian people through this project**:
- 🌾 **Peace and Freedom**: May Ukraine restore peace soon and people regain freedom
- 💙 **Unity and Courage**: Tribute to the courage and unity shown by the Ukrainian people
- 🌻 **Hope and Reconstruction**: Looking forward to Ukraine's bright future and prosperous reconstruction
- ⚖️ **Justice and Sovereignty**: Supporting Ukraine's just struggle to defend national sovereignty and territorial integrity

Every use of this navigation site is a commitment to the values of peace, freedom and justice, and a silent protest against acts of aggression.

*Slava Ukraini! 🇺🇦*

## 🤝 Contributing

1. Fork this repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

## 📄 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details

## 🌟 Acknowledgments

- Thanks to [Font Awesome](https://fontawesome.com/) for beautiful icons
- Thanks to all included websites for quality services
- Special tribute to Ukraine's resilience and courage 🇺🇦

## 📞 Contact

For questions or suggestions, feel free to contact via:

- Submit Issue
- Create Pull Request
- Email contact (if provided)

---

**WebNav Hub** - Making web navigation better ✨