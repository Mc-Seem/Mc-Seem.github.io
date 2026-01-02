# CLAUDE.md

## Project Overview
This is a GitHub Pages repository (`Mc-Seem.github.io`) - a personal website/portfolio hosted on GitHub Pages.

## Repository Information
- **Repository Name**: Mc-Seem.github.io
- **Type**: GitHub Pages Site
- **Platform**: GitHub Pages (typically serves static HTML/CSS/JS)
- **URL**: https://mc-seem.github.io (when published)

## Project Structure
Currently, this is a minimal repository with:
- `README.md` - Basic repository information
- `.git/` - Git version control
- `CLAUDE.md` - This file (context for Claude AI)

## Technology Stack
Expected technologies for a GitHub Pages site:
- HTML/CSS/JavaScript (static site)
- Potential frameworks: Jekyll, Hugo, or plain static HTML
- May include: Bootstrap, React, Vue.js, or other frontend frameworks

## Development Guidelines

### GitHub Pages Specific
- Main branch content is served at `https://mc-seem.github.io`
- `index.html` in root directory will be the homepage
- Jekyll is automatically supported by GitHub Pages
- Custom domains can be configured via CNAME file

### Git Workflow
- Main branch: `master`
- Clean working tree status
- Last commit: "Initial commit" (b0bc700)

### File Organization Best Practices
```
/
├── index.html          # Homepage
├── css/               # Stylesheets
├── js/                # JavaScript files
├── assets/            # Images, fonts, etc.
├── pages/             # Additional pages
├── _config.yml        # Jekyll config (if using Jekyll)
└── README.md          # Project documentation
```

## Common Tasks

### Adding Content
- Create or modify HTML files in the root or subdirectories
- Add styles in CSS files
- Include JavaScript for interactivity

### Testing Locally
```bash
# For Jekyll sites
bundle exec jekyll serve

# For static sites, use any local server
python -m http.server 8000
# or
npx serve
```

### Deploying
- Push to `master` branch
- GitHub Pages automatically builds and deploys
- Changes typically appear within a few minutes

## Dependencies Management
- Ensure `.gitignore` includes:
  - `node_modules/` (if using npm)
  - `_site/` (if using Jekyll)
  - `.DS_Store` (macOS)
  - Any build artifacts or local environment files

## Notes for Claude
- This is a personal website/portfolio project
- Prioritize clean, semantic HTML and accessible design
- Keep dependencies minimal for faster loading
- Optimize images and assets for web
- Ensure responsive design for mobile/tablet/desktop
- Test cross-browser compatibility

## Resources
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Jekyll Documentation](https://jekyllrb.com/docs/) (if applicable)
- [Web Accessibility Guidelines](https://www.w3.org/WAI/WCAG21/quickref/)

---
*Last Updated: 2026-01-02*
