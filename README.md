cat > README.md <<'EOF'
# React Project 02

A multi-page React website for an AI/IoT/STEM education brand.  
Includes pages for AI Launchpad kits, coding & robotics, hands-on AI, IoT projects, e-books/e-stories, gallery, blog, contact, and policy/legal sections.

## Features
- Multi-page frontend for products and learning content
- Blog, gallery, and resource pages
- Policy pages (Privacy, Terms, Disclaimer, Cookie Policy)
- Responsive layout
- Tailwind CSS styling (if configured)
- FontAwesome icons

## Tech Stack
- React (Create React App)
- Tailwind CSS
- FontAwesome

## Getting Started

### Requirements
- Node.js (recommended 18+)
- npm

### Install
npm install

### Run locally
npm start

### Build
npm run build

## Project Structure
src/
  components/
  pages/
public/

## Deployment
Deployable on Vercel, Netlify, or other static hosting.

## Notes
If you face icon-related errors:
npm install @fortawesome/fontawesome-svg-core @fortawesome/react-fontawesome @fortawesome/free-brands-svg-icons @fortawesome/free-solid-svg-icons @fortawesome/free-regular-svg-icons

## Author
Mohsin Khan

## License
For learning/demo purposes.
EOF

git add README.md
git commit -m "add readme"
git push
