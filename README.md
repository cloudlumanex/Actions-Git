Emman learnng CICD with github action

# Actions-Git

![Owner](https://avatars.githubusercontent.com/u/0) <!-- Replace with actual avatar link if needed -->

## Overview

**Actions-Git** is a simple web application demonstrating a complete **CI/CD deployment pipeline using GitHub Actions**. This project showcases the deployment of a web app to an EC2 instance (or similar environment) with automated testing, packaging, and deployment.

---

## Features

- Simple static and dynamic web app
  - `index.html` – A static web page announcing the deployment.
  - `app.py` – A minimal Python Flask app (optional).
  - `server.js` – A simple Node.js Express server with a greeting endpoint.
- CI/CD automation
  - `.github/workflows` – GitHub Actions workflow that automates deployment.
  - Automatic Apache installation and setup.
  - Git repository cloning and deployment to web root.
- Package management
  - `package.json` – Node.js dependencies initialized for the Express app.

---

## Recent Updates

- Corrected heading from **'sly'** to **'sky'** in `index.html` and other references.
- Updated deployment script for Apache installation in workflow.
- Initialized `package.json` and Express server for Node.js testing.

---

## Usage

### Clone Repository
```bash
git clone https://github.com/cloudlumanex/Actions-Git.git
cd Actions-Git
