
# Tejas Sevak - Portfolio Website

A personal portfolio website showcasing projects, skills, and professional links. Built with HTML, CSS, JavaScript, and styled with Tailwind CSS.

## 🌐 Live Demo

Visit the live portfolio at: [teejaz.github.io](https://teejaz.github.io)

## 📁 Project Structure

```
├── index.html              # Main portfolio page
├── src/
│   ├── mystyle.css         # Custom CSS styles
│   └── style_movement.css  # Animation styles
├── images/                 # Image assets
│   ├── ART/               # 3D artwork images
│   └── ...                # Profile and project images
├── dist/                  # Compiled CSS output
├── package.json           # Dependencies and build scripts
└── tailwind.config.js     # Tailwind CSS configuration
```

## 🚀 Features

- **Responsive Design**: Mobile-friendly layout using Bootstrap and Tailwind CSS
- **Tab Navigation**: Multi-section portfolio with smooth tab switching
- **Project Showcase**: Interactive project cards with hover effects
- **3D Art Gallery**: Dedicated section for 3D modeling work
- **Professional Links**: Quick access to LinkedIn, GitHub, and resume

## 📋 Sections

1. **Home**: Introduction with social links and personal photos
2. **Projects**: Showcase of development projects including:
   - AI/TensorFlow image painting
   - Smart parking system
   - Java blog platform
   - Planetary system simulation
3. **3D Projects**: Gallery of 3D artwork and simulations
4. **Links**: Additional resources and connections

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Tailwind CSS, Bootstrap 4.4.1
- **Icons**: Ionicons, Material Icons
- **Build Tools**: Node.js, PostCSS
- **Deployment**: GitHub Pages

## 🔧 Setup & Development

### Prerequisites
- Node.js (v20 or higher)
- npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/teejaz/teejaz.github.io.git
cd teejaz.github.io
```

2. Install dependencies:
```bash
npm install
```

3. Build CSS files:
```bash
npm run build
```

4. Start development server:
```bash
python -m http.server 5000
```

5. Open your browser and navigate to `http://localhost:5000`

### Build Process

The project uses Tailwind CSS for styling. To compile CSS:

```bash
# Build and minify CSS
npm run build

# This compiles:
# src/mystyle.css → dist/styles.css
# src/style_movement.css → dist/style_movement.css
```

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- Desktop computers
- Tablets
- Mobile devices

## 🎨 Customization

### Adding New Projects

1. Add project images to the `images/` directory
2. Update the Projects tab in `index.html` with new project cards
3. Follow the existing structure for consistency

### Styling Changes

- Modify `src/mystyle.css` for custom styles
- Use Tailwind utility classes in HTML
- Run `npm run build` after making changes

## 📞 Contact

- **LinkedIn**: [Tejas Sevak](https://www.linkedin.com/in/tejas-sevak99/)
- **GitHub**: [teejaz](https://github.com/teejaz)

## 📄 License

This project is open source and available under the [ISC License](LICENSE).

---

Built with ❤️ by Tejas Sevak
