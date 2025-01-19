# HTML Quick Guide

## Table of Contents
1. [Introduction to HTML](#introduction-to-html)
2. [Basic Structure of an HTML Document](#basic-structure-of-an-html-document)
3. [Common HTML Elements](#common-html-elements)
   - [Headings](#headings)
   - [Paragraphs](#paragraphs)
   - [Links](#links)
   - [Images](#images)
   - [Lists](#lists)
4. [Forms and Inputs](#forms-and-inputs)
5. [Tables](#tables)
6. [Semantic Elements](#semantic-elements)
7. [HTML Attributes](#html-attributes)
8. [HTML5 New Features](#html5-new-features)
9. [Best Practices](#best-practices)

---

## Introduction to HTML
HTML (HyperText Markup Language) is the standard language for creating webpages. It describes the structure of a webpage using elements represented by tags.

---

## Basic Structure of an HTML Document
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Welcome to HTML</h1>
    <p>This is a basic structure of an HTML document.</p>
</body>
</html>
```

---

## Common HTML Elements
### Headings
```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Smaller Heading</h3>
```

### Paragraphs
```html
<p>This is a paragraph of text.</p>
```

### Links
```html
<a href="https://example.com">Visit Example</a>
```

### Images
```html
<img src="image.jpg" alt="Description of image">
```

### Lists
#### Ordered List
```html
<ol>
    <li>First item</li>
    <li>Second item</li>
</ol>
```

#### Unordered List
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```

---

## Forms and Inputs
```html
<form action="/submit" method="POST">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">

    <label for="email">Email:</label>
    <input type="email" id="email" name="email">

    <button type="submit">Submit</button>
</form>
```

---

## Tables
```html
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Alice</td>
        <td>25</td>
    </tr>
    <tr>
        <td>Bob</td>
        <td>30</td>
    </tr>
</table>
```

---

## Semantic Elements
```html
<header>
    <h1>Page Header</h1>
</header>

<main>
    <p>Main content goes here.</p>
</main>

<footer>
    <p>Footer content here.</p>
</footer>
```

---

## HTML Attributes
Attributes provide additional information about elements.
```html
<a href="https://example.com" target="_blank">Open in new tab</a>
<img src="image.jpg" alt="Sample image" width="500">
```

---

## HTML5 New Features
- **Audio and Video**
```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
</audio>

<video controls>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video element.
</video>
```


```

---

## Best Practices
1. Use semantic tags for better accessibility.
2. Always include the `alt` attribute for images.
3. Validate your HTML code to ensure it follows standards.
4. Use external stylesheets and scripts to keep HTML clean.

---
