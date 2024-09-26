# CMPG 323 Overview - <39013219>

Welcome to the repository for **CMPG 323**. This repository contains the code and documentation for all the projects in the CMPG 323 module. Each project focuses on different aspects of software development, including Agile methodology, source control, design patterns, and automation.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Branching Strategy](#branching-strategy)
3. [GitIgnore and Security](#gitignore-and-security)
4. [Milestones and Projects](#milestones-and-projects)
5. [Links to Documentation](#links-to-documentation)
6. [Reference](#reference)

---

## 1. Introduction
This repository is designed to track the progress and submission of various projects for the CMPG 323 module. Throughout the module, five projects will be developed following the Agile and Scrum methodologies. Each project will focus on the following areas:
- Agile and Scrum principles
- Source Control using GitHub
- Application Programming Interfaces (APIs)
- Web Applications and Design Patterns
- Robotic Process Automation (RPA)
- Data Visualization and Reporting

The projects aim to build real-world industry skills and promote workplace readiness.

---

## 2. Branching Strategy

In this repository, the following branching strategy will be used to manage the development of the projects:

- **Main Branch**: The main branch will always hold the most stable and production-ready version of the code.
- **Develop Branch**: All development work will be done on this branch. New features and fixes will be integrated here first.
- **Feature Branches**: For each new feature or task, a new feature-specific branch will be created from the develop branch. Once the feature is complete, it will be merged back into the develop branch.
- **Hotfix Branches**: In case urgent fixes are needed in production, a hotfix branch will be created from the main branch, and once the fix is complete, it will be merged back into both main and develop branches.

Example workflow:


1. **Create a new feature branch**:
    ```bash
    git checkout -b feature/new-feature
    ```
2. **Work on the feature and commit changes**:
    ```bash
    git add .
    git commit -m "Add new feature"
    ```
3. **Merge feature branch into develop**:
    ```bash
    git checkout develop
    git merge feature/new-feature
    ```
4. **When all features are complete, merge develop into main for production**:
    ```bash
    git checkout main
    git merge develop
    ```
    
---

## 3. GitIgnore and Security

This repository includes a `.gitignore` file, which is used to exclude certain files and directories from being tracked by Git. Sensitive information and environment-specific files (such as credentials, API keys, and configuration files) will not be stored in this repository for security reasons.

The `.gitignore` file will typically exclude:
- **Environment variables**: `.env` files
- **Build files**: `/bin`, `/obj`
- **Log files**: `.log`, `.txt`
- **Temporary files**: `.tmp`, `.bak`

---

## 4. Milestones and Projects

The following milestones have been defined for the CMPG 323 projects:

- **Project 1 Submission**:  
  *Description*: Initial setup of GitHub repository and documentation.  
  *Deadline*: 29 July

- **Project 2 Submission**:  
  *Description*: Creation of Web API with CRUD operations and JWT authentication.  
  *Deadline*: 9 August

- **Project 3 Submission**:  
  *Description*: Development of a web application following design patterns and best practices.  
  *Deadline*: 23 August

- **Project 4 Submission**:  
  *Description*: Creation and testing of RPA bot.  
  *Deadline*: 6 September

- **Project 5 Submission**:  
  *Description*: Data visualization and reporting solution development.  
  *Deadline*: 7 October

---

## 5. Links to Documentation

Each project will have detailed technical documentation, which will be linked here. The documentation will include the solution design, data flow diagrams, technical assumptions, wireframes, and more.

- **Link to Project 1 Documentation**: [Link to Lean Documentation](#) : https://docs.google.com/document/d/1aR5QFJm3rLOH0r9dnZcBYL-6EqKuxf6ePkE2NSfeqEw/edit?usp=sharing

## 6. References

Agrawal, A., Gans, J. & Goldfarb, A., 2019. *The Economics of Artificial Intelligence: An Agenda*. University of Chicago Press.

Chacon, S. & Straub, B., 2014. *Pro Git*. 2nd ed. Apress.

Elmasri, R. & Navathe, S.B., 2015. *Fundamentals of Database Systems*. 7th ed. Pearson.

Esposito, D., 2021. *Modern Web Development with ASP.NET Core 5*. 1st ed. Packt Publishing.

Freeman, A., 2018. *Pro ASP.NET Core MVC 2*. 7th ed. Apress.

Garrett, J.J., 2011. *The Elements of User Experience: User-Centered Design for the Web and Beyond*. 2nd ed. New Riders.

Galloway, J., 2020. *Professional ASP.NET Core 3.0: Building Modern Web Apps with .NET*. 1st ed. Wrox Press.

Harrington, J., 2009. *Relational Database Design and Implementation*. 3rd ed. Morgan Kaufmann.

Jorgensen, M., 2019. *SQL Server 2019 Administration Inside Out*. 1st ed. Microsoft Press.

Loeliger, J. & McCullough, M., 2012. *Version Control with Git*. 2nd ed. O'Reilly Media.

Meszaros, G., 2007. *xUnit Test Patterns: Refactoring Test Code*. 1st ed. Addison-Wesley Professional.

Price, M., 2018. *C# 7 and .NET Core 2.0 High Performance: Build Highly Performant Applications*. 1st ed. Packt Publishing.

Rubin, K.S., 2012. *Essential Scrum: A Practical Guide to the Most Popular Agile Process*. Addison-Wesley.

Schwaber, K. & Sutherland, J., 2017. *The Scrum Guide*. Available at: https://scrumguides.org.

Silberschatz, A., Korth, H.F. & Sudarshan, S., 2020. *Database System Concepts*. 7th ed. McGraw-Hill Education.

Teorey, T.J., Lightstone, S. & Nadeau, T., 2010. *Database Modeling and Design: Logical Design*. 5th ed. Morgan Kaufmann.

UiPath, 2020. *UiPath Studio Documentation*. Available at: https://docs.uipath.com/studio/docs.

Unger, R. & Chandler, C., 2012. *A Project Guide to UX Design*. 2nd ed. New Riders.

Yochay, I., 2020. *Testing ASP.NET Core Applications*. Available at: https://docs.microsoft.com/en-us/aspnet/core/test/.


