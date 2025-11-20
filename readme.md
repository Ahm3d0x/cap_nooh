# 🏋️‍♂️ CAP.NOOH Health & Fitness Calculator

A comprehensive **Single Page Application (SPA)** built for **Captain Ahmed Mohamed Attia (CAP.NOOH)**.  
This tool provides precise metabolic and nutritional calculations for multiple user categories — from professional athletes to patients with specific medical conditions.

---

## 📋 Table of Contents
- [Features](#-features)
- [Calculators Included](#-calculators-included)
- [Technical Stack](#-technical-stack)
- [Installation & Usage](#-installation--usage)
- [Project Structure](#-project-structure)
- [Credits](#-credits)

---

## ✨ Features

### ✔ Single File Architecture  
All logic (HTML, CSS, JS) is bundled in one portable file, fully operational offline.

### ✔ Responsive Design  
Optimized for Mobile, Tablet, and Desktop.

### ✔ Light/Dark Mode  
Includes a theme switcher with **LocalStorage** persistence.

### ✔ Custom Modals  
Beautiful, professional alert dialogs instead of browser defaults.

### ✔ Full Arabic Interface  
Right-to-Left (RTL) layout with the **Cairo** font for clean UI consistency.

---

## 🧮 Calculators Included

### 1️⃣ Bodybuilders Calculator  
- Uses **Mifflin-St Jeor** equation customized for athletes.  
- **Inputs:** Gender, Weight, Height, Age, Activity Level.  
- **Outputs:** BMR, TDEE, and high-performance macro split.

---

### 2️⃣ Normal People Calculator  
- Custom linear equations for the general population.  
- Unique coefficients for weight, height, and age.  
- Provides total maintenance calories + balanced macros.

---

### 3️⃣ WHO (World Health Organization) Calculator  
- Implements official WHO energy requirement equations by age ranges:  
  - 3–9, 10–17, 18–29, 30–60, 60+  
- **Special Medical Adjustments:**  
  - Diabetes: `+300 kcal`  
  - Heart Disease / Hypertension: `-250 kcal`  
  - Thyroid (Hypo/Hyper) adjustments  
  - Pregnancy & Lactation  
  - Renal & Liver Disorders  
  - + more clinical cases

---

### 4️⃣ High-Performance Athletes  
- Designed for elite athletes (sprinting, jumping, track & field).  
- Includes **Sleep Factor** to determine daily "Active Term".  
- Activity Coefficients: `0.79`, `1.1`, `2.79`.

---

### 5️⃣ BMI Calculator  
- Standard Body Mass Index formula.  
- Includes color-coded status (Healthy, Overweight, Obese…).

---

## 🛠 Technical Stack

### **HTML5**
- Clean semantic layout  
- Single-file organization  

### **CSS3**
- CSS Variables for dynamic theming  
- Grid & Flexbox layouts  
- Blur overlays for modals  
- Pure CSS (no frameworks)

### **JavaScript (ES6+)**
- SPA Navigation (show/hide sections)  
- All formula logic for 5 calculator categories  
- Theme persistence using LocalStorage  

---

## 🚀 Installation & Usage

1. **Download** `CAP_NOOH_Calculator.html`
2. **Open** the file in any modern browser (Chrome, Edge, Firefox, Safari)
3. Works **offline** once fonts/icons load the first time  
4. **No server or database required** — 100% client-side

---
## 📂 Project Structure

Although delivered as a single HTML file, the internal structure is modular:
```
CAP_NOOH_Calculator.html
│
├── <head>
│ ├── Google Fonts (Cairo)
│ ├── FontAwesome Icons
│ └── <style> (Theme variables, layouts, animations)
│
├── <body>
│ ├── <header> (Logo, Navigation Menu, Theme Toggle)
│ ├── <main>
│ │ ├── Bodybuilders Section
│ │ ├── Normal People Section
│ │ ├── WHO Calculator Section
│ │ ├── High-Performance Athletes Section
│ │ └── BMI Section
│ │
│ ├── <footer>
│ ├── Custom Modal Alert Box
│ │
│ └── <script>
│ ├── Navigation Logic
│ ├── Calculator Functions
│ └── UI Interaction (Modals, Theme)
```
---

## 👤 Credits

**Developer:** Ahmed Mohamed Attia  
**LinkedIn:** https://www.linkedin.com/in/ahmed-mohamed-attia-757aa6292/  
**Project Name:** CAP.NOOH Calculator  
**Year:** 2025  

This project was created following the detailed requirements provided in the official specification document.

---

