# 🔵 Circular Text Animation

## 📌 Overview
This project is a **circular scrolling text animation** designed as a **portfolio showcase** for a creative agency. Each letter represents a **project** in the agency's portfolio, and as the user scrolls, the movement follows a **circular path** rather than a traditional vertical or horizontal scroll. The **viewport** (small window) allows users to view each letter/project **one at a time** as they scroll.

---

## ✨ Key Features
1. **Circular Layout**  
   - Letters are arranged in a **perfect circle**.  

2. **Virtual Scrolling**  
   - Scrolling moves along a **circular trajectory** instead of a linear direction.  

3. **Viewport**  
   - A **fixed small window** that acts as the **viewing frame**.  

4. **Interactive Animation**  
   - The letters **animate dynamically** in response to scrolling movements.  

---

## 🛠️ Technologies Used
- **HTML** for structuring elements.  
- **CSS** for styling and positioning.  
- **JavaScript** for implementing the circular scroll effect.  
- **VirtualScroll (via Skypack CDN)** for smooth scrolling interaction.  

---

## 🔄 How It Works

### 1️⃣ HTML Structure:
- `.main` contains the viewport and circle animation.  
- `.view` is the **small window** that acts as the viewport.  
- `.circle-mock` holds the **letters representing projects**.  

### 2️⃣ CSS Styling:
- `.circle-mock` ensures a **circular shape**.  
- `.item` positions each **letter dynamically** around the circle.  
- `.wrapper` moves based on **scroll input**.  

### 3️⃣ JavaScript Mechanics:
- Fetches all `.item` elements (**letters**).  
- Calculates positions **along the circle** based on **trigonometry**.  
- Listens for **scroll events** and updates the `.wrapper` transform accordingly.  

---

## 🚀 Installation & Usage
1. **Clone or download** the project.  
2. **Open `main.html`** in a browser.  
3. **Scroll up/down** to see the letters rotate in a circular motion.  

## 🔄 Demo Content
The animation visually represents text characters arranged in a circular motion. Users interact by scrolling, and the letters rotate around a central point.

## 🛠️ Dependencies
- VirtualScroll (v2.1.1) via Skypack CDN.

## 🚀 Customization
1. Modify `main.html` to change the letters (projects).
2. Adjust the **circle size** in `.circle-mock`.
3. Change the **scroll sensitivity** in JavaScript.

📌 **Author**: _Olha Tkachiv_  
