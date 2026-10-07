# Sudeeksha Ballanda — Personal Portfolio Website

A clean, modern, minimalist personal portfolio website built with HTML5, CSS3, and JavaScript. Designed specifically for software engineering internship applications and developer profiles.

## 🚀 Features

- **Frontend Only**: 100% static, fast-loading, zero backend dependencies, zero database requirements.
- **Sophisticated Dark Theme**: Deep navy background (`#090d16`), subtle sky blue and indigo accents, glassmorphic cards, and clean typography (`Inter` & `Fira Code`).
- **Responsive Layout**: Designed to look great across mobile devices, tablets, and desktop displays.
- **Interactive Project Filtering**: Filter featured projects by category (*Web & Systems*, *IoT & Blockchain*, *Problem Solving / DSA*, *Data & GIS*).
- **SEO & Social Metadata**: Pre-configured OpenGraph tags, semantic HTML5 structure, and accessibility skip links.
- **Factually Grounded**: No invented URLs, fake stats, or percentage bars. Uses real profile links and displays "Repository coming soon" for unlinked repositories.

## 📁 Project Structure

```
PB-portfolio/
├── index.html       # Main HTML markup
├── style.css        # Custom CSS design system & responsive styling
├── script.js        # Dynamic UI interactions & project filters
├── favicon.svg      # Custom developer SVG favicon
└── README.md        # Documentation
```

## 🌐 Deploying to GitHub Pages

1. Commit and push all files to your GitHub repository:
   ```bash
   git add .
   git commit -m "Build personal portfolio site"
   git push origin main
   ```
2. Go to your repository settings on GitHub: **Settings > Pages**.
3. Under **Build and deployment**, select **Source: Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then click **Save**.
5. Your portfolio site will be live at `https://sudeekshaballanda-hub.github.io/PB-portfolio` (or your repository name).

## 🛠️ Local Development & Preview

You can open `index.html` directly in any standard browser or use a simple HTTP server:

```bash
# Using Python
python -m http.server 8000

# Or using Node.js npx
npx serve .
```
