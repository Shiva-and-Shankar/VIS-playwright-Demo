# Buggy Multipage Demo Website

This project is a **deliberately buggy multipage website** created for testing UI automation tools like **Playwright MCP** and **GitHub Copilot**.  
It is designed to look like a modern e-commerce site (Amazon-inspired) but contains many **intentional bugs** across HTML, CSS, and JavaScript.

---

## 🎯 Purpose
The goal is to provide a **realistic but broken** website for practicing:
- UI Test Automation  
- Bug Detection  
- Regression Testing  
- CSS/JS Debugging  

---

## 📂 Project Structure
```
ui-buggy-multipage-site.zip
│── index.html      → Homepage with dropdowns, checkboxes, radios (some broken)
│── shop.html       → Shop page with product cards and layout issues
│── about.html      → About page with grammar mistakes and styling bugs
│── login.html      → Login form (username: vispwdemo | password: admin)
│── account.html    → User account page after login
│── style.css       → Contains intentional CSS mistakes and conflicts
│── script.js       → Contains buggy JavaScript behaviors
```

---

## 🔑 Login Details
- **Username:** `vispwdemo`  
- **Password:** `admin`  

If login is successful → redirects to **account.html**.

---

## 🐞 Injected Bugs & Issues

### 🔹 Navigation
- "Deals" navigation link does **not** work (broken intentionally).
- Some nav items misaligned.

### 🔹 Forms & Inputs
- 4 Dropdowns → 1 dropdown missing items / broken.  
- Checkboxes → One checkbox does **not** toggle.  
- Radio buttons misaligned.  
- Inconsistent form spacing.

### 🔹 CSS Issues
- Conflicting rules: same selector defined twice with different colors.  
- Unused selectors that apply to nothing.  
- Inconsistent padding/margin across cards/buttons.  
- Scrollbars buggy (one content area cannot scroll).  
- Dark blue + orange theme inconsistently applied (some stray colors).  
- Z-index issues: some cards hidden behind headers.  
- Font-size inconsistencies inside the same component.  
- Hover/active states missing on some buttons.

### 🔹 JavaScript Issues
- Checkbox event handler prevents toggle.  
- Some buttons do not respond on click.  
- Scroll handling inconsistent.

### 🔹 Content Issues
- Spelling & grammar mistakes across pages.  
- Placeholder text like "Shop prodcts heree" left intentionally.  
- Asymmetric alignment of text and cards.

---

## 🎨 Theme
- **Dark Blue + Orange** are the intended primary colors.  
- Some components ignore this theme due to CSS bugs.

---

## 🚀 How to Run
1. Download and unzip the project:  
   `ui-buggy-multipage-site.zip`
2. Open `index.html` in any modern browser.  
3. Explore the site and identify bugs.  

---

## 🧪 Suggested Testing Scenarios
- Automate login flow with Playwright.  
- Check that all dropdowns load correctly (expect 1 failure).  
- Validate checkbox/radio behavior (expect issues).  
- Verify navigation links (expect "Deals" broken).  
- Test CSS alignment, font, and hover states.  
- Confirm scrollbar functionality.  

---

## ⚠️ Disclaimer
This site is **intentionally broken** for educational/testing purposes only.  
It should **not** be used in production environments.

---
