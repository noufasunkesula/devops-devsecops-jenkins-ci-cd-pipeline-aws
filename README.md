## DevSecOps Jenkins CI/CD Pipeline on AWS
> Secure-by-Design CI/CD Framework with Real-Time Scanning & Cloud Deployment.

A production-grade DevSecOps pipeline engineered with Jenkins and Docker to enforce secure coding, automated testing, and container security across every stage of the SDLC. This framework integrates SonarQube, OWASP Dependency-Check, Trivy, and Docker to deliver continuous visibility, real-time threat detection, and automated containerized deployment to AWS EC2. Built for scalability, auditability, and alignment with modern enterprise security standards.

<p align="center">
  <img src="04-icons/05-jenkins.png" alt="Jenkins Logo" width="120" style="vertical-align: middle; margin-right: 40px;"/>
  <img src="04-icons/06-aws-logo.png" alt="AWS Logo" width="150" style="vertical-align: middle;"/>
</p>

<br/>

<p align="center">
  <!-- Jenkins -->
  <img src="https://img.shields.io/badge/Jenkins-CI/CD-FF6C37?logo=jenkins&logoColor=white&style=for-the-badge" />
  
  <!-- AWS -->
  <img src="https://img.shields.io/badge/AWS-Deployment-FF9900?logo=amazon-aws&logoColor=white&style=for-the-badge" />

  <!-- SonarQube -->
  <img src="https://img.shields.io/badge/SonarQube-Code%20Quality-4E9BCD?logo=sonarqube&logoColor=white&style=for-the-badge" />

  <!-- OWASP Dependency Check -->
  <img src="https://img.shields.io/badge/OWASP-Dependency%20Check-8A4182?logo=owasp&logoColor=white&style=for-the-badge" />

  <!-- Trivy -->
  <img src="https://img.shields.io/badge/Trivy-Container%20Scanner-0db7ed?style=for-the-badge" />

  <img src="https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker&logoColor=white&style=for-the-badge" />

</p>

## Tools Used
<p align="center"> <img src="04-icons/01a-docker.png" alt="Docker" title="Docker" width="90" style="margin: 0 15px;"> <img src="04-icons/02-trivy.png" alt="Trivy" title="Trivy" width="90" style="margin: 0 15px;"> <img src="04-icons/03-owasp.png" alt="OWASP Dependency Check" title="OWASP Dependency Check" width="90" style="margin: 0 15px;"> <img src="04-icons/04-sonarqube.png" alt="SonarQube" title="SonarQube" width="90" style="margin: 0 15px;"> <img src="04-icons/05-jenkins.png" alt="Jenkins" title="Jenkins" width="90" style="margin: 0 15px;"> <img src="04-icons/06-aws-logo.png" alt="AWS" title="AWS" width="110" style="margin: 0 15px;"> <img src="04-icons/07-ec2.png" alt="EC2" title="EC2" width="70" style="margin: 0 15px;"> </p>

## Architecture Diagram

<p align="center">
  <img src="01-architecture/devsecops-architecure.png" alt="DevSecOps Jenkins CI/CD Architecture Diagram" width="80%"/>
</p>

<p align="center"><i>Secure-by-Design DevSecOps CI/CD Workflow using Jenkins, SonarQube, Trivy & AWS</i></p>

## Phases

Step | Description
--- | ---
DevSecOps Integration | Integrated security into every stage of CI/CD with Jenkins, Docker, SonarQube, OWASP, and Trivy.
Set up Jenkins | Installed and configured Jenkins on an AWS EC2 instance.
Build with Docker | Containerized the application for consistent builds and deployment.
Integrated SonarQube | Set up code quality checks and static analysis during builds.
Added OWASP Dependency-Check | Automated open-source vulnerability scanning during the build phase.
Integrated Trivy | Performed container image vulnerability scans post-Docker build.
Deployed to AWS EC2 | Final deployment done via automated scripts to AWS infrastructure.

## Repo Layout
```
devsecops-ci-cd-pipeline-with-jenkins/
│
├── 01-architecture/
│   └── devsecops-architecture.png
│
├── 02-pipeline-script/
│   └── Jenkinsfile
│
├── 03-screenshots/
│   └── *.png
│
├── 04-icons/
│   └── *.png
```
## Visual Walkthrough

View the 03-screenshots/ folder for more details and visuals of the pipeline in action.

## Reach Out At!!

Noufa Sunkesula

Email ID: noufasunkesula@gmail.com

Contact: +91 8106859686
