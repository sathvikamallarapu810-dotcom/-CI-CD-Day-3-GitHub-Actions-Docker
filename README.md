
🚀 CI/CD Day 3 — GitHub Actions + Docker

Today I integrated Docker into my GitHub Actions CI pipeline.

🔹 What I learned:
• GitHub Actions workflow automation
• Dockerfile creation
• Docker image building
• Integrating Docker into CI
• Automated Docker builds on every push

🔹 Pipeline:
Git Push
   ↓
GitHub
   ↓
GitHub Actions
   ↓
Checkout
   ↓
Build
   ↓
Test
   ↓
Docker Image Build
   ↓
✅ Pipeline Success

🔹 Dockerfile:
FROM nginx:1.27
COPY app.txt /usr/share/nginx/html/index.html
COPY app-build.txt /usr/share/nginx/html/app-build.txt

🔹 Local Docker Test:
Image: cicd-day3-app
Container: cicd-day3-container
Port: 8083

The application successfully ran through Docker, and the GitHub Actions workflow completed successfully.

Next: Docker Hub integration and automated image publishing.
<img width="956" height="567" alt="Screenshot 2026-10-01 204116" src="https://github.com/user-attachments/assets/dafd13c9-ba2e-4ddb-a53e-4e20d326cc0d" />
<img width="959" height="558" alt="Screenshot 2026-10-01 204122" src="https://github.com/user-attachments/assets/d3b63e8f-c599-461b-b8a0-064e5ab80019" />
<img width="959" height="563" alt="Screenshot 2026-10-01 204135" src="https://github.com/user-attachments/assets/d9005c2e-c90c-47da-a914-cbbaf2a4b47b" />




#CI/CD #GitHubActions #Docker #DevOps #CloudComputing #LearningInPublic
