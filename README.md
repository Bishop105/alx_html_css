# ALX HTML & CSS Project
CSS Advanced Project

## Overview
This repository contains basic HTML and CSS files for a web project. It includes styled HTML pages using CSS.

## Directory Structure

Here’s a filled-in example README you can adapt for your own repository.
It keeps the structure you provided but replaces the placeholders with concrete details for a **CSS Advanced Flexbox Layout Project**.

---

# CSS Advanced Project

## Table of Contents

* [Introduction](#introduction)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)

## Introduction

This project is a responsive multi-section webpage built entirely with **modern CSS techniques**—notably Flexbox and media queries.
Its purpose is to demonstrate how to create a professional, mobile-friendly layout without relying on heavy frameworks.
It solves the common problem of building a clean three-section page (header, main content with sidebar, and footer) that gracefully adapts to any screen size.

## Features

* **Pure Flexbox Layout** – No floats or external layout libraries; easy to understand and maintain.
* **Responsive Design** – Scales smoothly from large desktop screens down to small smartphones.
* **Scrollable Sections** – `overflow-y: auto` allows independent scrolling in the main article and sidebar.
* **Customizable Theme** – Easily change colors, fonts, and backgrounds in a single CSS file.
* **Lightweight** – Only HTML and CSS, zero JavaScript required for core layout.

## Technologies Used

* **HTML5** – Semantic markup for structure.
* **CSS3** – Flexbox, media queries, and custom properties.
* *(Optional)* Sass/SCSS for easier variable management and nesting (if you compile from `src/scss`).

No external CSS framework is required, keeping the project dependency-free.

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/css-advanced-project.git
   cd css-advanced-project
   ```
2. **(Optional) Install Sass** if you plan to edit SCSS files

   ```bash
   npm install -g sass
   ```
3. **Build CSS (if using Sass)**

   ```bash
   sass src/scss/styles.scss public/styles.css
   ```
4. **Open in a browser**
   Simply double-click `index.html` or use a local server:

   ```bash
   npx serve public
   ```

## Usage

* Resize your browser window or open the site on a phone to see the layout adapt.
* Scroll within the **Article** and **Aside** sections to test independent scrolling.
* To customize:

  1. Open `styles.css`.
  2. Adjust colors, fonts, or padding.
  3. Reload the page to view changes.


## Contributing

Contributions are welcome!

1. Fork the repo and create a new branch:

   ```bash
   git checkout -b feature/your-feature
   ```
2. Commit changes and push:

   ```bash
   git commit -m "Add your feature"
   git push origin feature/your-feature
   ```
3. Open a Pull Request describing your changes.

Please follow the existing CSS style conventions and keep commits concise.

## License

This project is licensed under the **MIT License**—you’re free to use, modify, and distribute it with proper attribution.
