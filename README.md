# 🌙 Nivedhitha K S — Minimal Dark Portfolio Website

A modern **4-page portfolio website** built with **HTML, CSS, and JavaScript**, designed in a **minimal dark theme** with smooth animations and responsive layout. This project transforms my resume into an interactive digital profile suitable for **personal branding, job applications, and online presence**.

---

## 🚀 Features

### ✅ Multi-Page Structure

| Page | Description |
|------|-------------|
| **Home / About** | Intro banner with typewriter subtitle, About Me section, Career Objectives |
| **Skills & Certifications** | Animated skill bars with hover effects, certification cards |
| **Education** | Vertical timeline-style layout with CGPA & percentage display |
| **Contact** | Social links (GitHub, Email, LinkedIn) + Contact form UI (EmailJS-ready) |

---

## 🎨 Design & Animations

- **Dark Minimal Theme** with muted indigo and soft pink accents  
- **Typewriter text animation** on the hero subtitle  
- **Scroll reveal animations** using Intersection Observer  
- **Skill bar fill animation** based on percentage  
- **Smooth scrolling & active nav highlighting**  
- **Hover effects** on buttons, certifications, and icons  
- **Floating ambient background blob** for subtle motion visuals  

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Structure & semantic layout |
| **CSS3** | Styling with variables, flex/grid, transitions |
| **JavaScript (Vanilla)** | Navigation control, animations, scroll effects |
| *(Optional)* EmailJS | Can be integrated for form submission |

---

## 📬 Contact Form Options

The contact form is currently in **demo mode**. You can activate real message delivery using:

### ✅ Option 1: EmailJS (Client-Side)

1. Create an account at **https://emailjs.com**
2. Create **Service**, **Template**, and **Public Key**
3. Replace the form submission handler in the JS section with:

```js
emailjs.send('SERVICE_ID', 'TEMPLATE_ID', {
  from_name: name,
  from_email: email,
  message: message,
});
