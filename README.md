# E-commerce Website Project 🛍️

## Overview 🌐

Welcome to the **E-commerce Website** project! This is a fully responsive, modern e-commerce platform built using the latest web technologies like **Google Fonts**, **Sass**, **Pug**, and **Bootstrap**. It's designed for users to easily browse products, check out details, and manage their shopping carts with a smooth user experience. 

---

## Technologies Used ⚙️

### 1. **Google Fonts** 📚
   - Elevates typography and makes the website more visually appealing.

### 2. **Sass** 🌿
   - A powerful CSS preprocessor for writing cleaner and more maintainable CSS.
   - *Version*: 1.92.1
   - *Compiled with Dart2js Version*: 3.9.2

### 3. **Pug** 📝
   - A templating engine to streamline HTML creation and enhance readability.
   - *Pug Version*: 2.0.4
   - *Pug CLI Version*: 1.0.0-alpha6

### 4. **Bootstrap** 🖥️
   - A front-end framework that accelerates web design with pre-styled components.
   - *Version*: 5.3 (or latest version used)

### 5. **Swiper.js** 🖥️
   - Used for creating interactive and responsive carousels and slideshows

---

## File Structure 📂

The project is organized in a way that ensures clean and efficient development. Here’s a quick overview of the directory structure:
<pre>
📂 dist/
├── 📂 assets/
│  └── 📂 images/ # Contains all images (product images, icons, etc.)
│
├── 📂 css/
│  ├── 🎨 style.css # Compiled CSS file
│  └── 🗺️ style.css.map # Source map for debugging CSS
│
├── 🛒 cart.html # Compiled HTML for cart page
├── 🗂️ category.html # Compiled HTML for category page
├── 🏠 index.html # Compiled HTML for homepage
└── 📦 productDetails.html # Compiled HTML for product details page
   
📂 stage/
├── 📂 pug/
│  └── 📂 layout/ # Layout files for reusable sections like footer and nav
│    ├── 📄 _mixins.pug   
│    ├── 📄 footer.pug
│    └── 📄 nav.pug
│
├── 📂 scss/
│  ├── 📂 global/ # Global styles and variables
│  │  └── 📄 _global.scss
│  │
│  ├── 📂 helpers/ # Helpers styles and variables
│  │  ├── 📄 _productCard.scss 
│  │  ├── 📄 _reviewCard.scss   
│  │  └── 📄 _images_sizes.scss  
│  │
│  ├── 📂 Layout/ # Layout-specific styles (cart, category, etc.)
│  │  ├── 📄 _cart.scss
│  │  ├── 📄 _category.scss
│  │  ├── 📄 _footer.scss
│  │  ├── 📄 _home.scss
│  │  ├── 📄 _nav.scss
│  │  └── 📄 _productDetails.scss
│  │
│  └── 🎨 style.scss # Main Sass file importing all styles
│
├── 📄 cart.pug # Pug file for cart page
├── 📄 category.pug # Pug file for category page
├── 📄 index.pug # Pug file for homepage
└── 📄 productDetails.pug # Pug file for product details page

</pre>

---

## Project Structure

- **Assets** 🖼️: Contains images like product pictures and icons.

- **SCSS** 💅: Organized into global styles, helper files (variables, image sizes), and layout-specific stylesheets.

- **Pug Files** 📝: Template files that render HTML pages like cart, category, product details, and the homepage.

- **HTML** 🌐: The compiled HTML files are output here.

---

## Class Naming Convention 🎨

This project follows the **kebab-case** naming convention for all class names, ensuring a clean and consistent codebase. For example:

- `.home-trendy-fashionable-couple-posing-img-width`
- `.home-checked-shirt-img-height`

This naming approach enhances the readability of styles and is easy to follow for future development.

---

## How to Run the Server for Sass and Pug 🛠️

To get started with compiling your Sass stylesheets and Pug templates, follow these steps:

### 1. **Running Sass**

  To run Sass and compile your stylesheets:
  
  1. **Install Node.js** (if you haven’t already).
  2. **Install Sass** globally by running:
     ```bash
       npm install sass -g 
     ```
  3. **Compile Sass** from stage/scss to dist/css and watch for changes:
     ```bash
       sass stage/scss:dist/css -w
     ```
   
### 2. **Running Pug**
  To compile Pug templates into HTML:
  
  1. **Install Pug** globally by running:
     ```bash
       npm install pug pug-cli -g
     ```
  2. **Compile Pug** files from stage/ and output them to dist/ while watching for changes:
     ```bash
       pug stage/*.pug -o dist -w -P
     ```
c

---

## Conclusion 🎉

This README covers all essential details to get you started with the project. If you encounter any issues or have questions, don't hesitate to reach out to the team. Happy coding! 😊
