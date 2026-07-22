# 🚀 Festival Musical

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/krosswelcauro/festival-musical?style=for-the-badge)](https://github.com/krosswelcauro/festival-musical/stargazers)

[![GitHub forks](https://img.shields.io/github/forks/krosswelcauro/festival-musical?style=for-the-badge)](https://github.com/krosswelcauro/festival-musical/network)

[![GitHub issues](https://img.shields.io/github/issues/krosswelcauro/festival-musical?style=for-the-badge)](https://github.com/krosswelcauro/festival-musical/issues)

[![GitHub license](https://img.shields.io/github/license/krosswelcauro/festival-musical?style=for-the-badge)](LICENSE)

**A captivating and responsive frontend website to showcase a music festival.**

[Live Demo](https://festival-musical-techn.netlify.app/) <!-- TODO: Add live demo link -->

</div>

## 📖 Overview

"Festival Musical" is a modern and engaging frontend-only web application designed to present information about a music festival. Built with a focus on a dynamic user experience and responsive design, it features dedicated sections for festival details, artist lineup, an immersive image gallery, and engaging video content. The project utilizes Gulp for an efficient development workflow, compiling SASS to CSS, optimizing images, and managing JavaScript.

This project is ideal for event organizers looking for a sleek online presence or as a portfolio piece demonstrating proficiency in front-end development with traditional build tools.

## ✨ Features

-   **Responsive Design**: Optimized for seamless viewing across all devices, from mobile to desktop.
-   **Interactive Navigation**: Smooth scrolling and intuitive navigation to different festival sections.
-   **Dynamic Artist Lineup**: Clearly presented schedule of performing artists and stages.
-   **Immersive Image Gallery**: A dedicated section to showcase memorable moments from the festival.
-   **Engaging Video Showcase**: Integrate video content to give visitors a taste of the festival atmosphere.
-   **Gulp-Powered Workflow**: Automated tasks for SASS compilation, JavaScript processing, and image optimization.
-   **Optimized Assets**: Ensures fast loading times with optimized images and minified code.

## 🖥️ Screenshots

![Screenshot 1 - Hero Section](https://github.com/user-attachments/assets/db6e96ee-0cca-4c09-8b2b-94b161ae7ed0) <!-- TODO: Add actual screenshots -->
_Captivating hero section with event details._

![Screenshot 2 - Lineup Section](https://github.com/user-attachments/assets/136d003e-a446-4601-8d0f-fdc5aac89ebb) <!-- TODO: Add actual screenshots -->
_Detailed artist lineup and schedule._

![Screenshot 3 - Mobile View](https://github.com/user-attachments/assets/15b7de72-a513-4dc9-b5b2-c27bed2b3a4e) <!-- TODO: Add mobile screenshots -->

_Responsive design adapting to smaller screens._

## 🛠️ Tech Stack

**Frontend:**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)

[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

[![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)](https://sass-lang.com/)

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**Build Tools & Workflow:**

[![Gulp](https://img.shields.io/badge/Gulp.js-CB444A?style=for-the-badge&logo=gulp&logoColor=white)](https://gulpjs.com/)

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)

[![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/)

## 🚀 Quick Start

Follow these steps to get the "Festival Musical" project up and running on your local machine.

### Prerequisites
-   **Node.js**: Ensure you have Node.js installed (version 16 or higher is recommended).
    -   You can download it from [nodejs.org](https://nodejs.org/).
-   **npm**: Node Package Manager, which comes with Node.js.

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/krosswelcauro/festival-musical.git
    cd festival-musical
    ```

2.  **Install dependencies**
    This project uses `npm` to manage its dependencies, including Gulp and its plugins.
    ```bash
    npm install
    ```

3.  **Start development server**
    Gulp includes a `dev` task that compiles SASS, processes JavaScript, optimizes images, and starts a local server with live reloading.
    ```bash
    npm run dev
    # Alternatively, if gulp is installed globally or in your path:
    # gulp dev
    ```

4.  **Open your browser**
    Visit `http://localhost:3000` (or the address provided by Browser-Sync in your terminal) to view the application.

## 📁 Project Structure

```
festival-musical/
├── .gitignore         # Specifies intentionally untracked files to ignore
├── gulpfile.js        # Gulp build system configuration
├── index.html         # Main entry point for the web application
├── package-lock.json  # Records the exact dependency tree
├── package.json       # Defines project metadata and scripts
├── src/               # Source files for the application
│   ├── scss/          # SASS/SCSS stylesheets
│   │   ├── base/      # Base styles (variables, mixins, resets)
│   │   ├── components/# Styles for UI components
│   │   ├── layout/    # Layout specific styles (header, footer, sections)
│   │   └── app.scss   # Main SASS entry file
│   ├── js/            # JavaScript files
│   │   └── app.js     # Main JavaScript file
│   └── img/           # Unoptimized image assets
├── video/             # Video assets for the website
└── # Other Gulp-generated directories (e.g., 'build' or 'dist' after compilation)
```

## ⚙️ Configuration

The primary configuration for this project is managed through `gulpfile.js`.

### Gulpfile.js
This file defines all the automated tasks for development and production builds:
-   **SASS Compilation**: Compiles `.scss` files into `.css` and minifies them.
-   **JavaScript Processing**: Concatenates and potentially minifies JavaScript files.
-   **Image Optimization**: Compresses images for faster loading.
-   **WebP Conversion**: Converts images to WebP format for modern browsers.
-   **Browser-Sync**: Sets up a local development server with live reloading.
-   **Watchers**: Monitors `scss`, `js`, and `html` files for changes and automatically re-runs relevant tasks.

## 🔧 Development

### Available Scripts
The `package.json` defines the following primary development script:

| Command     | Description

