# Web Programming – My Study Notes

## Getting Started

This README is my own summary of the main HTML, CSS and Responsive Design topics I am learning. I wrote these notes to help myself remember the important ideas in a simple way. Some things might sound basic, but they help me understand the big picture. Also, some parts are **extra important**, so I highlight them.

---

## HTML – Building the Structure

HTML is like the skeleton of a webpage. It tells the browser what each part of the page is. I’m still learning, but I try to practice by building small pages.

### What I Study in HTML

* How basic elements work (headings, paragraphs)
* Typography (strong, em, blockquote)
* Element anatomy (opening tag, closing tag, attributes)
* Navigation with links
* Lists (ordered + unordered)
* Adding images
* Audio and video elements
* Tables
* Semantic tags
* Div and span
* Forms
* Accessibility (this is *very* meaningful for real users)

### Small Example

Inline code: `<p>Hello!</p>`

Code block:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Practice Page</title>
  </head>
  <body>
    <h1>Learning HTML</h1>
    <p>I am still improving, but writing code helps me learn faster.</p>
  </body>
</html>
```

---

## CSS – Making Things Look Better

CSS is the part that makes the page look nice (or sometimes bad if I make mistakes!). I often need to test different values to see how layouts change.

### Main CSS Ideas I’m Learning

1. Basic syntax and units (px, %, rem)
2. Selectors and combinators
3. Cascade and specificity (this part is tricky for me)
4. Box model
5. Display types
6. Positioning
7. Flexbox (***very useful*** for layouts)

### What CSS Helps Me With

* Spacing between items
* Colors and backgrounds
* Making elements align
* Creating simple layouts

### My Steps When Adding CSS

1. Make a CSS file
2. Link it in HTML
3. Write some rules
4. Refresh and check the page

---

## Responsive Design – For All Screen Sizes

Responsive design makes the page look good on desktop and mobile. I use media queries when the layout needs to change.

```css
@media (max-width: 600px) {
  body {
    padding: 10px;
  }
}
```

---

## Helpful Website

I often use MDN when I forget something:
[https://developer.mozilla.org/](https://developer.mozilla.org/)

---

## Quick Comparison Table

| Topic | What It Helps With     |
| ----- | ---------------------- |
| HTML  | Page structure         |
| CSS   | Visual design & layout |
