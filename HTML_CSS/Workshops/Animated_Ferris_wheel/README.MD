# 🎡 Ferris Wheel Animation (HTML & CSS)

This project is a simple animated **Ferris Wheel** built using **HTML** and **CSS only**.  
It demonstrates the use of **CSS positioning, transforms, and keyframe animations** to create a rotating wheel with cabins that remain upright while the wheel spins.

---

## 🛠 Technologies Used

- **HTML5** – Structure of the ferris wheel
- **CSS3** – Styling and animation
  - `position`
  - `transform`
  - `transform-origin`
  - `@keyframes`
  - `nth-of-type`

---

## 🎢 How It Works

### 1. Wheel Container
- The `.wheel` element is a circular container created using:
  - `border-radius: 50%`
  - Fixed aspect ratio using `vw` units
- The entire wheel rotates using a CSS animation.

```css
@keyframes wheel {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}


