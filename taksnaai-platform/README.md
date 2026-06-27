# 🧠 Case Study : TaksnaAI – AI-Powered Student & Employee Assessment Platform


⚠️ Disclaimer: This case study is based on my frontend engineering contributions while working at EventBeep. Due to company confidentiality and intellectual property policies, the production source code cannot be shared publicly. This document highlights my technical contributions, engineering decisions, and frontend implementation experience.

## 📌 Project Overview

**TaksnaAI** is an AI-powered assessment platform designed to streamline the process of assigning, managing, and evaluating technical assessments for students and employees. The platform enables administrators to create customized assessment projects, assign them to candidates, and monitor completion, while providing candidates with an intuitive, AI-assisted test-taking experience.

I contributed to this project during my time at **ByteFlyte Technologies** as a project-based Full Stack Frontend Developer, where I was responsible for building responsive user interfaces, implementing assessment workflows, and creating a seamless experience for both administrators and candidates.

---

## 🚀 Tech Stack

* **Next.js**
* **TypeScript**
* **Chakra UI**
* **REST APIs**
* **Excel File Upload & Parsing**
* **AI Voice Integration**

---

# 👨‍💼 Admin Panel

## 🔐 Authentication

Developed a secure authentication flow for administrators, allowing authorized users to manage assessment projects efficiently.

### Features

* Secure Sign In
* Session-based authentication
* Role-based access

---

## 📊 Dashboard

Designed a responsive dashboard that provides administrators with a complete overview of all assessment projects.

### Features

* View all created assessment projects
* Project cards with current status
* Quick management actions
* Responsive UI for desktop and tablet devices

Each project card includes actions such as:

* ✏️ Edit Project
* 🟢 Activate / Deactivate
* ✅ View Completed Assignments
* 🗑️ Delete Project

---

## 📝 Project Creation Workflow

Built a dynamic project creation system allowing administrators to create customized assessments without developer involvement.

### Assessment Configuration

Administrators can:

* Create new assessment projects
* Organize projects by category
* Add multiple assessment questions
* Configure different question types

Supported question types include:

* Single Choice
* Multiple Choice
* Text Response
* File Upload

This flexible system enables assessments to be tailored for different recruitment and academic scenarios.

---

## 👥 Candidate Assignment Module

Implemented a complete assignment workflow that allows administrators to invite students or employees to participate in assessments.

### Candidate Management

Administrators can:

* Add candidates manually
* Upload candidate lists using Excel files
* Automatically process uploaded data
* View uploaded candidates in a hierarchical structure
* Assign assessments to selected candidates

Once assigned, candidates automatically receive login credentials via email.

---

# 🎓 Student / Employee Assessment Portal

## 🔐 Candidate Login

Created a dedicated login experience for students and employees after receiving their credentials via email.

After authentication, candidates are redirected to their personalized dashboard.

---

## 📋 Dashboard

Candidates can:

* View assigned assessment projects
* Track assessment status
* Start pending assessments
* Review completed assessments

Each project card displays its current status and includes a **Start** action when available.

---

## ⏱️ Assessment Experience

Developed an interactive assessment interface focused on simplicity and accessibility.

### Features

* Instruction page before assessment begins
* Assessment duration and timing details
* One question displayed per page
* Clean and distraction-free interface
* Progressive navigation through questions

To ensure data integrity, the **Next** button becomes available only after a valid response has been provided.

---

## 🎙️ AI Voice Assistance

Integrated AI-powered voice narration for assessment questions to improve accessibility and enhance the overall candidate experience.

Benefits include:

* Better accessibility
* Improved comprehension
* Enhanced engagement
* Support for multiple learning styles

---

## ✅ Assessment Completion

Upon completing all questions, candidates are automatically redirected back to their dashboard.

The assigned project status is updated to **Completed**, allowing candidates and administrators to track assessment progress in real time.

---

# 💡 Key Contributions

* Developed responsive Admin and Candidate portals using **Next.js** and **Chakra UI**
* Built complete assessment creation workflows with dynamic question management
* Implemented project lifecycle management (Create, Edit, Activate, Delete)
* Developed Excel-based bulk candidate upload functionality
* Built hierarchical candidate management interfaces
* Created assignment workflows for students and employees
* Designed an AI-assisted assessment interface with voice-enabled questions
* Implemented step-by-step assessment navigation with validation
* Developed project status tracking and completion workflows
* Collaborated with backend developers to integrate REST APIs and ensure seamless data synchronization

---

# 📚 What I Learned

Working on **TaksnaAI** strengthened my experience in building large-scale enterprise dashboards and workflow-driven applications. I gained hands-on expertise in designing dynamic form builders, implementing bulk data upload processes, integrating AI-assisted features, and creating user-friendly assessment experiences that balance functionality with usability. This project also enhanced my ability to collaborate in a client-focused development environment while delivering scalable and maintainable frontend solutions.
