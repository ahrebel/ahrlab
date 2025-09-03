# AHR Lab - Homelab Dashboard

A modern, responsive web dashboard for managing and accessing your homelab services. Built with vanilla HTML, CSS, and JavaScript for easy deployment on GitHub Pages.

## Features

- **Clean, Modern Design** - Glassmorphism UI with dark theme
- **Responsive Layout** - Works perfectly on desktop, tablet, and mobile
- **Service Cards** - Quick access to all your homelab services
- **System Overview** - At-a-glance stats and status indicators
- **Smooth Animations** - Subtle hover effects and transitions
- **Single File** - No build process required, just deploy and go

## Services Included

The dashboard comes pre-configured with cards that I currently use:

- 🛡️ **Pi-hole** - Network ad blocking and DNS filtering
- 🤖 **Local LLM** - Self-hosted AI chat interface

## Quick Start

1. **Clone this repository**
   ```bash
   git clone https://github.com/ahrebel/ahrlab.net.git
   ```

2. **Customize your services**
   - Edit `index.html`
   - Update subdomain URLs to match your setup
   - Modify service descriptions and icons as needed

3. **Deploy to GitHub Pages**
   - Push to your repository
   - Enable GitHub Pages in repository settings
   - Optionally configure custom domain

## Customization

### Adding a New Service

Copy an existing service card and modify:

```html
<div class="service-card">
    <div class="service-header">
        <div class="service-icon your-color-class">
            <i class="fas fa-your-icon"></i>
        </div>
        <div class="service-title">Your Service</div>
    </div>
    <div class="service-description">
        Description of your service...
    </div>
    <a href="http://yourservice.ahrlab.net" class="service-link">
        <i class="fas fa-external-link-alt"></i>
        Access Service
    </a>
</div>
```

### Updating Stats

Modify the values in the stats section or make them dynamic by connecting to your monitoring APIs.

### Styling

All styles are contained in the `<style>` section. Key variables:
- Color scheme: Update gradient colors and accent colors
- Service icons: Modify `.service-icon` background gradients
- Layout: Adjust grid columns in `.services-grid`

## Domain Setup

If using a custom domain like `ahrlab.net`:

1. Add your domain in GitHub Pages settings
2. Create DNS records:
   - `CNAME` record: `ahrlab.net` → `yourusername.github.io`
   - `CNAME` record: `www.ahrlab.net` → `yourusername.github.io`

## Tech Stack

- **HTML5** - Semantic structure
- **CSS3** - Modern styling with flexbox/grid
- **JavaScript** - Interactive animations
- **Font Awesome** - Icon library
- **GitHub Pages** - Free hosting

## License

MIT License - Feel free to use, modify, and distribute as needed.

## Contributing

This is a personal homelab dashboard, but feel free to fork and create your own version! Pull requests for general improvements are welcome.

---

**Built for the homelab community**
