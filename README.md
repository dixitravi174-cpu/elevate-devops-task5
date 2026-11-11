# Elevate Labs DevOps Internship - Task 5 (Static Website Hosting)

## 📌 Project Overview
This project demonstrates hosting a static website using **GitHub Pages**. The repository contains static HTML and CSS files deployed automatically via GitHub Pages deployment pipeline.

- **Live Website URL:** https://dixitravi174-cpu.github.io/elevate-devops-task5/
- **GitHub Repository:** https://github.com/dixitravi174-cpu/elevate-devops-task5

---

## 🛠️ Tools & Technologies Used
- **Version Control:** Git & GitHub
- **Hosting Platform:** GitHub Pages
- **Frontend:** HTML5, CSS3

---

## ⚙️ Deployment Steps Followed
1. Created `index.html` structure and `style.css` for customized styling.
2. Committed files to the `main` branch of the repository.
3. Navigated to **Settings** → **Pages**.
4. Configured source to `Deploy from a branch`, selecting `main` branch and `/ (root)` directory.
5. Successfully verified deployment at the live GitHub Pages URL.

---

## 📋 Interview Questions & Answers

### 1. What is GitHub Pages?
GitHub Pages is a static site hosting service provided directly by GitHub that takes HTML, CSS, and JavaScript files straight from a repository and publishes a live website.

### 2. Can you host dynamic apps here?
No, GitHub Pages only supports static content (client-side HTML, CSS, JS). Backend languages (like Node.js, Python, PHP) and databases cannot run directly on GitHub Pages.

### 3. What are the limits of GitHub Pages?
- Source repositories have a recommended limit of 1 GB.
- Published sites cannot exceed 1 GB in size.
- Monthly bandwidth limit is 100 GB.
- Build timeout is 10 minutes, with a soft limit of 10 builds per hour.

### 4. How do you update the website?
Any change pushed/committed to the selected publishing branch (`main`) automatically triggers a rebuild and redeployment workflow via GitHub Actions.

### 5. What happens when you delete the repo?
Deleting the repository permanently unpublishes the hosted site, causing the URL to return a **404 Not Found** error.

### 6. What is the default file that loads?
The default entry file served by GitHub Pages in the root directory is `index.html`.

### 7. Can you use a custom domain?
Yes, GitHub Pages allows adding a custom domain in repository settings by configuring appropriate CNAME or A records with your DNS provider.

---

## 📸 Proof of Deployment

### 1. GitHub Pages Configuration
![GitHub Pages Deployment](ss1-github-pages-deployment.png.png)

### 2. Live Website
![Live Website](ss2-live-website.png.png)
