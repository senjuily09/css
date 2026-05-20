# 🎨 CSS Fundamentals Practice

## 📖 Overview
This repository contains my hands-on practice files for core Cascading Style Sheets (CSS). Following up on my HTML foundations, these stylesheets document my progression in learning how to control layout, typography, spacing, and the overall visual aesthetics of a webpage. 

## 🗂️ What's Included
The files are broken down by specific CSS properties and concepts to isolate and master each technique:

* **The Box Model & Layout (`boxmodel.css`, `margin.css`, `outline.css`, `display.css`):** * Mastering how elements take up space (content, padding, borders, and margins).
  * Understanding document flow using block, inline, and inline-block display properties.
* **Typography & Text (`font.css`, `text.css`):** * Controlling font families, sizes, weights, text alignment, and decorations.
* **Colors & Visuals (`color.css`, `icon.css`):** * Applying hex, RGB, and named colors to text and backgrounds, alongside styling web icons.
* **Styling Specific Elements (`lists.css`, `tables.css`, `stylelinks.css`):** * Customizing list markers, adding borders and zebra-striping to tables, and handling pseudo-classes for links (`:hover`, `:visited`, `:active`).
* **Basics & Assets (`intro.css`, `rukia.jpg.jpg`):** * Introductory syntax, basic selectors, and practicing with external image assets.

## 🧠 Key Takeaways
* **The Box Model:** Realizing that every HTML element is essentially a box, which is the most critical concept for debugging layout issues.
* **Separation of Concerns:** Keeping styling entirely separate from HTML structure to maintain clean, readable, and scalable code.

## 🚀 How to View
Because this repository primarily contains `.css` files, they need to be attached to an HTML document to render visually.

1. Clone this repository to your local machine.
2. Create a basic `index.html` file in the same directory.
3. Link the CSS file you want to test in the `<head>` of your HTML document:
   ```html
   <link rel="stylesheet" href="boxmodel.css">
