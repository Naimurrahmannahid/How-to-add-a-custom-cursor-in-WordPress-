
# Custom Cursor with Kursor.js

This project integrates **Kursor.js**, a lightweight JavaScript library for adding custom cursors to websites.

## 🚀 Features
- Customizable cursor styles
- Lightweight and easy to implement
- Supports different cursor effects

## 📌 Installation

### 1️⃣ Add Kursor.js via CDN
Insert the following lines into your HTML file inside the `<head>` section:

```html
<!-- Kursor.js CSS -->
<link rel="stylesheet" href="https://unpkg.com/kursor/dist/kursor.css">

<!-- Kursor.js JavaScript -->
<script src="https://unpkg.com/kursor/dist/kursor.min.js"></script>
```

### 2️⃣ Initialize Kursor.js
Place this script before the closing `</body>` tag:

```html
<script>
  new kursor({
    type: 1,
    color: '#000000',
    removeDefaultCursor: false,
  });
</script>
```

## 🎨 Cursor Types
You can change the cursor effect by modifying the `type` value (1-5):

| Type | Effect |
|------|--------|
| `1`  | Basic cursor |
| `2`  | Bouncing cursor |
| `3`  | Blurred effect |
| `4`  | Growth cursor |
| `5`  | Ring cursor |

## ⚙️ Customization Options

| Option | Description | Default Value |
|--------|------------|--------------|
| `type` | Cursor effect type (1-5) | `1` |
| `color` | Cursor color (HEX) | `#000000` |
| `removeDefaultCursor` | Hide default browser cursor (`true` / `false`) | `false` |

## 📜 License
This project uses the **MIT License**.

---

**Enjoy your custom cursor! 🎉**  
If you find this useful, ⭐ **Star** this repository on GitHub!
