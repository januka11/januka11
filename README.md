# Dhurba's Blog

Welcome to my personal blog repository! This repository contains various projects and content related to blogging, coding, and more. Here, you'll find code snippets, templates, and resources to help you get started with your own blog or projects.

---

## About Me

<p align="center">
  <span id="sideAnimation">I am Dhurba</span>
</p>

---

## Repository Contents

- `index.html` - A basic structure for a personal blog.
- `styles.css` - The styles and layout for the blog.
- `scripts.js` - JavaScript functionality for future enhancements.

---

## Side Animation Example

The following is a simple animation showing the text "I am Dhurba" sliding from the left to the right of the page.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Side Animation</title>
  <style>
    #sideAnimation {
      position: absolute;
      left: -300px;
      font-size: 2em;
      font-weight: bold;
      animation: slideIn 3s forwards;
    }

    @keyframes slideIn {
      100% {
        left: 50%;
      }
    }
  </style>
</head>
<body>
  <div id="sideAnimation">I am Dhurba</div>
</body>
</html>
