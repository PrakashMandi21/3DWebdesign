# 🚀 3D Website Landing Page

A stunning, modern landing page featuring 3D elements, smooth animations, and a futuristic design. Built with pure HTML, CSS, and JavaScript, enhanced with Spline 3D graphics and AOS animations.

![Project Thumbnail](thumbnail.png)

## ✨ Features

- **🎨 Modern Design**: Sleek black theme with gradient accents and glassmorphism effects
- **🤖 3D Robot Animation**: Interactive 3D robot model powered by Spline
- **⚡ Smooth Animations**: Scroll-triggered animations using AOS (Animate On Scroll)
- **📱 Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **🎯 Interactive Elements**: Hover effects and smooth transitions throughout
- **🌈 Gradient Effects**: Dynamic gradient backgrounds and glowing elements

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with flexbox, animations, and responsive design
- **JavaScript**: Animation initialization and interactivity
- **Spline 3D**: For the interactive 3D robot model
- **AOS Library**: Scroll-triggered animations
- **Google Fonts**: Custom typography (Limelight, Fleur De Leah)

## 🎭 Visual Elements

### Color Scheme
- **Primary**: Black (#000000)
- **Secondary**: Light Gray (#a7a7a7, #656565)
- **Accent**: Purple (#7f42a7, #6600c5, #5300a0)
- **Text**: White (#ffffff) with gray variations

### Typography
- **Logo**: Limelight (sans-serif)
- **Body**: System fonts for optimal performance
- **Headings**: Bold, large-scale typography with text shadows

### 3D Elements
- Interactive robot model positioned dynamically
- Responsive scaling based on viewport size
- Positioned strategically to enhance visual hierarchy

## 📱 Responsive Design

The layout adapts seamlessly across devices:

- **Desktop (1300px+)**: Full layout with robot positioned right
- **Tablet (768px-1300px)**: Adjusted spacing and scaled robot
- **Mobile (<768px)**: Simplified navigation, stacked content, smaller robot

## 🚀 Getting Started

### Prerequisites
- Modern web browser with JavaScript enabled
- Internet connection for external resources (fonts, 3D model)

### Installation

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd 3D-startup-app
   ```

2. **Open in browser**
   - Simply open `index.html` in your browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     ```

3. **View the site**
   - Navigate to `http://localhost:8000` (if using local server)

## 🎨 Customization

### Changing Colors
Edit the CSS variables in `style.css`:
```css
/* Update gradient colors */
background: linear-gradient(to right, #656565, #7f42a7, #6600c5);

/* Update hover effects */
nav a:hover { color: #your-color; }
```

### Updating 3D Model
Replace the Spline URL in `index.html`:
```html
<spline-viewer url="https://prod.spline.design/your-model-url/scene.splinecode"></spline-viewer>
```

### Modifying Animations
Adjust AOS attributes in HTML:
```html
<div data-aos="fade-down" data-aos-duration="1500">Your content</div>
```

## 📁 Project Structure

```
3D-startup-app/
├── index.html          # Main HTML file
├── style.css           # All styling and animations
├── README.md          # This file
├── gradient.png       # Background gradient image
├── thumbnail.png      # Project thumbnail
└── youtube.png        # YouTube branding asset
```

## 🎯 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🚀 Performance Optimizations

- **Optimized Images**: Compressed PNG assets
- **Efficient CSS**: Minimal, organized stylesheets
- **CDN Resources**: External libraries loaded from CDN
- **Lazy Loading**: 3D model loads after page content

## 🎮 Interactive Features

- **Hover Effects**: Navigation links and buttons
- **Scroll Anim**: Content reveals on scroll
- **3D Interaction**: Click and drag the robot model
- **Responsive Navigation**: Adapts to screen size

## 📸 Screenshots

![Landing Page Screenshot](thumbnail.png)

## 🙋‍♂️ Support

If you found this project helpful, please consider:
- ⭐ Starring the repository
- 🐛 Reporting issues
- 📣 Sharing with others

---

**Built with ❤️ for the modern web**
