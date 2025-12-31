# Font Style Generator ✨

A stylish, interactive web application that transforms any word into 20 beautifully designed fonts with emoji labels. Each font style can be previewed in a full-screen view by opening it in a new tab.

## Features

✨ **20 Unique Font Styles:**
- 🎨 Bold Italic
- ✨ Cursive
- 🌟 Monospace
- 💎 Shadow
- 🔥 Small Caps
- 🎭 Comic Sans
- 🌈 Rainbow Color
- 🎪 Outlined
- ⭐ Uppercase Heavy
- 💫 Underline Double
- 🌊 Wave
- 🎯 Serif Fancy
- 🚀 Futuristic
- 💖 Pink Glow
- 🌙 Blue Glow
- 🔮 Mystical
- ⚡ Electric
- 🎨 Graffiti
- 🌸 Elegant
- 🎪 Strikethrough

🔍 **Real-Time Search:**
- Type any word (up to 30 characters)
- See instant preview of all 20 fonts
- Smooth animations and transitions

🌐 **New Tab Preview:**
- Click any font style to open a full-screen preview
- View your text in large, stylish format
- Easily navigate back to the generator

🎨 **Beautiful UI:**
- Dark gradient background with gold accents
- Smooth animations and hover effects
- Fully responsive design
- Mobile-friendly interface

## How to Use

1. **Visit the Site:** Open the application in your browser
2. **Explore More:** Click the "Explore More" button to scroll to the Font Style Generator
3. **Type a Word:** Enter any word in the search bar (max 30 characters)
4. **See the Magic:** All 20 font styles appear instantly
5. **Preview Full-Screen:** Click any font style to see it in a new tab
6. **Go Back:** Use the "Go Back" button to return to the generator

## Installation & Running Locally

### Prerequisites
- Node.js (v14 or higher)
- npm (comes with Node.js)

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/my-first-web-page.git
   cd my-first-web-page
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the server:**
   ```bash
   npm start
   ```

4. **Open in browser:**
   - Navigate to `http://localhost:5000`
   - Click "Explore More" to access the Font Style Generator

### Development Mode
For development with auto-reload:
```bash
npm run dev
```

## Project Structure

```
.
├── server.js           # Express server configuration
├── index.html          # Main HTML with embedded styles
├── script.js           # Font generation and UI logic
├── package.json        # Project dependencies
├── README.md           # This file
└── alphabets.json      # Legacy data (optional)
```

## Technologies Used

- **Backend:** Node.js with Express.js
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Font Families:** System fonts + Google Fonts
- **Styling:** CSS3 Gradients, Animations, and Filters

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features Details

### Font Styles Include:

| Style | Effect |
|-------|--------|
| Rainbow Color | Colorful gradient text |
| Electric | Yellow to orange gradient |
| Pink Glow | Glowing pink text shadow |
| Blue Glow | Glowing blue text shadow |
| Mystical | Italic serif with letter spacing |
| Futuristic | Large uppercase with letter spacing |
| Graffiti | Skewed impact font |
| Outlined | Text with stroke effect |

## Customization

### Add More Font Styles
Edit the `fontStyles` array in `script.js`:
```javascript
{ name: '🎨 Your Style', css: 'your-css-properties' }
```

### Change Colors
Modify the CSS variables in `index.html`:
```css
:root {
    --bg-gradient: linear-gradient(...);
    --accent: #ffd54d;
    --muted: rgba(255,255,255,0.95);
}
```

## Performance

- **Fast:** Instant font rendering as you type
- **Lightweight:** No heavy dependencies
- **Responsive:** Works perfectly on all devices
- **Accessible:** Keyboard navigation support

## Author

Created by **Yogesh**

## License

MIT License - Feel free to use this project for personal or commercial purposes.

## Contributing

Found a bug or have a suggestion? Feel free to open an issue or submit a pull request!

## Future Enhancements

- [ ] Add more font styles
- [ ] Download fonts as images
- [ ] Copy CSS to clipboard
- [ ] Font size customization
- [ ] Dark/Light theme toggle
- [ ] Export as HTML file

## Support

If you encounter any issues or have questions, please feel free to reach out!

---

**Enjoy creating stylish fonts!** ✨🎨
