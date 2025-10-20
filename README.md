# 🌐 CSS Image Grid

A **simple and responsive image grid** built with **HTML** and **CSS**.  
This project demonstrates how to create a clean, flexible image gallery using modern layout techniques like **CSS Grid**.  

Perfect for beginners, open-source enthusiasts, and Hacktoberfest contributors 🎉.  

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success)
![Hacktoberfest](https://img.shields.io/badge/Hacktoberfest-2025-orange)

### NOTE: Make sure to add your profile details to contributors.json in [Quiver 2025](https://github.com/noodles-sed/hacktober-base)

---

## ✨ Features
- 📱 **Responsive design** – adjusts to any screen size  
- 🖼️ **Beautiful image grid** with smooth hover effects  
- 🌙 **Dark/Light mode toggle** with localStorage persistence
- ⚡ **Lightweight & fast** – no external libraries  
- ♿ **Accessible** – keyboard navigation and ARIA labels
- 🎨 **Easy to customize** for your own projects
- 🔄 **Lazy loading** for better performance
- ✨ **Smooth animations** and transitions

---

## 🚀 Getting Started

### Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/vatsalgupta2004/CSS-Image-Grid.git

2. Navigate to the project directory:
   ```bash
   cd CSS-Image-Grid
   ```

3. Open cssimggrid.html in your browser:
   - Double-click the file, or
   - Right-click  Open with  Your browser
   - Or use a local server (recommended)

### Using a Local Server (Recommended)

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit http://localhost:8000 in your browser.

---

##  Customization

### Changing Images
Replace the image URLs in the HTML:
```html
<img src="your-image-url.jpg" alt="Description" loading="lazy">
```

### Adjusting Grid Layout
Modify the CSS grid properties:
```css
.grid-container {
  grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
  gap: 18px;
}
```

### Changing Colors
Update the gradient and theme colors:
```css
body {
  background: linear-gradient(135deg, #yourcolor1, #yourcolor2);
}
```

---

##  Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Grid layout, animations, transitions
- **JavaScript** - Theme toggle and localStorage
- **CSS Grid** - Responsive layout system

---

##  Accessibility Features

-  Keyboard navigation support (Tab, Enter, Space)
-  ARIA labels for screen readers
-  Focus indicators for interactive elements
-  Descriptive alt text for images
-  High contrast ratios
-  Semantic HTML structure

---

##  Browser Support

| Browser | Version |
|---------|---------|
| Chrome  |  Latest |
| Firefox |  Latest |
| Safari  |  Latest |
| Edge    |  Latest |
| Opera   |  Latest |

---

##  Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### Quick Contribution Steps:
1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

---

##  License

This project is open source and available for educational purposes.

---

##  Show Your Support

If you find this project helpful, please give it a  on GitHub!

---

##  Contact

Have questions or suggestions? Feel free to open an issue!

---

##  Future Enhancements

- [ ] Add lightbox/modal view for images
- [ ] Implement image filtering by category
- [ ] Add search functionality
- [ ] Include more animation options
- [ ] Add image upload feature
- [ ] Create theme customizer

---

**Made with  for Hacktoberfest 2025**

*Last Updated: October 2025*
