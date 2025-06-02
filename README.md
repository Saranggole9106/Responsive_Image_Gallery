# Responsive Image Gallery

A modern, responsive image gallery built with HTML, CSS, and JavaScript. This gallery features a clean design, smooth animations, and a user-friendly interface for showcasing your images across different categories.

## 🌟 Features

- **Responsive Design**: Adapts seamlessly to all screen sizes and devices
- **Category Filtering**: Filter images by categories (Nature, Architecture, Travel)
- **Lightbox View**: Full-screen image viewing with smooth transitions
- **Modern UI**: Clean and intuitive user interface with smooth animations
- **Keyboard Navigation**: Support for keyboard shortcuts (Escape to close)
- **Mobile-Friendly**: Optimized for touch devices and mobile viewing

![image](https://github.com/user-attachments/assets/de2e3559-d74e-4c33-bcfc-0e323867042a)

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables for theming)
- Vanilla JavaScript
- Responsive Design Principles
- CSS Grid and Flexbox for layouts

## 📱 Features in Detail

### Category Filtering
- Interactive category buttons (Nature, Architecture, Travel)
- Smooth transitions between categories
- Visual feedback for active category

### Lightbox
- Full-screen image viewing
- Click outside to close
- Keyboard support (Escape key)
- Smooth animations

### Responsive Design
- Adapts to all screen sizes
- Optimized grid layout
- Mobile-first approach
- Touch-friendly interactions

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/Saranggole9106/Responsive_Image-Gallery.git
```

2. Open `index.html` in your browser to view the gallery.

## 🎨 Customization

### Adding New Images
1. Add your image to the `images` directory
2. Add a new gallery item in `index.html` following the existing structure:
```html
<div class="gallery-item" data-category="your-category">
    <img src="images/your-image.jpg" alt="Description">
    <div class="gallery-item-info">
        <h3>Title</h3>
        <p>Description</p>
    </div>
</div>
```

### Modifying Colors
The color scheme can be easily modified by updating the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    --accent-color: #your-color;
}
```

## 📝 Project Structure

```
responsive-image-gallery/
├── index.html
├── styles.css
├── script.js
└── images/
    ├── nature/
    ├── architecture/
    └── travel/
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## 👏 Acknowledgments

- Images used in the demo are for demonstration purposes
- Inspired by modern web design trends
- Built with accessibility in mind

## 📧 Contact

For any questions or suggestions, please open an issue in the repository.

---

Made with ❤️ by [Sarang Gole]
