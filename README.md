# 🏦 Loan Renewal Calculator Pro

A premium, professional loan renewal calculator with bilingual support (English/Tagalog), dark mode, and print-ready agreements.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![PWA](https://img.shields.io/badge/PWA-ready-purple.svg)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔢 **Real-time Calculations** | Instant updates as you type |
| 🌐 **Bilingual Support** | English & Tagalog languages |
| 🌙 **Dark Mode** | Eye-friendly dark theme with persistence |
| 🖨️ **Print Agreements** | Professional 8.5" x 11" print layout |
| 📱 **PWA Support** | Install as mobile/desktop app |
| 📴 **Offline Ready** | Works without internet connection |
| ⚡ **Zero Dependencies** | Pure HTML/CSS/JS - no frameworks |
| 📐 **Responsive Design** | Works on all screen sizes |

---

## 🖼️ Screenshots

### Light Mode
![Light Mode](screenshots/light-mode.png)

### Dark Mode
![Dark Mode](screenshots/dark-mode.png)

### Print Agreement
![Print View](screenshots/print-view.png)

---

## 🚀 Quick Start

### Option 1: Direct Use
Simply open `index.html` in any modern web browser.

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8080

# Using Node.js
npx serve
```

### Option 3: Deploy Online
- **GitHub Pages**: Free hosting via repository settings
- **Netlify**: Drag & drop deployment
- **Vercel**: One-click deploy

---

## 📁 File Structure

```
loan-renewal-calculator/
├── index.html          # Main application (all-in-one)
├── manifest.json       # PWA manifest
├── sw.js              # Service worker
├── icon-192.png       # App icon (small)
├── icon-512.png       # App icon (large)
├── LICENSE            # MIT License
├── README.md          # This file
└── DEPLOYMENT_GUIDE.md # Deployment & monetization guide
```

---

## 🔧 Customization

### Change Default Interest Rate
In `index.html`, find and modify:
```javascript
const DEFAULT_INTEREST_RATE = 0.20; // 20% - change as needed
```

### Change Brand Colors
Modify CSS variables in `index.html`:
```css
:root {
    --primary: #667eea;      /* Main brand color */
    --secondary: #764ba2;    /* Gradient end color */
    --accent: #10b981;       /* Highlight/success color */
}
```

### Change App Title
Update the logo section in HTML:
```html
<h1 id="appTitle">Your Custom Title</h1>
<p id="appSubtitle">Your Custom Subtitle</p>
```

---

## 📊 Calculation Logic

| Field | Formula |
|-------|---------|
| **Interest** | Original Loan × Interest Rate |
| **Total Term** | (Original Loan + Interest) ÷ Daily Payment |
| **Total Paid** | Days Paid × Daily Payment |
| **Days Remaining** | Total Term - Days Paid |
| **Remaining Balance** | Days Remaining × Daily Payment |
| **Net Cash** | Renewal Loan - Remaining Balance |

---

## 🌐 Browser Support

| Browser | Support |
|---------|---------|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| Opera | ✅ Full |
| Mobile Browsers | ✅ Full |

---

## 📱 PWA Installation

### On Mobile (Android/iOS):
1. Open the app in browser
2. Tap "Add to Home Screen" or share menu
3. Confirm installation

### On Desktop (Chrome/Edge):
1. Open the app in browser
2. Click install icon in address bar
3. Confirm installation

---

## 🔒 Privacy

This application:
- ✅ Runs entirely in your browser
- ✅ Stores preferences locally (localStorage)
- ✅ Does NOT send data to any server
- ✅ Does NOT require registration
- ✅ Does NOT use cookies for tracking

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🤝 Support

For questions, customization requests, or support:
- 📧 Email: [your-email@example.com]
- 🐛 Issues: [GitHub Issues](https://github.com/hiprofitpro/loan-renewal-app-byIRA/issues)

---

## 📈 Changelog

### v1.0.0 (January 2025)
- ✅ Initial release
- ✅ Bilingual support (EN/TL)
- ✅ Dark mode with persistence
- ✅ Print agreement feature
- ✅ PWA support
- ✅ Customizable interest rate
- ✅ Previous balance deduction display
- ✅ Dark mode visibility fix for readonly fields

---

## 💡 Use Cases

- 💼 **Lending Businesses** - Track loan renewals professionally
- 🏪 **Pawnshops** - Calculate renewal terms quickly
- 🤝 **Cooperatives** - Manage member loans
- 👤 **Personal Use** - Track personal lending/borrowing
- 📊 **Financial Advisors** - Client loan analysis

---

Made with ❤️ for the Filipino lending community