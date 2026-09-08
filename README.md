# RIVR Dashboard - Hero Section

A sleek, glassmorphism-styled Hero section for the RIVR DeFi dashboard, ready for Vercel deployment.

## Files

This project contains only 4 files for simplicity and easy deployment:

- `index.html` - Main HTML file with CDN dependencies
- `main.js` - All React components (transpiled with Babel)
- `styles.css` - Custom styles with Tailwind CSS and custom font
- `README.md` - This file

## Deployment to Vercel

### Option 1: Drag and Drop (Simplest)

1. Go to [vercel.com](https://vercel.com) and sign in
2. Click "Add New Project" 
3. Choose "Upload a file or folder"
4. Drag and drop the `rivr-dashboard` folder
5. Click "Deploy"

### Option 2: Git Integration

1. Initialize a git repository in the folder:
   ```bash
   cd rivr-dashboard
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. Push to GitHub/GitLab/Bitbucket

3. Import the repository in Vercel

## Local Testing

Simply open `index.html` in your browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then visit `http://localhost:8000`

## Technologies Used

- **React 18** - UI library (via CDN)
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Framer Motion** - Animation library (via CDN)
- **Lucide Icons** - Icon library (via CDN)
- **Babel** - JSX transformation (via CDN)

## Features

- **Glassmorphism Design**: Premium UI with backdrop blur and transparency effects
- **Custom Typography**: Helvetica Regular font imported from CDN
- **Responsive Layout**: Fully responsive design for mobile, tablet, and desktop
- **Smooth Animations**: Powered by Framer Motion for polished interactions
- **Video Background**: Auto-playing looped video for dynamic visual appeal
- **Interactive Elements**: Hover effects and scale animations on buttons
- **Complex Layout**: Faux-cutout corner design with SVG masks

## Customization

### Colors
- Background: `#f0f0f0`
- Primary text: `#5E6470`
- Accent: `rgba(30,50,90,0.8)` to `rgba(30,50,90,1)`

### Font
The custom "Helvetica Regular" font is loaded from Online Web Fonts CDN. To change fonts, update the `@font-face` declaration in `styles.css`.

### Video Background
To change the background video, update the `src` attribute in the `<video>` element in `main.js`.

## License

This project is private and proprietary.
