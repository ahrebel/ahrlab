# AHR Lab Dashboard

A modern homelab dashboard for accessing self-hosted services. Single HTML file with responsive design and secure access control.

## Features

- Secure login with session-based authentication
- Responsive design for desktop and mobile
- Service cards with status indicators
- Quick actions panel
- Glassmorphic UI with animated background

## Installation

### GitHub Pages
1. Fork this repository
2. Enable GitHub Pages in repository settings
3. Access at `https://[username].github.io/ahrlab`

### Self-Hosted
Simply host the `index.html` file on any web server.

### Local Development
```bash
python -m http.server 8000
# Visit http://localhost:8000
```

## Configuration

### Services
Edit the service cards in the `services-grid` section to match your infrastructure. Each card includes:
- Service name and icon
- Description
- Status indicator
- Direct link to service

### Quick Actions
Modify the quick action buttons in the `quick-actions` section for frequently accessed tools.

### Styling
Update CSS variables in the `:root` section to customize colors and theme.

## Structure

```
index.html          # Single-file dashboard
README.md           # Documentation
```

## Requirements

- Modern web browser (Chrome 88+, Firefox 78+, Safari 14+)
- No server-side dependencies
- Font Awesome CDN for icons

## Security

The dashboard includes a login system with session storage. Configure authentication according to your security requirements.

## License

MIT License

## Contributing

Pull requests are welcome for bug fixes and improvements.
