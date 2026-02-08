# Portfolio Website

A professional portfolio website showcasing my work, experience, and side projects as a Senior Software Developer.

## Features

- **Responsive Design** - Mobile-friendly layout using Tailwind CSS
- **Modern UI/UX** - Clean and professional interface
- **Social Media Integration** - Links to X, LinkedIn, and GitHub
- **Projects Showcase** - Display of side projects
- **About Section** - Professional bio and expertise

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3/Tailwind CSS** - Styling and responsive design
- **Vanilla JavaScript** - Minimal interactivity

## Getting Started

### Prerequisites

- Node.js 14+ (for Tailwind CSS development)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/michaelkrasuski/portfolio.git
cd portfolio
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

The Tailwind CSS compiler will watch for changes and rebuild the CSS file.

### Build for Production

```bash
npm run build
```

This generates the optimized CSS file in the `dist/` directory.

## Project Structure

```
portfolio/
├── index.html           # Main HTML file
├── dist/
│   └── output.css      # Compiled Tailwind CSS
├── src/
│   └── input.css       # Tailwind CSS input
├── package.json        # Dependencies and scripts
├── tailwind.config.js  # Tailwind configuration
└── README.md           # This file
```

## Data Management

The portfolio uses **static HTML content**. All data (bio, projects, social links) is embedded directly in the HTML file. This approach:

- ✅ No backend required
- ✅ Fast loading times
- ✅ Easy deployment (serve as static files)
- ✅ Perfect for GitHub Pages hosting

For future scalability, consider migrating to a JSON data file and using JavaScript to render content dynamically.

## Deployment

### GitHub Pages

1. Push code to GitHub repository
2. Go to repository Settings → Pages
3. Select "Deploy from a branch"
4. Choose `main` branch and `/root` folder
5. Your site will be live at `https://michaelkrasuski.github.io/portfolio`

### Alternative Hosting

- Netlify (offers CLI deployment)
- Vercel (supports static files)
- Any static hosting service

## License

MIT License - feel free to use this as a template for your own portfolio.

## Author

Michael Krasuski - Senior Software Developer
