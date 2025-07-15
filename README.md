# 👟 Adidas Shoes Landing Page

This is a modern, responsive **Adidas landing page** built using only **HTML and CSS**.  
It features a clean layout, stylish animations, and adapts to all screen sizes.

---

## 🔥 Features

- Gradient background with dynamic red **clip-path** shape
- Responsive layout for desktop and mobile
- Navigation bar with hover effects
- Eye-catching product section with image and text
- Uses **Flexbox**, **media queries**, and **Google Fonts**

---

## 📱 Live Demo

👉 [Click here to view the project live](https://mohamed12511.github.io/HTML-AND-CSS-Templates-/)

---

## 🧠 What I Learned / Fixed

This project helped me understand responsive design and layout structure better.  
Here are some important mistakes I fixed during the process:

### 1. `height: 100vh` Problem
- ❌ Using `height: 100vh` on `<body>` caused content to be **cut off** on small screens.
- ✅ Fixed by using `min-height: 100vh` which allows the page to grow with content.

### 2. Fixed Height on Container
- ❌ `height: 80%` on `.container` prevented content from fitting inside.
- ✅ Removed it and used `padding` so layout is more flexible.

### 3. Image Overflow
- ❌ The image was too wide (`width: 400px`) and broke on small screens.
- ✅ Used `max-width: 100%` and resized it with media queries for all devices.

### 4. Background Circle (`clip-path`)
- ❌ Circle was in the wrong position and **covered the text** on mobile.
- ✅ Moved it to `bottom center` using a media query.

---

## 🛠️ Technologies

- HTML5  
- CSS3  
- Flexbox  
- Media Queries  
- Google Fonts  
- Clip-path  

---

## 📂 Folder Structure

