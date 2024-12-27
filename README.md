# Webpage Styling Demonstrations

This repository contains HTML files demonstrating the effect of different CSS approaches on webpage styling: **Without any normalization**, **With a CSS reset**, and **With normalize.css**. The goal is to show how each method influences the layout, appearance, and consistency of various HTML elements like headings, paragraphs, lists, tables, and form controls across different browsers.

## Table of Contents

1. [Overview](#overview)
2. [Without Any Normalization](#without-any-normalization)
3. [With a CSS Reset](#with-a-css-reset)
4. [With normalize.css](#with-normalizecss)
5. [Screenshots](#screenshots)

## Overview

Browsers apply their own default styles to HTML elements like headings, paragraphs, tables, and form controls. These styles can vary significantly between different browsers. To mitigate this issue, developers use techniques like **CSS resets** or **normalize.css** to ensure consistency across browsers.

### Three Main Approaches:
1. **Without Any Normalization**: Relies on the default browser styles, which can vary widely.
2. **With a CSS Reset**: Removes most browser default styles (e.g., margins, padding), giving you a clean slate to work from.
3. **With normalize.css**: A more refined approach that normalizes styles, ensuring consistency while keeping some useful defaults.

## Without Any Normalization

In this approach, the webpage is styled entirely with the default browser styles. Each browser applies its own settings for margins, padding, fonts, and other properties, which can result in inconsistent displays across different browsers.

- **Outcome**: Margins, padding, font sizes, and layout can look very different depending on the browser used.
- **Example**: Headings might have different spacing in Chrome compared to Firefox. Lists might display with different bullet points or indentation.

**Add a picture here showing the result of this approach.**

## With a CSS Reset

A **CSS Reset** is a technique that removes all default margins, padding, and other styles applied by browsers. This approach clears out all the built-in styles to provide a "blank slate" for styling.

- **Outcome**: All elements (headings, paragraphs, lists, etc.) will have no margin or padding, so developers will need to explicitly set them.
- **Example**: After applying a CSS reset, you can control all the styles from scratch, but it may require extra work to redefine basic layouts, such as spacing between elements.

**Add a picture here showing the result of the CSS reset approach.**

## With normalize.css

**normalize.css** is a modern, more refined alternative to CSS resets. Instead of completely removing browser-specific styles, **normalize.css** preserves useful default styles while addressing inconsistencies in how browsers render certain elements.

- **Outcome**: Provides a consistent and clean starting point while preserving sensible defaults like form element styling, button appearances, and list bullet points.
- **Example**: Normalizes font sizes, line heights, and margins for elements like headings, paragraphs, and lists, making them appear the same across all modern browsers.

Normalize.css ensures that all elements are rendered with predictable styling while respecting the built-in styles that make sense (like form inputs and buttons). This is less intrusive than a full CSS reset and is often a better choice for modern web development.

**Add a picture here showing the result of using normalize.css.**

## Screenshots

Below are screenshots of the webpage rendered using the different styling techniques. These images will help you understand the differences in how the page appears with different methods:

- **Without Normalization**:  
  ![Without Normalization](path_to_image_1.png)

- **With CSS Reset**:  
  ![With CSS Reset](path_to_image_2.png)

- **With normalize.css**:  
  ![With normalize.css](path_to_image_3.png)

## Summary

- **Without Normalization**: You get browser-specific styles, which can cause inconsistencies between browsers.
- **With CSS Reset**: All default styles are removed, but you have to manually define the appearance of every element, which can lead to extra work.
- **With normalize.css**: The best of both worlds—provides a consistent baseline for all elements without stripping away useful default styles.

By using **normalize.css**, you ensure that your page is styled consistently across all modern browsers, with minimal effort. It allows you to build your design on a stable foundation without dealing with cross-browser quirks.

---

## How to Use normalize.css

To use **normalize.css** in your project, simply add the following link in your HTML `<head>`:

```html
<link rel="stylesheet" href="https://necolas.github.io/normalize.css/8.0.1/normalize.css">
```
Alternatively, you can download and include the file locally in your project by visiting the normalize.css repository at:

- https://necolas.github.io/normalize.css/8.0.1/normalize.css

This will ensure that your website or application renders consistently across all modern browsers.