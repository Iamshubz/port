# Shubham Kayande - Portfolio

A modern, fully responsive portfolio website built with React, Three.js, and Tailwind CSS.
## Features

✨ **3D Background Animation** - Interactive Three.js background with mouse tracking
📱 **Fully Responsive** - Works perfectly on mobile, tablet, and desktop
🎨 **Beautiful UI** - Modern glassmorphism design with smooth animations
⚡ **Performance Optimized** - Fast loading and smooth interactions
🔧 **Easy to Customize** - Clean, well-structured code
  
## Tech Stack

- **React 18** - UI Framework
- **Vite** - Build tool and dev server
- **Three.js** - 3D graphics library
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide Icons** - Beautiful SVG icons

## Project Structure

```
├── src/
│   ├── App.jsx           # Main application component
│   ├── main.jsx          # Entry point
│   └── index.css         # Global styles
├── public/               # Static assets
├── index.html            # HTML template
├── package.json          # Dependencies
├── vite.config.js        # Vite configuration
├── tailwind.config.js    # Tailwind configuration
└── postcss.config.js     # PostCSS configuration
```

## Installation

1. Navigate to the project directory:
```bash
cd /Users/shubhamkayande/Documents/GitHub/Portfoilio
```

2. Install dependencies:
```bash
npm install
```

## Development

Run the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:5173`

## Build

Build for production:
```bash
npm run build
```

## Preview Production Build

```bash
npm run preview
```

## Responsive Design

The portfolio is fully responsive with:
- Mobile-first approach
- Breakpoints: sm (640px), md (768px), lg (1024px)
- Touch-friendly navigation
- Optimized for all screen sizes

## Customization

### Colors
Edit `tailwind.config.js` to customize the color scheme.

### Content
Update the `projects`, `experience`, and `skills` arrays in `src/App.jsx` to modify portfolio content.

### Contact
Update the email in the footer section and social links.

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized Three.js rendering
- CSS animations instead of JavaScript where possible
- Smooth scrolling and transitions
- Responsive images and icons

## License

© 2025 Shubham Kayande. All rights reserved.
