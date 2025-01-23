# Hacker Style Library - Documentation

Welcome to the **Hacker Style Library**! This CSS library is designed to give your web pages a retro hacker aesthetic with bright green text, black backgrounds, and glowing elements. Below is a detailed guide to using this library effectively.

---

## Getting Started

1. **Include the CSS File**
   
   To use the Hacker Style Library, link the CSS file to your HTML document:

   ```html
   <link rel="stylesheet" href="hacker.css">
   ```

2. **Set Up Your HTML Structure**

   Use semantic HTML tags for better results. The library provides styles for most common HTML elements like headings, paragraphs, buttons, tables, and forms.

---

## Available Styles

### 1. **Base Styling**
- **Body:**
  - Black background (`#000000`)
  - Bright green text (`#00ff00`)

### 2. **Typography**
- **Headings (`<h1>` to `<h6>`):** Text-shadow effect for a glowing look.
- **Paragraphs (`<p>`):** Line-height set for better readability.

### 3. **Links**
- Default color: Bright green (`#00ff00`).
- On hover: Slightly darker green with a glow effect.

Example:
```html
<a href="#">Hacker Link</a>
```

### 4. **Buttons**
- Use the `hacker-button` class for buttons.
- Hover: Inverts colors with a glow effect.
- Active: Slightly darker green background.

Example:
```html
<button class="hacker-button">Click Me</button>
```

### 5. **Forms**
- Inputs, textareas, and selects are styled with glowing borders and backgrounds.
- On focus: Glow intensifies with a slightly darker green.

Example:
```html
<input type="text" class="hacker-input" placeholder="Enter text">
```

### 6. **Tables**
- Tables have bright green borders and alternating row colors for better readability.
- Hovering over rows highlights them.

Example:
```html
<table>
    <thead>
        <tr>
            <th>Column 1</th>
            <th>Column 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
        </tr>
        <tr>
            <td>Data 3</td>
            <td>Data 4</td>
        </tr>
    </tbody>
</table>
```

### 7. **Code Blocks**
- For `<pre>` and `<code>` tags, glowing borders and padding are applied.

Example:
```html
<pre><code>// This is a code block
console.log("Hello, World!");
</code></pre>
```

### 8. **Utility Classes**

#### Cards
Use the `.hacker-card` class to create glowing containers.
```html
<div class="hacker-card">
    This is a hacker card.
</div>
```

#### Alerts
Use the `.hacker-alert` class for styled alerts. You can also use `.hacker-alert-warning` or `.hacker-alert-error` for different alert types.
```html
<div class="hacker-alert">Default Alert</div>
<div class="hacker-alert-warning">Warning Alert</div>
<div class="hacker-alert-error">Error Alert</div>
```

---

## Responsive Design

This library includes a media query for screens smaller than 768px:
- Reduces font sizes for better readability on smaller devices.

---

## Customization

Feel free to modify the values in the CSS file to suit your project. Common changes include:
- Adjusting colors (e.g., glow effects or text color).
- Tweaking animation durations for typing or blinking effects.

---

## License
This library is open-source and free to use. Attribution is appreciated but not required.

---

Enjoy creating your hacker-themed web pages!
