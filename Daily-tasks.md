# Jenkins – Daily Tasks in Real-Time Projects (4+ Years DevOps Experience)

In my current DevOps role, Jenkins is a central tool for implementing CI/CD pipelines. Below are my **day-to-day Jenkins activities** as part of project delivery and automation processes:

---

## 🔧 1. Pipeline Monitoring and Troubleshooting

- Monitor Jenkins jobs and pipelines for build and deployment status.
- Troubleshoot failed builds by analyzing logs and recent commits.
- Coordinate with developers to resolve build issues (e.g., Maven, SonarQube, or deployment failures).

---

## ⚙️ 2. Managing CI/CD Jobs

- Create and maintain Jenkins jobs using both Freestyle and Pipeline (Scripted & Declarative).
- Implement `Jenkinsfile` in source code repositories.
- Manage multi-branch pipeline jobs to detect changes across branches.
- Convert old freestyle jobs to pipeline-based for better control and versioning.

---

## 🔄 3. Source Code Integration

- Integrate Jenkins with GitHub/GitLab.
- Configure triggers using **webhooks** or **Poll SCM** to start builds automatically on push events.

---

## ☁️ 4. Artifact Management with Nexus

- Integrate Jenkins with Nexus to upload Maven artifacts (`.jar`, `.war`).
- Implement version tagging and cleanup strategies for old artifacts.

---

## 🧪 5. Static Code Analysis (SonarQube)

- Integrate SonarQube with Jenkins for code quality checks.
- Run code scans using SonarQube Scanner plugin.
- Enforce quality gates and use JaCoCo for code coverage reports.

---

## 🚀 6. Application Deployment

- Deploy applications to Tomcat using:
  - **Deploy to Container Plugin**
  - **SSH Agent Plugin** for custom shell-based deployment
- Deploy to WebLogic/WebSphere where applicable.

---

## 🔌 7. Plugin and Jenkins Core Maintenance

- Regularly update Jenkins plugins and core packages.
- Perform safe restarts after upgrades.
- Monitor plugin compatibility and health.

---

## 📬 8. Email Notifications

- Configure Email Extension plugin for:
  - Build success/failure alerts
  - Team notifications
  - Custom messages with build details

---

## 🛡️ 9. Jenkins Security and Access Control

- Manage user accounts and roles using Role-Based Authorization Strategy plugin.
- Restrict access to jobs or folders.
- Secure Jenkins with custom port changes and basic HTTPS configuration.

---

## 💾 10. Backup and Recovery

- Schedule backups using ThinBackup plugin.
- Backup Jenkins home directory, job configs, and credentials.
- Restore jobs or migrate Jenkins to a new server if required.

---

## 📂 11. Jenkins Shared Libraries

- Use Shared Libraries to reuse pipeline functions across multiple projects.
- Store custom steps under `vars/` and load dynamically into pipelines.

---

## 🧰 12. Custom Utilities and Job Maintenance

- Configure build parameters and environment variables.
- Add timestamp to console output for better traceability.
- Discard old builds and clear workspace before builds to save disk space.
- Set custom build names using Build Name Setter plugin.

---

## 🛠️ 13. Safe Restart and System Tasks

- Perform Jenkins Safe Restart during maintenance hours.
- Clear old workspace logs and manage node/workspace availability.

---

## 📈 Summary Statement for Interview

> "My daily Jenkins tasks include managing and monitoring CI/CD pipelines, resolving build/deployment issues, integrating with tools like Maven, Nexus, SonarQube, and Tomcat, maintaining secure access control, handling Jenkins backups, and optimizing job configurations for stability and performance."

---
