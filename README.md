# FloatChat - Ocean Data Visualization Chat Interface

A sophisticated React application built with Next.js that provides an AI-powered chat interface for ocean data visualization. Features three distinct modes: Standard Query, Visual Discovery, and Deep Search.

## Features

- **Standard Query Mode**: Text-based answers and summaries
- **Visual Discovery Mode**: Interactive graphs and charts using Recharts
- **Deep Search Mode**: Interactive maps for geospatial data
- **Responsive Design**: Mobile-first design with Tailwind CSS
- **Interactive Visualizations**: Dynamic charts and SVG-based maps
- **Modern UI**: Clean, professional interface with smooth animations

## Technologies Used

- **Next.js 14** - React framework
- **React 18** - UI library
- **Recharts** - Chart visualization library
- **Lucide React** - Icon library
- **Tailwind CSS** - Utility-first CSS framework
- **Vercel** - Deployment platform

## Development

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Start production server
npm start
```

## Deployment

### Deploy to Vercel

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Connect your repository to Vercel
3. Vercel will automatically detect it's a Next.js project and deploy it

### Manual Deployment

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

## Project Structure

```
/
├── pages/
│   ├── _app.js          # Next.js app wrapper
│   └── index.js         # Main application page
├── styles/
│   └── globals.css      # Global styles and Tailwind imports
├── package.json         # Dependencies and scripts
├── next.config.js       # Next.js configuration
├── tailwind.config.js   # Tailwind CSS configuration
└── postcss.config.js    # PostCSS configuration
```

## Live Demo

Visit the deployed application: [Your Vercel URL will appear here after deployment]