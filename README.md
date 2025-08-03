# July-2025-Cohort-Hackathon-1

## Project Overview
A personal portfolio web project showcasing interests, projects, and profile information.

## Features
- Responsive design
- Visually appealing layout
- Sections for profile, interests, and projects

## Getting Started
1. Clone the repository:
   ```
   git clone https://github.com/chibeauty/July-2025-Cohort-Hackathon-1.git
   ```
2. Open `index.html` in your browser.

## Deployment
This project can be deployed using GitHub Pages:
- Go to your repository on GitHub
- Click on Settings > Pages
- Set the source branch to `main` and folder to `/root`
- Save and access your site at `https://chibeauty.github.io/July-2025-Cohort-Hackathon-1/`

## Technology Stack
- HTML5
- CSS3 (responsive, modern design)

## Development Process
- Use branches for new features
- Open issues for bugs or enhancements
- Document progress in pull requests

## Credits
- Developed by chibeauty

## License
MIT License
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

## 🧠 Features

- Fully responsive layout (mobile-first)
- Sticky navigation bar with smooth section scrolling
- Projects grid with live previews
- Accessible and semantic HTML structure
- Downloadable CV
- Contact form for easy communication

---

## 🚀 How to Use

1. **Clone the Repository**

```bash
git clone https://github.com/chibeauty/portfolio-site.git
Navigate into the Project

bash
Copy
Edit
cd portfolio-site
Open with Live Server or Your Browser

bash
Copy
Edit
# If using VS Code
Open with Live Server extension

# Or just open index.html directly
📁 Folder Structure (Expected)
bash
Copy
Edit
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

php-template
Copy
Edit

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

css
Copy
Edit
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
