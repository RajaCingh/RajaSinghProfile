# Raja Singh - Portfolio Website

A modern, responsive portfolio website built with React showcasing my skills as a .NET Developer.

## 🚀 Features

- **Modern Design**: Clean, professional design with smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Interactive**: Smooth scrolling navigation and hover effects
- **Performance**: Optimized for fast loading and smooth user experience
- **Accessible**: Built with accessibility best practices

## 🛠️ Technologies Used

- **React 18** - Modern React with hooks
- **Framer Motion** - Smooth animations and transitions
- **React Icons** - Beautiful icon library
- **CSS3** - Modern CSS with custom properties and animations
- **HTML5** - Semantic markup

## 📋 Prerequisites

Before running this project, make sure you have:

- Node.js (version 14 or higher)
- npm or yarn package manager

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd raja-singh-portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Add your profile image**
   - Save your profile image as `profile-image.jpg`
   - Place it in the `public` folder
   - The image will automatically appear on the homepage

4. **Start the development server**
   ```bash
   npm start
   ```

5. **Open your browser**
   - Navigate to `http://localhost:3000`
   - The website will automatically reload when you make changes

## 📁 Project Structure

```
src/
├── components/          # React components
│   ├── Header.js       # Navigation header
│   ├── Hero.js         # Hero section with profile
│   ├── About.js        # About section
│   ├── Experience.js   # Work experience
│   ├── Education.js    # Education and certifications
│   ├── Skills.js       # Technical skills
│   ├── Contact.js      # Contact form
│   └── Footer.js       # Footer section
├── App.js              # Main app component
├── index.js            # App entry point
└── index.css           # Global styles
```

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy color customization. Edit the `:root` variables in `src/index.css`:

```css
:root {
  --primary-color: #2563eb;    /* Main brand color */
  --accent-color: #f59e0b;     /* Accent color */
  --text-primary: #1e293b;     /* Primary text color */
  /* ... other colors */
}
```

### Content
Update the content in each component file:
- Personal information in `Hero.js`
- About section in `About.js`
- Experience details in `Experience.js`
- Education info in `Education.js`
- Skills in `Skills.js`
- Contact information in `Contact.js`

### Social Links
Update social media links in:
- `Hero.js` (social links in hero section)
- `Contact.js` (contact section)
- `Footer.js` (footer section)

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 767px and below

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

This creates a `build` folder with optimized production files.

### Deploy to Netlify
1. Build the project: `npm run build`
2. Drag and drop the `build` folder to Netlify
3. Your site will be live!

### Deploy to Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

### Deploy to GitHub Pages
1. Install gh-pages: `npm install --save-dev gh-pages`
2. Add to package.json scripts:
   ```json
   "homepage": "https://yourusername.github.io/portfolio",
   "predeploy": "npm run build",
   "deploy": "gh-pages -d build"
   ```
3. Run: `npm run deploy`

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Contact

**Raja Singh**
- Email: er.singhraja@gmail.com
- Phone: +977 9862940185
- Location: Koteshwar, Nepal
- GitHub: [@RajaCingh](https://github.com/RajaCingh)
- LinkedIn: [rajacingh](https://www.linkedin.com/in/rajacingh/)
- Instagram: [@raja.cingh](https://www.instagram.com/raja.cingh)

---

Made with ❤️ by Raja Singh
