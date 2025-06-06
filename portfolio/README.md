# Aniket Sharma - Portfolio Website

A modern, responsive portfolio website built with React.js showcasing my projects, experience, and skills as a Full Stack Developer.

## 🚀 Features

- **Single Page Application**: Smooth scrolling between sections
- **Responsive Design**: Works perfectly on all devices
- **Modern UI/UX**: Dark theme with gradient accents
- **Interactive Navigation**: Active section highlighting
- **Social Media Integration**: Links to LinkedIn, GitHub, Instagram, and CodeChef
- **Project Showcase**: Detailed project cards with technologies used
- **Experience Timeline**: Professional experience with certificates
- **Contact Information**: Easy ways to get in touch

## 🛠️ Technologies Used

- React.js 18
- CSS3 with modern features
- Font Awesome Icons
- Google Fonts (Inter)
- Responsive Grid Layout

## 📁 Project Structure

```
portfolio/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
├── package.json
└── README.md
```

## 🔧 Setup Instructions

### Prerequisites

Make sure you have the following installed on your machine:
- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Step 1: Create the Project Directory

```bash
mkdir portfolio
cd portfolio
```

### Step 2: Initialize React App

```bash
npx create-react-app .
```

### Step 3: Replace Default Files

Replace the contents of the following files with the provided code:

1. **package.json** - Copy the package.json content
2. **public/index.html** - Replace with the provided HTML
3. **src/App.js** - Replace with the provided React component
4. **src/App.css** - Replace with the provided CSS styles
5. **src/index.js** - Replace with the provided index file
6. **src/index.css** - Replace with the provided index styles

### Step 4: Add Your Profile Image

1. Add your profile image to the `public` folder
2. Update the image path in `App.js`:
   ```javascript
   // Replace this line in App.js:
   <img src="/api/placeholder/200/200" alt="Aniket Sharma" />
   // With:
   <img src="/your-image-name.jpg" alt="Aniket Sharma" />
   ```

### Step 5: Install Dependencies

```bash
npm install
```

### Step 6: Start the Development Server

```bash
npm start
```

The website will open in your browser at `http://localhost:3000`

## 🌐 Building for Production

To create a production build:

```bash
npm run build
```

This creates a `build` folder with optimized files ready for deployment.

## 📱 Deployment Options

### Option 1: Netlify
1. Build the project: `npm run build`
2. Drag and drop the `build` folder to [Netlify](https://netlify.com)

### Option 2: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow the prompts

### Option 3: GitHub Pages
1. Install gh-pages: `npm install --save-dev gh-pages`
2. Add to package.json scripts:
   ```json
   "homepage": "https://yourusername.github.io/portfolio",
   "predeploy": "npm run build",
   "deploy": "gh-pages -d build"
   ```
3. Run: `npm run deploy`

## 🎨 Customization

### Colors
The website uses a gradient color scheme. To change colors, update the CSS variables in `App.css`:

```css
/* Main gradient: #667eea to #764ba2 */
/* You can replace these colors throughout the CSS file */
```

### Content
Update the following in `App.js`:
- Personal information
- Project descriptions
- Experience details
- Contact information
- Social media links

### Sections
The website includes these sections:
- Home (Hero section with intro)
- About (Personal description)
- Experience (Work experience)
- Projects (Portfolio projects)
- Contact (Contact information)

## 📧 Contact Information

Update the contact details in the Contact section:
- Email: aniket.sharma.ani04@gmail.com
- Phone: +91 9868459890
- LinkedIn: https://www.linkedin.com/in/aniket-sharma-07ba6617b
- GitHub: https://github.com/aniketsharma04

## 🔗 Important Links

Make sure to update these links in the code:
- Resume: https://drive.google.com/file/d/1Q4MGACbfBGZ9hLd2ZiOLZWp-uXr4pmMs/view
- LinkedIn: https://www.linkedin.com/in/aniket-sharma-07ba6617b
- GitHub: https://github.com/aniketsharma04
- Instagram: https://www.instagram.com/aniketsharma054
- CodeChef: https://www.codechef.com/users/anikets_iiitn
- Certificates: https://drive.google.com/drive/folders/1selpuO4G5cXY0fIO8SeokSLu71l7o7N7

## 🐛 Troubleshooting

### Common Issues:

1. **Port already in use**: If port 3000 is busy, React will automatically use the next available port
2. **Module not found**: Run `npm install` to install all dependencies
3. **Build errors**: Check console for specific error messages
4. **Images not loading**: Ensure images are in the `public` folder and paths are correct

### Performance Tips:

1. Optimize images before adding them
2. Use WebP format for better compression
3. Minimize CSS and JavaScript in production builds

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use!

---

**Made with ❤️ by Aniket Sharma**