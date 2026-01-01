# 🌆 City Skyline Project (HTML & CSS)

This project creates a **city skyline illustration** using **only HTML and CSS**.  
It demonstrates how complex visuals can be built with `div` elements, CSS variables, gradients, and Flexbox — **no JavaScript required**.


## 🛠 Technologies Used

- **HTML5** – Structure of the skyline
- **CSS3** – Styling and layout
  - CSS Variables (`:root`)
  - Flexbox
  - Linear & radial gradients
  - Media queries

---

## 🎯 Project Features

- Background and foreground building layers
- Multiple building designs using pure CSS
- Windows created with gradients and flex layouts
- Responsive color theme using media queries
- Automatic dark/monochrome mode on smaller screens

---

## 🧱 Project Structure Explanation

### HTML Structure

- `.background-buildings`
  - Represents buildings far from the viewer
  - Uses `bb` prefixed classes (bb1, bb2, bb3, etc.)

- `.foreground-buildings`
  - Represents buildings closer to the viewer
  - Uses `fb` prefixed classes (fb1, fb2, fb3, etc.)

- `.building-wrap`
  - Groups building sections vertically

- `.window-wrap`
  - Aligns windows evenly inside buildings

Each building is made from **nested `div` elements** styled entirely with CSS.

---

## 🎨 CSS Design Overview

### CSS Variables

All colors are controlled using variables:

```css
:root {
  --building-color1: #aa80ff;
  --building-color2: #66cc99;
  --building-color3: #cc6699;
  --building-color4: #538cc6;
  --window-color1: #bb99ff;
  --window-color2: #8cd9b3;
  --window-color3: #d98cb3;
  --window-color4: #8cb3d9;
}


