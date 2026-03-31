# CI/CD Demo Application

[CI/CD Pipeline]
(https://github.com/awonriaz/cicd-demo-app/workflows/CI/CD%20Pipeline/badge.svg)

[Pull Request Validation]
(https://github.com/awonriaz/cicd-demo-app/workflows/Pull%20Request%20Validation/badge.svg)

This is a simple web application demonstrating CI/CD pipelines with GitHub Actions.

## Features
- Automated testing on every commit
- Automated deployment to GitHub Pages
- Pull request validation
- Simple web interface with interactive elements

## Live Demo
🚀 [View Live Application](https://awonriaz.github.io/cicd-demo-app)

## Local Development

1. Clone the repository
```bash
git clone https://github.com/awonriaz/cicd-demo-app.git
cd cicd-demo-app
Run tests
npm test
Start local server
npm start
Open http://localhost:8000 in your browser

CI/CD Pipeline

This project uses GitHub Actions for:

✅ Running automated tests
✅ Code quality validation
✅ Deploying to GitHub Pages on successful builds
✅ Pull request validation

Workflow Files

.github/workflows/ci-cd.yml - Main CI/CD pipeline
.github/workflows/pr-validation.yml - Pull request validation
.github/workflows/staging.yml - Staging deployment

Project Structure

cicd-demo-app/
├── src/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── tests/
│   └── test.js
├── .github/
│   └── workflows/
│       ├── ci-cd.yml
│       ├── pr-validation.yml
│       └── staging.yml
└── package.json
