<p align="center">
  <picture><source media="(prefers-color-scheme: dark)" srcset="https://global.media.stuxedo.com/logo-light.png"><source media="(prefers-color-scheme: light)" srcset="https://global.media.stuxedo.com/logo-dark.png"><img src="https://global.media.stuxedo.com/logo-dark.png" height="100" alt="Stuxedo Logo"></picture>
</p>

# Maintenance Page

A clean and simple maintenance page template for Stuxedo services.

## Overview

This repository contains a lightweight HTML page designed to inform users of ongoing maintenance on a Stuxedo service. It's perfect for keeping users informed while work is being carried out.

## Features

- 📄 Simple, clean HTML structure
- ⚡ Lightweight and fast-loading
- 🎨 Ready to customize
- 📱 Responsive design
- 🚀 Deployed at [maintenancepage.stuxedo.net](https://maintenancepage.stuxedo.net)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Stuxedo/maintenancepage.git
   ```

2. Open `index.html` in your browser or deploy to your hosting provider

## Customization

Edit the HTML files to:
- Update the maintenance message
- Add your branding and logo
- Customize colors and styling
- Include contact or status links

## Deployment

This project uses GitHub Pages and can be automatically deployed to your desired domain.

The live version is deployed at [maintenancepage.stuxedo.net](https://maintenancepage.stuxedo.net).

## Previous designs

This repository always holds the current Stuxedo design (v2, the tuxedo-cat logo colours). Earlier designs are preserved as their own archived repositories:

- [maintenancepage-v1](https://github.com/Stuxedo/maintenancepage-v1): the original green design, live at [maintenancepage-v1.stuxedo.net](https://maintenancepage-v1.stuxedo.net/)

## License

This project is open source and available for use and modification.

---

*Built & Maintained by <picture><source media="(prefers-color-scheme: dark)" srcset="https://global.media.stuxedo.com/icon-light.png"><source media="(prefers-color-scheme: light)" srcset="https://global.media.stuxedo.com/icon-dark.png"><img src="https://global.media.stuxedo.com/icon-dark.png" height="14" alt="Stuxedo" valign="middle"></picture> [Stuxedo](https://github.com/Stuxedo).  
Stuxedo is a part of the <picture><source media="(prefers-color-scheme: dark)" srcset="https://global.media.stux.group/icon-light.png"><source media="(prefers-color-scheme: light)" srcset="https://global.media.stux.group/icon-dark.png"><img src="https://global.media.stux.group/icon-dark.png" height="14" alt="Stux.Group" valign="middle"></picture> Stux.Group brand of businesses.*

## Local preview

Run `./dev-server.sh` (or `dev-server.bat`, add a port as the last argument) to serve the site at `http://127.0.0.1:8000` the way GitHub Pages does, with the dev-mode banner on. Add `--no-dev-mode` to see it exactly as production does, or `?banner=soon,maintenance,site` to preview the other banner types. It uses PHP 7.4's built-in server (set `PHP_BIN` to pick another PHP).
