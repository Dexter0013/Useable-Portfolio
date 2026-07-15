# Useable Portfolio Template

A clean, fast, multipage portfolio template that anyone can customize and use for their own personal website.

## Demo

- Live Demo: https://dexter0013.github.io/Useable-Portfolio/index.html

## Features

- Easy to set up
- Fully responsive
- Multipage structure
- SEO-friendly
- No extra frameworks required
- No extra libraries required
- Customizable color theme
- Great lighthouse/audit performance

## Tech Stack

- HTML
- CSS
- JavaScript
- SASS

## Getting Started

### 1) Clone the repository

```bash
git clone https://github.com/Dexter0013/Useable-Portfolio.git
cd Useable-Portfolio
```

### 2) Install dependencies

```bash
npm install
```

### 3) Start SASS compilation

```bash
npm run compile:scss
```

### 4) Open the project

Open `index.html` in your browser or use a Live Server extension.

## How to Customize

### Update your colors

Edit:

```scss
sass/abstracts/_variables.scss
```

Change this variable:

```scss
$themeClrPrimary: #0062b9;
```

### Update your homepage content

Edit `index.html` and replace the sample information with your own:

- Name and logo in the header
- Hero section title and bio
- About section details and skills
- Project titles, descriptions, and links
- Contact section content
- Footer name and social links

### Update project pages

Edit:

- `project-1.html`
- `project-2.html`
- `project-3.html`

Replace the mockups, descriptions, live links, and code links with your own project details.

## Deployment

This template can be deployed easily with Netlify.

Recommended settings:

- Build command: `npm run build`
- Publish directory: your generated build folder

## Folder Overview

- `index.html` — homepage
- `project-1.html` — project case study page
- `project-2.html` — project case study page
- `project-3.html` — project case study page
- `sass/` — styles source files
- `assets/` — images and icons
- `scripts/` — JavaScript files

## For Users

This repository is meant to be a starting point for a portfolio website. You can use it as a base for:

- personal portfolios
- developer portfolios
- freelancer landing pages
- project showcase sites

Feel free to clone it, edit the content, and make it your own.

## License

Licensed under GPL-3.0.
