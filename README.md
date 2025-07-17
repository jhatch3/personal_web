# 🌐 Personal Portfolio Website – Justin Hatch

This repository contains the source code for my personal website, created to showcase my background, coursework, skills, and projects. Built using HTML, CSS, and a bit of JavaScript, the site is fully static and designed to be hosted via GitHub Pages or any static web hosting platform.

---

## 📝 Table of Contents

- 🖥️ [Project Overview](#project-overview)
- 📂 [File Structure](#file-structure)
- ⚙️ [Installation & Usage](#installation--usage)
- 🎨 [Customization](#customization)
- 🛠️ [Technologies Used](#technologies-used)
- 🌐 [Deployment](#deployment)
- 🧠 [Learning Outcomes](#learning-outcomes)

---

## 🖥️ Project Overview

This multi-page static website includes:

- A **Home** page with a brief introduction and featured projects
- An **About Me** page highlighting my background and skills
- A **Projects** page with interactive project cards
- A **Class Work** page listing relevant coursework
- A **Contact** page with a working form powered by Formspree

The design is clean, responsive, and customizable, aimed at recruiters, collaborators, and tech professionals.

---

## 📂 File Structure

| File / Folder               | Description                                                  |
| --------------------------- | ------------------------------------------------------------ |
| `index.html`                | Home page with brief intro and navigation                    |
| `about_me.html`             | About Me page detailing education and skills                 |
| `projects.html`             | List of personal and academic projects with expandable cards |
| `class.html`                | Classwork/Coursework list relevant to CS and Data Science    |
| `contact.html`              | Contact form powered by Formspree + social links             |
| `styles.css`                | Centralized styling for the entire website                   |
| `picture.jpg`               | Profile picture used on About page                           |
| `icons8-github-150 (1).png` | GitHub icon used for external links                          |
| `README.md`                 | This README file                                             |

---

## ⚙️ Installation & Usage

To view or modify the website locally:

1. **Clone the Repository**

   ```bash
   git clone https://github.com/jhatch3/personal_web.git
   cd personal_web
   ```

2. **View the Site**

   - Option 1: Open `index.html` in your browser
   - Option 2: Use Python's HTTP server
     ```bash
     python3 -m http.server
     # Then visit http://localhost:8000
     ```

3. **Navigate the Site** Use the nav bar to move between pages: Home, About Me, Projects, Class Work, and Contact.

---

## 🎨 Customization

You can easily adapt this site to your needs:

- **Text & Content:** Edit `.html` files to update bio, skills, and project info.
- **Images:** Replace `picture.jpg` and icon files with your own assets.
- **Styling:** Modify `styles.css` to change fonts, colors, layout, and spacing.
- **Contact Form:** Update the `form` `action` in `contact.html` with your Formspree link.

---

## 🛠️ Technologies Used

- **HTML5** – Static structure for all pages
- **CSS3** – Styling and layout
- **Vanilla JavaScript** – Enables interactive project cards
- **Formspree** – Handles contact form submissions
- **Google Fonts (Roboto)** – Typography styling
- **Icons8** – Social icons (GitHub, LinkedIn)

---

## 🌐 Deployment

This site is ready for deployment via:

- **GitHub Pages**
- **Netlify**
- **Vercel**
- Any static file host

To deploy with GitHub Pages:

1. Push the repo to GitHub
2. Go to **Settings > Pages**
3. Set source to `main` and root directory
4. Visit `https://your-username.github.io/personal_web/`

---

## 🧠 Learning Outcomes

Through this project, I learned:

- How to design and deploy a static website from scratch
- Responsive layout techniques using HTML/CSS
- Implementing interactive elements with JavaScript
- Real-world use of GitHub for version control
- Using third-party services like Formspree for form handling
