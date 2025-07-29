# 📚 Triple Peaks Library

A modern, responsive library website built as the first project in the TripleTen Software Engineering program. This project showcases mastery of semantic HTML5 and advanced CSS techniques, delivering a fully accessible and visually stunning web experience.

![Triple Peaks Library](https://img.shields.io/badge/Project-Library%20Website-blue?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)

## 🌟 Live Preview

An immersive web experience showcasing the Triple Peaks Library with dynamic sections, smooth animations, and modern design that invites users to explore the library's services and community.

## ✨ Key Features

### 🎨 **Design & UX**
- **Responsive Design**: Optimized for all screen sizes (1100px - 1600px)
- **Smooth Navigation**: Seamless scrolling between sections with anchor links
- **Interactive Elements**: Elegant hover effects and transitions
- **Professional Typography**: Helvetica Neue with clear visual hierarchy

### 🏗️ **Technical Architecture**
- **Semantic HTML5**: Accessible structure with appropriate elements
- **Modern CSS**: Flexbox layouts for complex designs
- **BEM Methodology**: Consistent and maintainable class naming
- **Image Optimization**: Lazy loading and decoding attributes

### 📱 **Interactive Sections**
- **Hero Section**: Striking presentation with main library image
- **Events**: Featured upcoming events with detailed information
- **Staff Picks**: Curated book recommendations from library staff
- **Membership**: Step-by-step process to join the library
- **About**: Library history and community statistics
- **Footer**: Contact information and social media links

## 🚀 Live Demo

[View Live Demo](https://your-username.github.io/triple-peaks-library) *(Update with your URL)*

## 📋 Table of Contents

- [Installation](#-installation)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Features](#-features)
- [Best Practices](#-best-practices)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

## 🛠️ Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code recommended)
- Prettier extension for VS Code (optional)

### Local Setup

```bash
# Clone the repository
git clone https://github.com/your-username/triple-peaks-library.git

# Navigate to directory
cd triple-peaks-library

# Open in your favorite editor
code .

# Open index.html in your browser
# Or use Live Server extension in VS Code
```

### Development Configuration

The project includes VS Code configuration:

```json
// .vscode/settings.json - Automatic formatting
{
  "editor.formatOnSave": true,
  "files.autoSave": "onFocusChange"
}
```

## 📁 Project Structure

```
triple-peaks-library/
├── 📄 index.html              # Main HTML file
├── 📁 styles/
│   └── 📄 style.css          # Main stylesheet
├── 📁 vendor/
│   └── 📄 normalize.css      # CSS normalization
├── 📁 images/                # Visual assets
│   ├── 🖼️ logo.svg
│   ├── 🖼️ inside_the_library.png
│   ├── 🖼️ cafe.png
│   └── 📁 icons/            # Icon assets
├── 📁 .vscode/              # Editor configuration
│   ├── 📄 settings.json
│   └── 📄 extensions.json
├── 📄 .editorconfig          # Universal editor config
├── 📄 .prettierignore       # Prettier exclusions
├── 📄 LICENSE               # MIT License
└── 📄 README.md             # This file
```

## 🔧 Technologies Used

### Core Technologies
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) **Semantic HTML5**
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) **Advanced CSS3**
- ![Normalize](https://img.shields.io/badge/Normalize.css-v8.0.1-red?style=flat) **Normalize.css v8.0.1**

### Methodologies & Patterns
- **BEM (Block Element Modifier)**: For scalable CSS architecture
- **Mobile-First**: Progressive responsive design approach
- **Semantic HTML**: Optimized for accessibility and SEO
- **CSS Grid & Flexbox**: Modern, flexible layout systems

### Development Tools
- **Prettier**: Automatic code formatting
- **EditorConfig**: Consistent configuration across editors
- **VS Code**: Recommended editor with extensions

## 🎯 Features

### 🎨 User Interface
- [x] Smooth navigation between sections
- [x] Interactive hover effects on elements
- [x] Responsive design for multiple devices
- [x] Hierarchical and readable typography
- [x] Professional color scheme

### 🏗️ Architecture
- [x] Semantic HTML for accessibility
- [x] Modular CSS with BEM methodology
- [x] Optimized images with lazy loading
- [x] Organized file structure

### 📱 Responsive Design
- [x] Optimized breakpoints
- [x] Adaptive images
- [x] Mobile-friendly navigation
- [x] Scalable content

## 🏆 Best Practices Implemented

### Accessibility
```html
<!-- Descriptive alt texts -->
<img src="./images/logo.svg" alt="Triple Peaks Library Logo" />

<!-- Semantic navigation -->
<nav class="nav">
  <ul class="nav__links">
    <li><a href="#events">Events</a></li>
  </ul>
</nav>
```

### Performance
```css
/* Lazy loading for images */
img {
  loading: lazy;
  decoding: async;
}

/* Smooth transitions */
.nav__link {
  transition: color 0.2s ease-in-out;
}
```

### SEO
```html
<!-- Optimized meta tags -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Triple Peaks Library</title>
```

## 🎨 Style Guide

### Primary Colors
```css
:root {
  --primary-blue: #2f80ed;
  --hover-blue: #1f69c9;
  --text-dark: #1f1f1f;
  --text-gray: #838383;
  --background-light: #f2f2f2;
  --white: #ffffff;
}
```

### Typography
```css
.page {
  font-family: "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  line-height: 20px;
}
```

## 📈 Roadmap & Future Enhancements

- [ ] **Version 2.0**: Implement JavaScript for enhanced interactivity
- [ ] **Enhanced Responsive**: Tablet and mobile optimizations
- [ ] **Dark Mode**: Theme switcher for dark/light modes
- [ ] **Animations**: CSS micro-interactions and animations
- [ ] **PWA**: Convert to Progressive Web App
- [ ] **Backend Integration**: Connect to library management system

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Contribution Process

1. **Fork** the project
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Code of Conduct

This project follows the [Contributor Covenant](https://www.contributor-covenant.org/). Please maintain a respectful and constructive environment.

### Reporting Issues

- Use the [issue templates](https://github.com/your-username/triple-peaks-library/issues/new/choose)
- Include screenshots if relevant
- Describe steps to reproduce the problem

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

```
MIT License - Copyright (c) 2025 Marcos Freixanet
```

## 👨‍💻 Contact

**Marcos Freixanet** - Frontend Developer

- 🌐 Portfolio: [your-portfolio.com](https://your-portfolio.com)
- 💼 LinkedIn: [linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)
- 📧 Email: your-email@example.com
- 🐙 GitHub: [@your-username](https://github.com/your-username)

---

## 🙏 Acknowledgments

- **TripleTen**: For the educational guidance and resources
- **Normalize.css**: For the excellent CSS reset
- **Unsplash**: For high-quality imagery
- **Developer Community**: For constant inspiration and support

---

<div align="center">

**Thank you for visiting Triple Peaks Library!** 📚✨

[⬆ Back to top](#-triple-peaks-library)

*Made with ❤️ and lots of ☕ by [Marcos Freixanet](https://github.com/your-username)*

</div>
