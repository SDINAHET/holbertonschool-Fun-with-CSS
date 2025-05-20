# holbertonschool-Fun-with-CSS

# 📘 Fun with CSS

![badge](https://img.shields.io/badge/Level-Amateur-red)
👨‍💻 By: Guillaume, CTO at Holberton School
🎯 **Weight:** 1
🧪 **Manual QA required** — *Request it when you're done with the project.*

---

## 📝 Description

In this project, you will experiment and implement **fun layout and interactions using only HTML and CSS**.

> ❌ No JavaScript allowed
> ✅ 100% CSS-based animations and styles

You will learn to:

* Use CSS sprites to optimize performance
* Create toggle switches with CSS only
* Animate underlines and transitions
* Build a responsive vertical icon menu using only checkboxes and `:checked` selectors

---

## 📁 Project Repository

**Repo name:** `holbertonschool-Fun-with-CSS`
Each task has its own file named accordingly.

---

## ✅ Tasks

### 0. Sprite Languages

* **File:** `0-styles.css`
* **HTML Provided:**

  ```html
  <ul>
    <li>HTML<span class="icon i-html"></span></li>
    <li>CSS<span class="icon i-css"></span></li>
    <li>JavaScript<span class="icon i-js"></span></li>
  </ul>
  ```
* **Image provided:** `0-sprite.png`

🔒 You are **not allowed** to modify the HTML or image file.
🧠 Goal: Use **background positioning** and **CSS sprites** to display the correct icons.

---

### 1. Move the (under)line

* **File:** `1-styles.css`
* **HTML Provided:**

  ```html
  <h2>
    Hello <a href="https://www.holbertonschool.com">Holberton!</a>
  </h2>
  ```

🎯 Goal: Create an animation where the **underline appears slowly** on hover.
No HTML modifications allowed.

---

### 2. Toggle

* **File:** `2-styles.css`
* **HTML Provided:**

  ```html
  <input type="checkbox" name="toggle" class="toggle-cb" id="toggle-0" checked>
  <label class="toggle-label" for="toggle-0">
    <div class="toggle-inner"></div>
    <div class="toggle-switch"></div>
  </label>
  ```

🎯 Goal: Build a **custom toggle switch** with the following features:

* Checked: Red background, text **"Yes"**, switch aligned right
* Unchecked: Grey background, text **"No"**, switch aligned left

---

### 3. Menu

* **File:** `3-styles.css`
* **HTML Provided:** Responsive circular menu button with Font Awesome icons

  ```html
  <nav class="menu">
    <input type="checkbox" class="menu-open" id="menu-open"/>
    <label class="menu-open-button" for="menu-open">...</label>
    <a href="#" class="menu-item"> <i class="fa fa-area-chart"></i> </a>
    ...
  </nav>
  ```

🎯 Goal: Create a **floating action menu** (FAB) using only CSS.
Icons must animate outward from the button when checked or hovered.

---

## 🧠 Tips

* Use `:checked` and `+` or `~` selectors for toggle and menu logic
* Apply `transform`, `opacity`, `transition` to create clean animations
* Don’t forget `position: absolute` and `z-index` tricks for layered elements

---

## 📌 Status

* [ ] 0\. Sprite languages - **0/14 pts**
* [ ] 1\. Move the (under)line - **0/8 pts**
* [ ] 2\. Toggle - **0/11 pts**
* [ ] 3\. Menu - **0/11 pts**

🔴 **Make sure to pass all tasks and request a manual QA review!**

---

## 🛠️ Author

Project starter by [Guillaume, CTO @ Holberton School](https://www.linkedin.com/in/guillaumegomez)

---
