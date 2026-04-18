# 👋 Welcome Tural SEYIDOV

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Tural%20Seyidov&fontSize=40&fontColor=ffffff&animation=fadeIn" />
  <source media="(prefers-color-scheme: light)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:56ccf2,100:2f80ed&height=200&section=header&text=Tural%20Seyidov&fontSize=40&fontColor=ffffff&animation=fadeIn" />
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&section=header&text=Tural%20Seyidov&fontSize=40" />
</picture>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=700&lines=Test+Automation+Engineer;SDET;QA+Tester;CI%2FCD+Enthusiast;Automation+Architect" />

</div>

---

## 🚀 About Me
Test Automation Engineer focused on building **scalable, maintainable, and CI-integrated automation frameworks**.

---

## 🛠️ Languages & Tools  

<div align="center">

<img src="https://skillicons.dev/icons?i=java,selenium,jenkins,git,github,maven,mysql,postman&theme=dark" />

<img src="https://img.shields.io/badge/TestNG-%23E33332.svg?style=for-the-badge&logo=testng&logoColor=white"/>
<img src="https://img.shields.io/badge/Cucumber-23D96C?style=for-the-badge&logo=cucumber&logoColor=white"/>
<img src="https://img.shields.io/badge/JIRA-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>

</div>

---

## 📊 Test Automation Dashboard

<div align="center">

<img src="https://img.shields.io/badge/Test%20Coverage-85%25-brightgreen?style=for-the-badge"/>
<img src="https://img.shields.io/badge/API%20Tests-Passing-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/UI%20Tests-Stable-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Build-Passing-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Parallel%20Execution-Enabled-orange?style=for-the-badge"/>

</div>

---

## 🧱 Test Automation Architecture

```mermaid
graph TD

A[TestNG Runner] --> B[Cucumber Features]
B --> C[Step Definitions]

C --> D[Page Object Model]
D --> E[Base Test]
E --> F[Driver Factory]
F --> G[WebDriver Manager]

G --> H[Local Browser]
G --> I[Selenium Grid]

E --> J[Config Reader]
E --> K[Utilities]
K --> L[Wait Utils]
K --> M[Driver Utils]
K --> N[Test Data Manager]

C --> O[API Testing Layer]
O --> P[Rest Assured]
P --> Q[Backend Services]

A --> R[Reporting]
R --> S[Extent Reports]
R --> T[Logs]

A --> U[CI/CD Pipeline]
U --> V[Jenkins]
V --> W[Maven Build]
W --> X[Test Execution]
X --> Y[Report Publish]

Z[GitHub Repo] --> V
