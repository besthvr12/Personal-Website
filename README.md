# Harsh Verma - Personal Website

A modern, responsive personal portfolio website showcasing professional experience, projects, publications, and achievements.

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **Interactive Elements**:
  - Smooth scrolling navigation
  - Mobile-friendly hamburger menu
  - Scroll-to-top button
  - Animated section reveals
  - Active navigation highlighting
- **Comprehensive Sections**:
  - Hero section with contact links
  - About and Education
  - Technical Skills
  - Work Experience
  - Featured Projects
  - Publications
  - Scholastic Achievements
  - Contact Information

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, animations, and custom properties
- **JavaScript**: Interactive features and smooth scrolling
- **Font Awesome**: Icon library for social media and UI icons

## How to Open the Website

### Option 1: Open Directly in Browser (Recommended)

1. Navigate to the project directory
2. Double-click on `index.html` or right-click and select "Open with" your preferred browser
3. The website will open in your browser

### Option 2: Using Python HTTP Server

```bash
# Navigate to the project directory
cd /home/user/Personal-Website

# Python 3
python3 -m http.server 8000

# Then open your browser and go to:
# http://localhost:8000
```

### Option 3: Using Node.js HTTP Server

```bash
# Install http-server globally (if not already installed)
npm install -g http-server

# Navigate to the project directory
cd /home/user/Personal-Website

# Start the server
http-server -p 8000

# Then open your browser and go to:
# http://localhost:8000
```

### Option 4: Using Live Server (VS Code Extension)

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Project Structure

```
Personal-Website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## Sections Overview

### 1. Hero Section
- Name and professional title
- Brief description
- Call-to-action buttons
- Social media links (Email, LinkedIn, GitHub)

### 2. About Section
- Professional summary
- Education details (IIT Madras & IIIT Naya Raipur)

### 3. Skills Section
- Programming Languages: Python, SQL, C++, CUDA, ROS
- Frameworks: PyTorch, TensorFlow, TensorRT, ONNX, OpenCV, etc.
- Tools: SLURM, Triton, Git, Docker, DVC, MLflow, etc.
- Platforms: AWS, Jupyter, PyCharm, VS Code, etc.

### 4. Experience Section
- Current role: Perception Engineer at Monarch Tractor
- Key achievements and responsibilities
- Technologies used and impact metrics

### 5. Projects Section
- M.Tech Thesis: Porting PyTorch on ShaktiMAAN SOC
- Advanced RAG System
- Blind Signal Detection
- CNN-Based Criminal Detection

### 6. Publications Section
- IEEE ICASSP 2025 paper (Accepted)
- Blind Signal Detection research paper
- CNN-Based Criminal Detection (17 citations)

### 7. Achievements Section
- GATE 2022 AIR 242
- GATE 2021 AIR 1172
- Best Thesis Award

### 8. Contact Section
- Email: harshv034@gmail.com
- Phone: +91 9110960313
- LinkedIn and GitHub profiles

## Customization

### Update Personal Information

Edit the content in `index.html` to update:
- Contact details
- Experience
- Projects
- Publications
- Achievements

### Modify Colors

Edit the CSS custom properties in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    /* ... other color variables */
}
```

### Add New Sections

1. Add the HTML structure in `index.html`
2. Style it in `styles.css`
3. Add any interactive features in `script.js`
4. Update the navigation menu

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Opera

## Performance

- Optimized CSS with minimal redundancy
- Efficient JavaScript with debounced scroll handlers
- Lazy loading support for images
- Smooth animations with CSS transforms
- Mobile-optimized responsive design

## Future Enhancements

- [ ] Dark mode toggle
- [ ] Blog section
- [ ] Project filtering
- [ ] Download CV button
- [ ] Contact form with backend integration
- [ ] Multi-language support
- [ ] Analytics integration

## License

This project is open source and available for personal use.

## Contact

For any questions or feedback, please reach out:

- **Email**: harshv034@gmail.com
- **LinkedIn**: [Harsh Verma](https://www.linkedin.com/in/harsh-verma)
- **GitHub**: [Harsh Verma](https://github.com/harsh-verma)

---

**Built with ❤️ using HTML, CSS, and JavaScript**
