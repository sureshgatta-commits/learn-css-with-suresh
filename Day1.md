
```markdown
📅 Date: 29 September 2025

## 🎨 Day 1 – Introduction to CSS

CSS stands for **Cascading Style Sheets**.  
It’s used to apply styles and control the layout, alignment, and visual appearance of HTML elements.

Think of HTML as the structure, and CSS as the paint, polish, and positioning.

---

### ✅ Why CSS?

- To make websites look professional and visually appealing  
- To control spacing, colors, fonts, and alignment  
- To separate content (HTML) from design (CSS)  
- To reuse styles across multiple pages

---

## 🧠 How to Apply CSS – 3 Real-Time Methods

---

### 1️⃣ External CSS – Linking a Separate File

This is the most scalable and recommended method for real-world projects.

**📁 File Structure:**
```
index.html  
style.css
```

**🔗 index.html**
```html
<!DOCTYPE html>
<html>
<head>
  <title>Day 1 – External CSS</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Welcome to CSS</h1>
  <p>This paragraph is styled using external CSS.</p>
</body>
</html>
```

**🎨 style.css**
```css
h1 {
  color: teal;
  text-align: center;
  font-family: Verdana, sans-serif;
}

p {
  font-size: 18px;
  color: darkgray;
  line-height: 1.6;
}
```

**💬 Real-Time Tip:**  
Make sure your `style.css` is in the same folder as your HTML file, or adjust the path accordingly.

---

### 2️⃣ Inline CSS – Styling Inside the Tag

Quick and direct, but not ideal for maintainability.

```html
<h2 style="color: crimson; text-align: right; font-size: 24px;">
  This heading uses inline CSS
</h2>
```

**💬 Real-Time Tip:**  
Use inline CSS only for small tweaks or testing. Avoid it in large projects.

---

### 3️⃣ Internal CSS – Using the `<style>` Tag in `<head>`

Useful for single-page demos or quick prototypes.

```html
<!DOCTYPE html>
<html>
<head>
  <title>Day 1 – Internal CSS</title>
  <style>
    h3 {
      color: navy;
      font-family: Arial, sans-serif;
      text-align: left;
    }

    p {
      text-align: justify;
      font-size: 16px;
      color: #555;
    }
  </style>
</head>
<body>
  <h3>Internal CSS Example</h3>
  <p>This paragraph is styled using internal CSS. It’s great for quick demos and testing styles directly in the HTML file.</p>
</body>
</html>
```

**💬 Real-Time Tip:**  
Internal CSS is good for small projects, but external CSS is better for organization and reuse.

---

## 🧪 Quick Challenge

Try styling this button using all three methods:

```html
<button>Click Me</button>
```

Can you make it blue with white text and some padding?

---

## 🏁 Summary

| Method       | Use Case                        | Pros                          | Cons                          |
|--------------|----------------------------------|-------------------------------|-------------------------------|
| External     | Real projects, reusable styles   | Clean, scalable, organized    | Requires separate file        |
| Inline       | Quick fixes, testing             | Fast, direct                  | Messy, hard to maintain       |
| Internal     | Demos, small pages               | Easy to test styles           | Not reusable across pages     |

---

Let’s keep styling and make the web beautiful—one tag at a time!
```
