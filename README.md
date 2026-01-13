# Students&Companies (S&C) 🎓💼

> **A comprehensive System Design & Requirements Engineering project for a two-sided internship marketplace platform.**

![Status](https://img.shields.io/badge/Status-Completed-success)
![Type](https://img.shields.io/badge/Type-Individual_Project-blue)
![Focus](https://img.shields.io/badge/Focus-System_Design_&_Architecture-orange)

## 📂 Repository Structure
This repository follows the structure below:

* 📂 **[PDF Files](PDF%20Files/)**: **Start here.** Contains the compiled documentation and the presentation slide

    * 📄 [Presentation](PDF%20Files/Presentation.pdf): A brief visual overview of the system design and UI mock-ups *(Read the other files for a comprehensive explanation of each architectural choice)*

    * 📄 [R.A.S.D. v. 1.1](PDF%20Files/RASD_v.1.1.pdf): The complete Requirements Analysis and Specification Document (R.A.S.D.)

    * 📄 [D.D. v. 1](PDF%20Files/DD_v.1.pdf): The complete Design Document (D.D.)

* 📂 **[LaTeX Files](LaTeX%20Files/)**: The source code used for producing the related documentation *(Open the subfolders on your favourite LaTeX Editor to work on the code)*

    * 📂 [R.A.S.D.](LaTeX%20Files/R.A.S.D.): The Requirements Analysis and Specification Document (R.A.S.D.) source code

    * 📂 [D.D.](LaTeX%20Files/D.D.): The Design Document (D.D.) source code

* 📄 **[RASD and DD Assignement.pdf](RASD%20and%20DD%20Assignement.pdf)**: The project assignment

## 📖 About The Project

**Students&Companies** is a digital platform designed to streamline the complex matchmaking process between university students and companies offering internships.

This repository contains the complete **Software Engineering specification** for the system, moving from vague initial requirements to a mathematically verified model and a concrete architectural design.

During this process, the entire engineering lifecycle has been addressed:

1.  **Requirements Elicitation:** Transforming high-level stakeholder goals into concrete functional specifications

2.  **Formal Verification:** Using **Alloy** to mathematically prove the consistency of the data model and logic

3.  **System Architecture:** Designing a scalable **3-Tier Architecture** to handle high-concurrency usage.

## ⚡ Core Features Designed

This project focuses on the core matchmaking and management lifecycle:

* **For Companies:**
    * **Internship Management:** Creation and detailed specification of the internship proposals.
    
    * **Selection Pipeline:** Tools to manage applicants, including scheduling interviews and administering questionnaires

    * **Talent Scouting:** Capabilities to review student CVs and skills.

* **For Students:**

    * **Proactive Search:** Advanced filtering to find internships based on domain, wage and technology

    * **Application Tracking:** A dashboard to monitor the status of applications (i.e. Sent, Withdrawn, Rejected, Accepted)

    * **Feedback Loop:** Mechanisms to report complaints and monitor the resolution status during the internship

## 🏗️ Engineering Approach & Artifacts

This repository is organized to showcase the two major phases of the engineering process:<br>

### 1. Requirements Analysis & Specification Document (R.A.S.D.)
* **Goal:** Define *what* the system does before writing a single line of code.
* **Key Techniques:**

    * **Use Case Modeling:** Detailed breakdown of actor interactions (Student, Company)

    * **Formal Methods (Alloy):** Designing an Alloy model to simulate the system's state space, ensuring that "illegal" states (e.g. a student accepting two simultaneous internships) are mathematically impossible

    * **UML Modeling:** Sequence, Class and State diagrams to map out complex logic

### 2. Design Document (D.D.)
* **Goal:** Define *how* the system will be built.
* **Key Decisions:**

    * **Architecture:** **Three-Tier Architecture** (i.e. Presentation, Logic and Data) to ensure separation of concerns

    * **Pattern:** **Model-View-Controller (MVC)** to decouple the user interface from the business logic

    * **Integration:** Design of external APIs for AI-based recommendations and mail servers

---

<div align="center">

*This project was developed as part of the Software Engineering 2 Course (A.Y. 2024 - 2025) at Politecnico di Milano.*

</div>
