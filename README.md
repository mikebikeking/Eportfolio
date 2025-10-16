<div id="top"></div>

<!-- HEADER STYLE: CLASSIC -->
<div align="center">

# EPORTFOLIO

<em>Showcase Your Vision, Inspire Future Opportunities</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/mikebikeking/Eportfolio?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/mikebikeking/Eportfolio?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/mikebikeking/Eportfolio?style=flat&color=0080ff" alt="repo-language-count">


<br>

<em>Built with the tools and technologies:</em>

<br>

<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=flat&logo=HTML5&logoColor=white" alt="HTML5">
<img src="https://img.shields.io/badge/CSS3-1572B6.svg?style=flat&logo=CSS3&logoColor=white" alt="CSS3">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&logo=JavaScript&logoColor=black" alt="JavaScript">

</div>

<br>

---

## 📑 Table of Contents

- [📋 Overview](#-overview)
- [✨ Features](#-features)
- [📁 Project Structure](#-project-structure)
- [🚀 Getting Started](#-getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
- [🎨 Customization](#-customization)
- [📧 Contact Form Setup](#-contact-form-setup)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 📋 Overview

**ePortfolio** is a developer-friendly template for creating engaging and interactive portfolio websites. It combines dynamic visual effects, seamless user interactions, and integrated contact features to help you showcase your work effectively.

### Why ePortfolio?

This project aims to streamline the development of a professional online portfolio with rich interactivity. Whether you're a developer, designer, or creative professional, this template provides a solid foundation for presenting your work in a modern, accessible format.

---

## ✨ Features

### Core Functionality

- 🎨 **Visual Effects & Dynamic Backgrounds** 
  - Animated particle backgrounds
  - Smooth UI transitions and hover effects
  - Responsive animations that adapt to screen size

- 🔧 **Theme Contrast Toggle** 
  - Seamless light/dark mode switching
  - User preference persistence
  - Accessible contrast ratios

- 📩 **Contact Form Integration** 
  - Email service integration
  - Form validation
  - Spam protection

- 🧩 **Modular Layout & Styling** 
  - Component-based architecture
  - Easy-to-customize CSS variables
  - Mobile-first responsive design

- 🎯 **Interactive Modals & Content Presentation** 
  - Project showcase modals
  - Image galleries
  - Smooth scroll navigation

---

## 📁 Project Structure

```
Eportfolio/
├── index.html              # Main HTML file
├── css/
│   ├── styles.css         # Main stylesheet
│   ├── animations.css     # Animation definitions
│   └── responsive.css     # Responsive design rules
├── js/
│   ├── main.js           # Core JavaScript functionality
│   ├── particles.js      # Particle background effects
│   ├── theme.js          # Theme switcher logic
│   └── contact.js        # Contact form handling
├── assets/
│   ├── images/           # Image assets
│   ├── fonts/            # Custom fonts
│   └── icons/            # Icon files
├── projects/             # Project showcase content
└── docs/                 # Documentation
```

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Git** (for cloning the repository)
- **A modern web browser** (Chrome, Firefox, Safari, or Edge)
- **A text editor or IDE** (VS Code, Sublime Text, etc.)
- **A local web server** (optional, but recommended for development)
  - You can use Python's built-in server: `python -m http.server`
  - Or Node.js with http-server: `npm install -g http-server`

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mikebikeking/Eportfolio.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Eportfolio
   ```

3. **Open the project:**
   - For development with a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Or using Node.js http-server
     http-server
     ```
   - Then navigate to `http://localhost:8000` in your browser

   - For quick viewing:
     ```bash
     # Simply open the index.html file in your browser
     open index.html  # macOS
     start index.html # Windows
     xdg-open index.html # Linux
     ```

### Usage

1. **Customize your content:**
   - Edit `index.html` to add your personal information
   - Update project details in the `projects/` directory
   - Modify styles in `css/styles.css` to match your brand

2. **Add your projects:**
   - Create new project cards in the portfolio section
   - Add project images to `assets/images/`
   - Update project descriptions and links

3. **Deploy your portfolio:**
   - Push to GitHub Pages
   - Deploy to Netlify or Vercel
   - Host on your own domain

---

## 🎨 Customization

### Theme Colors

Edit the CSS variables in `css/styles.css`:

```css
:root {
  --primary-color: #0080ff;
  --secondary-color: #ff6b35;
  --background-light: #ffffff;
  --background-dark: #1a1a1a;
  --text-light: #333333;
  --text-dark: #f0f0f0;
}
```

### Typography

Customize fonts in `css/styles.css`:

```css
body {
  font-family: 'Your Font', sans-serif;
  font-size: 16px;
  line-height: 1.6;
}
```

### Layout Options

The portfolio supports multiple layout configurations:
- Grid layout for project cards
- Masonry layout for varied content sizes
- List view for detailed descriptions

---

## 📧 Contact Form Setup

To enable the contact form functionality:

1. **Using EmailJS (Recommended):**
   - Sign up at [EmailJS](https://www.emailjs.com/)
   - Create an email service and template
   - Add your credentials to `js/contact.js`:
     ```javascript
     emailjs.init("YOUR_USER_ID");
     ```

2. **Using Formspree:**
   - Sign up at [Formspree](https://formspree.io/)
   - Update the form action in `index.html`:
     ```html
     <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
     ```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines

- Follow the existing code style
- Comment your code when necessary
- Update documentation for new features
- Test across different browsers

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Inspired by modern web design trends and best practices
- Built with accessibility and performance in mind

---

## 📬 Contact

**GitHub:** [@mikebikeking](https://github.com/mikebikeking)

**Project Link:** [https://github.com/mikebikeking/Eportfolio](https://github.com/mikebikeking/Eportfolio)

---

<div align="center">
  <strong>⭐ If you find this project helpful, please consider giving it a star!</strong>
</div>

<div align="right">
  <a href="#top">⬆ Back to Top</a>
</div>
