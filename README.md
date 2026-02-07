# Valentine Letter Website 💌

A cute interactive Valentine's Day website featuring an animated envelope and letter with a special question!

## Features

- 🎁 Animated envelope that opens to reveal a letter
- 💝 Interactive "Will you be my Valentine?" question
- 🐱 Adorable cat animations
- 🎯 Playful "No" button that runs away
- 💕 Sweet success message when "Yes" is clicked

## Deployment

This website is configured to automatically deploy to GitHub Pages.

### How it works:

1. The site automatically deploys when changes are pushed to the `main` branch
2. GitHub Actions workflow (`.github/workflows/deploy.yml`) handles the deployment
3. The site will be available at: `https://bharjap.github.io/valentinenini/`

### Setup Instructions:

To enable GitHub Pages for this repository:

1. Go to your repository on GitHub
2. Click on **Settings** → **Pages** (in the left sidebar)
3. Under **Source**, select **GitHub Actions** as the deployment source
4. Merge this PR to the `main` branch
5. The workflow will automatically run and deploy your site

### Manual Deployment:

You can also manually trigger a deployment:

1. Go to the **Actions** tab in your repository
2. Select the "Deploy to GitHub Pages" workflow
3. Click "Run workflow" → "Run workflow"

## Local Development

To run this website locally:

1. Clone the repository
2. Open `index.html` in your web browser, or
3. Use a local development server like:
   ```bash
   python -m http.server 8000
   ```
   or
   ```bash
   npx serve
   ```

Then open `http://localhost:8000` in your browser.

## File Structure

- `index.html` - Main HTML file
- `style.css` - Styling and animations
- `script.js` - Interactive JavaScript functionality
- `*.png`, `*.gif`, `*.jpg` - Image assets

## Technologies Used

- HTML5
- CSS3 (with animations)
- Vanilla JavaScript
- Google Fonts (Pixelify Sans)

---

Made with ❤️ for Valentine's Day
