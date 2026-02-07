# website
A personal website

## GitHub Pages Deployment

This website is automatically deployed to GitHub Pages using GitHub Actions.

### How it works

1. When you push to the `main` or `master` branch, the GitHub Actions workflow automatically triggers
2. The workflow deploys the static HTML files to GitHub Pages
3. Your website will be available at your GitHub Pages URL

### Manual Deployment

You can also manually trigger the deployment:
1. Go to the "Actions" tab in your GitHub repository
2. Select the "Deploy to GitHub Pages" workflow
3. Click "Run workflow"

### Setup Instructions

To enable GitHub Pages for this repository:
1. Go to your repository Settings
2. Navigate to "Pages" in the sidebar
3. Under "Build and deployment", select "GitHub Actions" as the source
4. The workflow will automatically deploy on the next push to main/master

### Custom Domain

A custom domain (www.gautamashish.com.np) is configured via the CNAME file.
