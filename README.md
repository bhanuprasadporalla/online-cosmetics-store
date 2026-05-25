# online-cosmetics-store

This repository contains a simple static HTML website deployed with Azure Static Web Apps. The current site is built from a single `index.html` file and presents a personal resume page with profile details, education, skills, internship information, and image sections.

## Project Overview

- Static frontend built with HTML.
- No build tools, package manager, or backend API are required.
- Uses externally hosted images from Cloudinary.
- Includes GitHub Actions workflows for Azure Static Web Apps deployment.

## Files

```text
.
|-- index.html
|-- README.md
`-- .github/workflows/
    |-- azure-static-web-apps-blue-ground-04f0d0c1e.yml
    |-- azure-static-web-apps-gray-plant-0cceea500.yml
    `-- azure-static-web-apps-lemon-desert-0c749351e.yml
```

## How To Run

Open `index.html` directly in a browser.

No installation step is needed because the project does not use Node.js, npm, or any external build process.

## Deployment

The repository is configured for Azure Static Web Apps. On pushes to the `main` branch, the GitHub Actions workflows upload the root folder as the app source:

- `app_location: "/"`
- `api_location: ""`
- `output_location: "."`

## Repository

GitHub remote:

```text
https://github.com/bhanuprasadporalla/online-cosmetics-store.git
```
