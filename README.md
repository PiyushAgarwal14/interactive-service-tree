# Interactive Service Tree

[![License: GPL v2 or later](https://img.shields.io/badge/License-GPLv2%2B-blue.svg)](https://www.gnu.org/licenses/gpl-2.0.html)

An interactive WordPress plugin that displays an expandable, hierarchical tree of services with modal popups for detailed information. Ideal for showcasing complex service structures with parent and child services in a clean, user-friendly way.

---

## Table of Contents

- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Creating Services](#creating-services)  
- [Shortcode](#shortcode)  
- [FAQ](#faq)  
- [Screenshots](#screenshots)  
- [Changelog](#changelog)  
- [License](#license)  

---

## Features

- Create hierarchical services using a custom post type (`ist_service`).  
- Expand/collapse parent services to reveal child services.  
- Click on any service to open a modal popup showing detailed content.  
- AJAX-powered loading of service details for smooth user experience.  
- Clean and lightweight with minimal dependencies (only jQuery).  
- Easy to customize CSS and JavaScript.  

---

## Installation

1. Download or clone this repository to your WordPress `/wp-content/plugins/` directory:  
   ```bash
   git clone https://github.com/PiyushAgarwal14/interactive-service-tree.git
   
2. Activate the plugin through the WordPress Admin Dashboard under Plugins > Installed Plugins.

3. Add the shortcode [interactive_services] to any post or page where you want the service tree to appear.

# Usage

## Creating Services
- Navigate to Services > Add New in your WordPress Admin.

- Add a Title and Content describing your service.

- To create child services, use the Parent option in the right sidebar to assign a parent service.

- Publish the service.

# Displaying the Service Tree
- Insert the shortcode [interactive_services] in the content editor of the page or post where you want the tree displayed.

- The frontend will render a collapsible tree with all parent and child services.

- Clicking on any service item will open a modal with detailed information loaded via AJAX.

# Shortcode
[interactive_services]

Outputs the interactive service tree with modal popups.

# FAQ
## Q: How do I add child services?
A: When creating or editing a service, use the Parent dropdown in the sidebar to select the parent service. This makes your service a child of the selected parent.

## Q: Can I customize the modal style?
A: Yes! Edit the CSS file located in css/style.css or add custom styles in your theme’s stylesheet to override the plugin styles.

## Q: Does this plugin support Gutenberg?
A: Yes, the custom post type supports the block editor (show_in_rest enabled).

# Screenshots
- Service Tree View — Shows the hierarchical expandable list of services.

  <img src="https://raw.githubusercontent.com/PiyushAgarwal14/interactive-service-tree/refs/heads/main/Screenshot1.png" />

- Modal Popup — Shows detailed service content on clicking a service item.
-  <img src="https://raw.githubusercontent.com/PiyushAgarwal14/interactive-service-tree/refs/heads/main/Screenshot2.png" />

# Changelog
1.0
- Initial release with full hierarchical service tree and AJAX-powered modals.

# License
This plugin is licensed under the GPLv2 or later.

# Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss your ideas.

## Support
If you encounter any issues or have questions, please open an issue on GitHub.

## Author
Piyush Agarwal

