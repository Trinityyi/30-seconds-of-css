---
title: Zebra striped list
tags: visual
expertise: beginner
cover: blog_images/forest-balcony.jpg
firstSeen: 2018-10-31T08:19:06+02:00
lastUpdated: 2020-12-30T15:37:37+02:00
---

Creates a striped list with alternating background colors.

- Use the `:nth-child(odd)` or `:nth-child(even)` pseudo-class selectors to apply a different `background-color` to elements that match based on their position in a group of siblings.
- **Note:** You can use it to apply different styles to other HTML elements like `<div>`, `<tr>`, `<p>`, `<ol>`, etc.

```html
<ul>
  <li>Item 01</li>
  <li>Item 02</li>
  <li>Item 03</li>
  <li>Item 04</li>
  <li>Item 05</li>
</ul>
```

```css
li:nth-child(odd) {
  background-color: #999;
}
```
