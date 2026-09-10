# QloApps

Open-source hotel management and reservation platform. One codebase covers the property management system, public booking website, front-desk operations, revenue tools, and channel management.

## Overview

QloApps is a full-stack hospitality product: hotels can publish inventory, take bookings, run the front desk, and connect payments without assembling a PMS and a booking engine from separate vendors. This repository is the engineering copy used in the [Anton Karas portfolio](https://github.com/antonkarasbiz/portfolio).

## Capabilities

- Hotel website and booking engine
- Reservations, occupancy, and room inventory
- Front-desk and guest operations
- Revenue management and reporting
- POS and payment integrations
- Channel management for distribution
- Modular add-ons for property-specific workflows

## Requirements

### Hosted

- Web server: Apache 1.3 / 2.x, Nginx, or Microsoft IIS
- PHP 8.1–8.4
- MySQL 5.7+ through 8.4
- SSH or FTP access
- PHP: `memory_limit=128M`, `upload_max_filesize=16M`, `max_execution_time=500`, `allow_url_fopen=on`
- Extensions: PDO_MySQL, cURL, OpenSSL, SOAP, GD, SimpleXML, DOM, Zip, Phar
- SSL certificate when card payments are processed on-site

### Local

Same PHP/MySQL/extension baseline on Windows, macOS, or Linux (Wamp, XAMPP, or equivalent).

## Installation

1. Provision PHP, MySQL, and a virtual host pointing at this tree.
2. Follow the installer in the browser, or use the published Docker image when a container workflow is preferred.

```bash
docker pull webkul/qloapps_docker
```

Official install notes: [qloapps.com/install-qloapps](https://qloapps.com/install-qloapps/)

## Documentation

- Product: [qloapps.com](https://www.qloapps.com)
- Docs: [docs.qloapps.com](https://docs.qloapps.com/)
- Add-ons: [qloapps.com/addons](https://qloapps.com/addons/)

## License

QloApps core is licensed under OSL-3.0. Modules authored by Webkul keep the license file in each module root; other modules use AFL-3.0. See [LICENSE.md](LICENSE.md).

## Maintainer

[Anton Karas](https://github.com/antonkarasbiz) — full-stack, blockchain, and AI engineering.
