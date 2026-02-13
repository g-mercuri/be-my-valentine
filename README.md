# 💖 Be My Valentine

A beautiful, interactive Valentine's Day webpage with a playful twist - the "No" button keeps running away! Perfect for Valentine's Day proposals, romantic gestures, or making someone special smile.

![Valentine's Day](https://img.shields.io/badge/Valentine's%20Day-2026-ff69b4?style=for-the-badge)
![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red?style=for-the-badge)

## ✨ Features

- 🎨 **Beautiful Design** - Elegant animated gradient background with floating container
- 💕 **Multi-language Support** - Say "I love you" in 15 different languages
- ☑️ **Smart Defaults** - English pre-selected, with optional language customization
- 🎯 **Interactive "No" Button** - The "No" button playfully runs away when you try to click it
- 💝 **Personalization** - Customizable with names and pre-selected languages
- 🎊 **Celebration Effects** - Confetti hearts rain down when "Yes" is clicked
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- ⚡ **Zero Dependencies** - Pure HTML, CSS, and JavaScript - no frameworks needed
- 🎁 **Easy Customization** - Simple configuration to personalize for your special someone

## 🚀 Quick Start

### Option 1: Just Open It
1. Download or clone this repository
2. Open `index.html` in your web browser
3. That's it! Share the love 💕

### Option 2: Deploy to GitHub Pages (Recommended)

Deploy your personalized version for free on GitHub Pages:

1. **Fork or Create Repository**
   - Fork this repository OR create a new repository on GitHub
   - Upload `index.html` to your repository

2. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to **Pages** (under "Code and automation")
   - Under **Source**, select `main` branch
   - Click **Save**

3. **Access Your Page**
   - Your page will be available at: `https://yourusername.github.io/repository-name/`
   - Usually takes 1-2 minutes to go live

4. **Share the Love**
   - Copy the URL and send it to your special someone! 💌

## 🎨 Customization Guide

### Skip the Input Form OR Pre-select Languages

Want to personalize it for someone specific? Edit the `CONFIG` section at the top of the JavaScript in `index.html`:

**Option 1: Skip the form entirely (most romantic!)**
```javascript
const CONFIG = {
    // The name of your special someone
    defaultName: "Sarah",
    
    // Languages for "I love you" messages (comma-separated)
    defaultLanguages: "English, Italian, Spanish",
    
    // Skip the form and go straight to the question
    skipFormIfConfigured: true
};
```

**Option 2: Pre-select languages (keep the name field)**
```javascript
const CONFIG = {
    // Leave name empty to show the form
    defaultName: "",
    
    // Pre-select these languages in the checkboxes
    defaultLanguages: "Italian, Polish, French",
    
    // Show the form but with languages pre-selected
    skipFormIfConfigured: true
};
```

**Example Configuration:**
```javascript
const CONFIG = {
    defaultName: "Maria",
    defaultLanguages: "Italian, Polish, French",
    skipFormIfConfigured: true
};
```

This will skip the input form and immediately show the Valentine's question with their name!

### Available Languages

Choose from 15 languages:
- English
- Spanish
- Italian
- French
- German
- Portuguese
- Polish
- Russian
- Japanese
- Korean
- Chinese
- Arabic
- Dutch
- Greek
- Turkish

### Customize Colors

Want to change the color scheme? Look for these CSS sections in `index.html`:

**Background Gradient:**
```css
background: linear-gradient(135deg, #ee9ca7 0%, #ffdde1 50%, #ee9ca7 100%);
```

**Button Colors:**
```css
.yes-btn {
    background: linear-gradient(135deg, #ff4757 0%, #ff6b81 100%);
}
```

## 📱 How It Works

1. **Enter Your Name** - Type in your name
2. **Language Selection** - English is pre-selected, or click "Change languages" to choose from 15 languages with country flags
3. **The Question** - "Will you be my Valentine?" with Yes/No buttons
4. **Playful Interaction** - The "No" button escapes when you try to hover over it
5. **Sweet Celebration** - Click "Yes" to see love messages in chosen languages with heart confetti

## 🌟 Perfect For

- 💝 Valentine's Day proposals
- 💑 Romantic gestures
- 🎁 Fun interactive greetings
- ❤️ Showing someone special how much you care
- 🎉 Creative date invitations

## 🛠️ Technical Details

**Built with:**
- Pure HTML5
- CSS3 (Animations, Gradients, Flexbox)
- Vanilla JavaScript (ES6+)
- Google Fonts (Pacifico & Poppins)

**No build process required** - Just open and use!

## 📦 File Structure

```
be-my-valentine/
│
├── index.html          # Main application file (everything in one file!)
└── README.md          # This file
```

## 🎯 Browser Support

Works on all modern browsers:
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 💡 Tips & Tricks

1. **For GitHub Pages:** Use a custom domain for extra romance!
2. **Mobile Sharing:** Works perfectly when shared via text/messaging apps
3. **Screenshots:** The "No" button moves on hover, creating fun reactions
4. **Personalization:** Configure it for maximum impact - add their favorite languages!

## 🤝 Contributing

Feel free to fork this project and make it your own! Some ideas:
- Add more languages
- Create different themes (Christmas, Birthday, etc.)
- Add sound effects
- Create different button behaviors

## 📝 License

This project is free to use for personal purposes. Spread the love! ❤️

## 🎉 Credits

Made with ❤️ for Valentine's Day 2026

---

### ⭐ If you use this project, give it a star!

**Happy Valentine's Day! 💕**
