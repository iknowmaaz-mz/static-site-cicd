# Static Website CI/CD Pipeline with GitHub Actions & GitHub Pages

## Project Overview

This project demonstrates a fully automated CI/CD pipeline for deploying a static website using **GitHub Actions** and **GitHub Pages**.

Every push to the `main` branch automatically triggers a workflow that:

- Checks out the repository
- Configures GitHub Pages
- Uploads the website as an artifact
- Deploys it to GitHub Pages

This eliminates manual deployment and ensures the live website is always up to date.

---

## Live Demo
https://iknowmaaz-mz.github.io/static-site-cicd/


---

## Tech Stack

- HTML5  
- CSS3  
- Git  
- GitHub Actions (CI/CD)  
- GitHub Pages (Hosting)

---

## Project Structure


---

## CI/CD Workflow Explanation

**Trigger:**  
Push to `main` branch

**Pipeline Steps:**

1. Checkout repository
2. Configure GitHub Pages
3. Upload build artifact
4. Deploy to GitHub Pages

Workflow file location:


---

## Setup Instructions

###  Create Repository

- Repository name: `static-site-cicd`
- Visibility: Public
- Initialize with README

---

###  Clone Repository

```bash
git clone https://github.com/<your-username>/static-site-cicd.git
cd static-site-cicd
