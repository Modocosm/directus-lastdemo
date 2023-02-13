---
title: Directus
description: A one-click-install Directus instance using PostgreSQL. Always install lastest version know of Directus.
tags:
  - javascript
  - directus
  - cms
  - postgreSQL
---

# Directus railway template

This example runs a [Directus](https://directus.io/) instance with minimal config using PostgreSQL.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/2fy758?referralCode=4ArgSI)

## ✨ Features

- Directus
  - "directus-extension-action-button": "^1.0.1",
  - "directus-extension-api-docs": "^1.5.1",
  - "directus-extension-display-link": "^1.6.1",
  - "directus-extension-editorjs": "^1.5.0",
  - "directus-extension-svgmap-picker-interface": "^0.1.0",
  - "directus-extension-tags-m2m-interface": "^0.8.0",
  - "directus-extension-vgrid-interface": "^1.0.15",
  - "directus-extension-wpslug-interface": "^1.1.0",
  - "directus-extension-vgrid-interface": "^1.0.15",
  
- Javascript
- PostgreSQL
- "pg": "^8.9.0"

## 💁‍♀️ How to use

- Add the .env vars on template (you can add more vars when the app is deployed).
- Let railway deploy your service, grab the generated domain from the service settings.
- Login in the panel using the defined ADMIN_EMAIL and ADMIN_PASSWORD used in .env vars

## 📝 Notes

- This is a minimal one-click-deploy solution to Directus, see [Directus docs](https://docs.directus.io/getting-started/introduction.html) to config it to your needs.

- Re deploys won't erase your db data since according to Directus docs `Directus will use an existing .env file (or existing environment variables) to either install the database (if it's empty) or migrate it to the latest version (if it already exists and has missing migrations).` but be careful!