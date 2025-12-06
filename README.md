# ⚕️ Holliday-Segar Fluid Calculator

A professional web-based medical calculator for determining pediatric IV fluid maintenance requirements using the Holliday-Segar method.

![Calculator Preview](https://img.shields.io/badge/status-active-success) ![Platform](https://img.shields.io/badge/platform-web-blue) ![License](https://img.shields.io/badge/license-MIT-green)

## 🌐 Live Demo

**[Launch Calculator →](https://bloemsarel.github.io/Calculator/)**

## 📱 Features

- ✅ **Holliday-Segar Formula** (100/50/20 ml/kg method)
- ✅ **Rehydration Calculation** (20 ml/kg)
- ✅ **Mobile-Friendly** - Works on all devices
- ✅ **Offline Capable** - Works without internet
- ✅ **Installable** - Add to home screen as an app
- ✅ **Professional Interface** - Clean medical design
- ✅ **No Login Required** - Instant access
- ✅ **Free & Open Source**

## 🧮 Calculations Provided

1. **Daily Fluid Requirement** (mL/day)
2. **Hourly Maintenance Rate** (mL/hr)
3. **Rehydration Volume** (mL)
4. **Weight Verification** (kg)

## 🚀 Quick Start

### Use Online (Recommended)
Simply visit the link above on any device - no installation needed!

### Install as Mobile App

**On Android:**
1. Open the calculator in Chrome
2. Tap menu (⋮) → "Add to Home screen"
3. Tap "Add"
4. App appears on home screen

**On iPhone:**
1. Open the calculator in Safari
2. Tap Share button (□↑)
3. Tap "Add to Home Screen"
4. Tap "Add"

**On Desktop:**
1. Open in Chrome/Edge
2. Click install icon (⊕) in address bar
3. Click "Install"

## 📋 How to Use

1. Enter patient weight in kilograms
2. Click "Calculate Volume"
3. View results:
   - Daily fluid requirement
   - Hourly maintenance rate
   - Rehydration volume

## 🔬 Formula Reference

### Holliday-Segar Method
- **0-10 kg:** 100 mL/kg/day
- **11-20 kg:** 1000 mL + 50 mL/kg for each kg above 10
- **>20 kg:** 1500 mL + 20 mL/kg for each kg above 20

### Rehydration
- **Standard:** 20 mL/kg

## 💻 Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Design:** Custom medical-grade UI
- **Hosting:** GitHub Pages
- **PWA:** Progressive Web App capabilities
- **Offline:** Service Worker caching

## 📦 GitHub Pages Deployment

Your calculator is configured to work with GitHub Pages. To enable it:

1. **Go to your repository settings:**
   - Visit: `https://github.com/bloemsarel/Calculator/settings/pages`

2. **Configure GitHub Pages:**
   - Under "Build and deployment"
   - Set **Source** to: `Deploy from a branch`
   - Set **Branch** to: `main` (or `master`)
   - Set **Folder** to: `/ (root)`
   - Click **Save**

3. **Wait 1-2 minutes** for GitHub to build your site

4. **Your calculator will be live at:**
   `https://bloemsarel.github.io/Calculator/`

### Files Required in Your Repository

Make sure these files are in the root of your repository:
- ✅ `index.html` (main calculator file)
- ✅ `manifest.json` (PWA configuration)
- ✅ `sw.js` (service worker for offline support)
- ✅ `README.md` (this file)

## 🛠️ Local Development

### Clone Repository
```bash
git clone https://github.com/bloemsarel/Calculator.git
cd Calculator
```

### Run Locally
Simply open `index.html` in your browser. No build process needed!

### Customize
Edit the HTML file to modify:
- Colors (search for CSS variables)
- Formula calculations
- UI layout

## 📱 Browser Support

- ✅ Chrome (Android & Desktop)
- ✅ Safari (iOS & macOS)
- ✅ Edge
- ✅ Firefox
- ✅ Samsung Internet
- ✅ Opera

## ⚠️ Medical Disclaimer

This calculator is for educational and reference purposes only. Always verify calculations and use clinical judgment. Fluid requirements may vary based on:

- Patient condition
- Clinical scenario
- Ongoing losses
- Comorbidities
- Local protocols

**Always consult appropriate medical guidelines and supervising physicians.**

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

## 📚 References

- Holliday MA, Segar WE. *The maintenance need for water in parenteral fluid therapy.* Pediatrics. 1957;19(5):823-832.
- NICE Clinical Guidelines - Intravenous fluid therapy in children
- WHO Guidelines on fluid management in children

---

**Made with ❤️ for healthcare professionals**

*Star ⭐ this repository if you find it useful!*
