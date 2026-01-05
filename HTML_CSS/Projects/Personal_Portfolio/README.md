# Personal Portfolio Website 🌐

## 📌 Project Overview

This project is a **Personal Portfolio Website** built using **HTML and CSS** as part of the **freeCodeCamp Responsive Web Design Certification**.

The website demonstrates core web development concepts such as layout design, navigation, responsive design, and CSS positioning. It fulfills all required user stories and passes the freeCodeCamp automated tests.

---

## 🎯 Objectives

The objectives of this project are to:

- Build a single-page portfolio website
- Use semantic HTML elements
- Implement a fixed navigation bar
- Create a full-screen welcome section
- Display projects using reusable components
- Apply responsive design using media queries

---

## 🧱 Features

- **Fixed Navigation Bar**  
  The navigation bar remains at the top of the viewport while scrolling.

- **Full-Screen Welcome Section**  
  The welcome section uses `height: 100vh` to match the viewport height.

- **Projects Section**  
  Projects are displayed using elements with the `.project-tile` class.

- **External Profile Link**  
  Includes a link to a GitHub profile that opens in a new tab.

- **Responsive Design**  
  A media query ensures the layout adapts to smaller screens.

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  
- Responsive Web Design  

---
 
---

## 📱 Responsive Design

The project includes a media query that activates when the screen width is `768px` or less.  
This improves usability on tablets and mobile devices.

```css
@media (max-width: 768px) {
  body {
    background-color: lightblue;
  }
}


