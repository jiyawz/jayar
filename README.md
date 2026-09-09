# Jay-ar M. Calalo — Personal Portfolio

> **Thoughtful digital experiences that feel simple, useful, and human.**  
> A personal portfolio showcasing frontend development, UI/UX design, and systems engineering projects.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Design-Editorial](https://img.shields.io/badge/Style-Editorial%20%2F%20Retro%20Usability-71806B?style=flat-square)](#design-philosophy--aesthetics)
[![License: MIT](https://img.shields.io/badge/License-MIT-292A26?style=flat-square)](LICENSE)

---

## 📖 Overview

This repository contains the personal portfolio website of **Jay-ar M. Calalo**, a 4th-year **Bachelor of Science in Information Technology (BSIT)** student at the **University of Mindanao** based in Davao City, Philippines.

The site is built with a focus on **lightweight performance**, **accessible semantic HTML**, and a distinct **editorial design system** combining retro tactile textures with modern web typography and fluid layouts.

---

## ✨ Key Features

- **Editorial & Tactile Aesthetics**: Styled with a warm paper palette, delicate noise texture, subtle drop shadows, and refined serif/monospace typography.
- **Pure Vanilla Stack**: Zero framework dependencies or build steps—fast load times, fully responsive, and easy to maintain.
- **Interactive Navigation**: Smooth scrolling with mobile-responsive hamburger navigation and active state transitions.
- **Curated Project Showcase**: Dynamic feature articles highlighting vertical slice game dev and collaborative capstone builds with direct repository links.
- **Design Process & Toolkit**: Visual breakdown of Jay-ar's design approach (`Understand → Explore → Design → Test → Refine`) and tech competencies.
- **Interactive Contact Card**: Built-in contact form interface ready for direct connection to form endpoints (Formspree, EmailJS, etc.).

---

## 🎨 Design Philosophy & Aesthetics

The portfolio bridges vintage publication print design with modern responsive web usability:

| Token | Hex / Value | Usage |
| :--- | :--- | :--- |
| **Cream Paper** | `#F4F0E6` | Primary page background |
| **Parchment Accent**| `#EAE4D6` | Section contrast & frame backdrops |
| **Charcoal / Ink** | `#292A26` | Primary headings, dark accents, statement banners |
| **Sage Green** | `#71806B` | Primary button, brand marks, and subtle accents |
| **Terracotta** | `#B66F58` | Alert highlights, badge accents, subtext tags |
| **Butter Ochre** | `#D9C98C` | Hero visual elements, interactive highlights |
| **Typography** | `Fraunces`, `Inter`, `DM Mono` | Editorial display serifs, legible UI text, and monospace metadata |

---

## 🛠️ Tech Stack & Skills

### Built With (Portfolio):
- **Markup**: Semantic HTML5 (W3C standard, accessibility-first)
- **Styling**: Vanilla CSS3 (Custom design system, CSS Grid, Flexbox, media queries, SVG noise filter)
- **Scripting**: Vanilla JavaScript (ES6+ DOM manipulation)
- **Typography**: Google Fonts ([Fraunces](https://fonts.google.com/specimen/Fraunces), [Inter](https://fonts.google.com/specimen/Inter), [DM Mono](https://fonts.google.com/specimen/DM+Mono))

### Featured Skills & Core Stack:
- **Frontend**: ReactJS, Vanilla JavaScript, HTML5, CSS3
- **Backend & Systems**: C#, ASP.NET Core, Python, SQL Server, Luau / Rojo
- **Infrastructure & Security**: Computer Networking, Information Security, Cybersecurity
- **UI/UX & Product Design**: UX Research, Interaction Design, Prototyping, Usability Testing, Design Systems

---

## 💼 Featured Projects

### 01. The Shattered Crown — Roblox RPG (Chapter 01)
- **Description**: A story-driven Roblox RPG vertical slice following a recruit of the Valdris Vanguard.
- **Highlights**: Server-authoritative combat, quest progression systems, equipment management, and comic-style dialogue.
- **Stack**: `Luau` · `Rojo` · `Roblox Studio`
- **Repository**: [github.com/arvnddl18/RPGgamerblx](https://github.com/arvnddl18/RPGgamerblx)

### 02. FoodieSaur — Personalized Food Recommendation Assistant (Capstone)
- **Description**: A smart, location-based food assistant combining conversational AI with mapping and dietary constraint filtering.
- **Highlights**: Team-built capstone featuring natural language processing, interactive maps, dietary preferences, and curated restaurant recommendations.
- **Stack**: `ASP.NET Core` · `C#` · `SQL Server` · `Dialogflow` · `Google Maps API`
- **Repository**: [github.com/arvnddl18/PersonalizedFoodRecommendation](https://github.com/arvnddl18/PersonalizedFoodRecommendation)

---

## 📂 Project Structure

```text
jayar/
├── images/
│   └── foodiesaurimage.png   # Screenshot preview for FoodieSaur project
├── index.html                # Main portfolio landing page & structure
├── style.css                 # Custom CSS design system, typography & animations
└── README.md                 # Project documentation and setup guide
```

---

## 🚀 Quick Start / Local Development

Since this portfolio is built with pure HTML, CSS, and JavaScript, you do not need to install any `npm` dependencies or run a build step.

### Option 1: Double-click / Open in Browser
Simply double-click [`index.html`](index.html) or open it directly in any modern web browser (Chrome, Firefox, Safari, Edge).

### Option 2: Live Server (VS Code)
1. Open the project folder in **Visual Studio Code**.
2. Install the **Live Server** extension by *Ritwick Dey*.
3. Right-click [`index.html`](index.html) and select **"Open with Live Server"**.

### Option 3: Python Local HTTP Server
Run the following in your terminal inside the project root directory:

```bash
# Python 3
python -m http.server 3000
```
Then visit `http://localhost:3000` in your browser.

---

## 🌐 Deployment

You can host this static portfolio for free on various platforms:

### Deploy to GitHub Pages
1. Push this repository to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
2. In your repository on GitHub, go to **Settings** > **Pages**.
3. Under **Branch**, select `main` and root folder `/`, then click **Save**.
4. Your site will be live at `https://<your-username>.github.io/<your-repo-name>/`.

### Deploy to Vercel or Netlify
- **Netlify**: Drag and drop the `jayar` folder into [Netlify Drop](https://app.netlify.com/drop).
- **Vercel**: Import your GitHub repository into [Vercel](https://vercel.com) — no build command needed!

---

## 🔧 Customization Guide

### 1. Updating Profile Picture
In [`index.html`](index.html), find the `.portrait` container under the Hero section (around line 26). Replace the placeholder initial block with an `<img>` tag:
```html
<div class="portrait">
  <img src="images/your-profile.jpg" alt="Jay-ar M. Calalo" style="width: 100%; height: 100%; object-fit: cover;">
</div>
```

### 2. Connecting the Contact Form
To receive submissions directly to your email without a custom backend, you can connect [Formspree](https://formspree.io/):
```html
<form id="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
  <!-- Form fields -->
</form>
```

### 3. Adding Certification Links
Under `<section class="certificates">` (around line 40), replace the placeholder spans with direct verification URLs:
```html
<a class="text-link" href="https://your-cert-url.com" target="_blank" rel="noreferrer">
  Verify Credential <b>↗</b>
</a>
```

---

## 📬 Contact & Connect

- **Name**: Jay-ar M. Calalo
- **Education**: BSIT Student, University of Mindanao, Davao City, Philippines
- **GitHub**: [@arvnddl18](https://github.com/arvnddl18)
- **LinkedIn**: [Add your LinkedIn profile link here]
- **Email**: [Add your professional email here]

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — you are free to use it as inspiration for your own portfolio.
