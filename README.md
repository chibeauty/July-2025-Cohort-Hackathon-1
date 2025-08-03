# Gloria Ngwu - Personal Portfolio Website

Welcome to the source code of my personal portfolio website! This site serves as a digital introduction to who I am as a developer—highlighting my background, technical skills, and projects.

---

## 🌟 About the Project

This responsive, accessible, and modern portfolio site was created using:

- **HTML5** for structured content
- **CSS3** (inline) for styling and layout
- Smooth scrolling, hover interactions, and a sticky header
- Sections include: About Me, Skills, Education, Interests, Projects, and Contact Form

---

## 🎯 Purpose

- Showcase my journey from chemical engineering to front-end development
- Display my technical skills and academic background
- Provide an easy way for recruiters or collaborators to contact me

---



## 📸 Screenshots

Added screenshots of my site here:

![Home Page Screenshot](./project3.jpg)

### 📋 Project Management Board & Issues

Below is a screenshot of my active GitHub Project board, which tracks features, bugs, and progress. Issues are linked to cards for transparency and collaboration.

![Project Board Screenshot](./project-board-screenshot.png)

> You can view the live board and issues at: [GitHub Project Board](https://github.com/chibeauty/July-2025-Cohort-Hackathon-1/projects) and [Issues](https://github.com/chibeauty/July-2025-Cohort-Hackathon-1/issues)

## 🌐 Live Demo

[View the live site on GitHub Pages](https://chibeauty.github.io/July-2025-Cohort-Hackathon-1/)

---

## 🧠 Features

- Fully responsive layout (mobile-first)
- Sticky navigation bar with smooth section scrolling
- Projects grid with live previews
- Accessible and semantic HTML structure
- Downloadable CV
- Contact form for easy communication
- **Light/Dark mode toggle** for user preference
- **Subtle fade-in animations** for modern feel

---

## 🛠️ Development Process & Project Management

This project follows a simple, transparent workflow using GitHub's built-in tools:

### 1. GitHub Project Board
- Go to your repository on GitHub.
- Click on the "Projects" tab and create a new board (e.g., "Portfolio Development").
- Add columns like "To Do", "In Progress", and "Done".
- Create cards for each feature, bug, or improvement.

### 2. Issues
- Use GitHub Issues to track bugs, feature requests, and tasks.
- Link issues to Project board cards for better tracking.

### 3. Workflow Documentation
Each new feature starts as an Issue, is added to the Project board, and is closed via Pull Request."

---

---

## 🚀 How to Use

1. **Clone the Repository**

```bash
git clone https://github.com/chibeauty/portfolio-site.git
Navigate into the Project

cd portfolio-site
Open with Live Server or Your Browser

# If using VS Code
Open with Live Server extension

# Or just open index.html directly
📁 Folder Structure (Expected)

/portfolio-site
│
├── images/
│   ├── profile.jpg
│   ├── About-me-picture.jpg
│   ├── project1.jpg
│   ├── project2.jpg
│   └── interest*.jpg
│
├── Gloria-Ngwu-CV.pdf
└── index.html
✍️ Author
Gloria Chidima Ngwu
Frontend Developer | Software Engineering Student
📧 gloriangwu45@gmail.com
🔗 LinkedIn
🐙 GitHub

📜 License
This project is licensed under the MIT License - feel free to use and customize it for your own portfolio.


---

## 🧾 Code Commenting Guidelines

You already wrote clean HTML and CSS. Here’s how to add meaningful comments:

### HTML

Add comments to indicate the purpose of each section:

```html
<!-- ===== HEADER WITH NAVIGATION ===== -->
<header role="banner">
    ...
</header>

<!-- ===== HERO SECTION: Introduction ===== -->
<section class="hero" aria-labelledby="hero-heading">
    ...
</section>

<!-- ===== ABOUT SECTION ===== -->
<section id="about" aria-labelledby="about-heading">
    ...
</section>
CSS
Use comment headers to break down styles into logical sections:

/* -------------------------
   GLOBAL RESET & BASE STYLES
---------------------------- */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* -------------------------
   HEADER STYLES
---------------------------- */
header {
  background: #2563eb;
  ...
}

/* -------------------------
   HERO SECTION STYLES
---------------------------- */
.hero {
  background: linear-gradient(...);
  ...
}
