[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15222493&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

Involves use of principles and practices from computer science, project management, engineering and other disciplines to create high quality software that meets user requirements is reliable,  efficient and mantainable.



What is software engineering, and how does it differ from traditional programming?

Software engineering is an engineering process primarily related to computers, programming, and developing various applications using information technology while traditional programming involves writing code for specific tasks or functionalities



Software Development Life Cycle (SDLC):



Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

1. Planning and analysis
 - This is the initial phase in which business requirements are gathered from stakeholders

2. Requirements Definition
  - Converts information from the planning phase into clear requirements
  - Helps in guiding development team

3. Design
 - Focuses on system architecture, user interface and data design.
4. Development
 - Actual coding and implementation of the software
5. Testing
 - Rigorous testing to identify and fix defects
 - Includes unit testing, integration testing, and system testing.
6. Deployment
 - Software is deployed to production environments
 - Users can access and use the platform

7. Maintenance
- Continuos support, bug fixes, and updates


Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
 - The Waterfall model follows a linear and sequential method of development while the Agile method is iterative and incremental.
 - Agile  model is highly adaptable to changes in requirements, with regular reassessment and adjustments whereas Waterfal flexibility is low.
 - In Waterfall customer involvement is limited to certain milestones while in Agile customer involvement is continuos.
 - In Waterfall documentation is detailed and extensive while in Agile the documentation is minimal, just enough for progress.
 - The Waterfall model is best suited for projects with well-defined, stable requirements and regulatory needs, whereas the Agile model excels in dynamic environments where flexibility and customer feedback are crucial.

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Requirement engineering (RE) is the process of defining, documenting and maintaining the requirements of a system or software.

1. Feasibility Study
- Assesses whether the project should proceed.
- Examines technical, economic, legal, operational, and schedule feasibility.
2. Requirement Elicitation and Analysis
- Involves detailed gathering of requirements.
- Identifies needs and wishes of potential users.

3. Software Requirement Specification

 - Documents requirements in a clear and structured manner
 - Forms the basis for design and development.

4. Software Requirement Validation
- Ensures that the specified requirements are accurate and complete.
- Helps prevent misunderstandings and costly errors.


Software Design Principles:


Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

Modularity in software design is a technique where complex software is divided into smaller, independent modules, such as functions, classes, or components.It facilitates easier management and understanding of complex systems by breaking them down into digestible parts.




Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?

Unit Testing

- Unit testing is when every module of the application gets tested respectively
- Unit testing is done by the developer himself. After he has written code for a feature, he will ensure it is working fine
- Junit, Pytest, and TestNg frameworks for unit testing the application are used.

Integration Testing
- Integration testing is a testing technique where two or more independent components are tested together.
- Integration testing is done by the developer. Here test cases are written to ensure the data flowing between them is correct.
- Integration testing is done when the application is still developing to find bugs early on in the development process

System Testing

- System testing is done by the tester where the entire application is tested as a single unit.
- Hence, system testing test cases are also performance test cases, load testing, and stress testing test cases.

Acceptance Testing

- Acceptance testing is done by the client where he evaluates whether the product is made by the requirement he listed out.
- Acceptance testing is done at the UAT server where a well-tested product is deployed by the team for the client's reference so he can track ongoing changes in the project



Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

Version control are tools that help manage changes to source code or other collections of information over time.They help collaboration among developers and also help in history tracking of changes made to files and who made them. Another important benefit is they act as backups for data.Examples of version control include: 

1. Git
 - Distributed Version Control: Every developer has a complete copy of the repository, including its history.
 - Branching and Merging: Highly efficient branching and merging capabilities, allowing multiple parallel development lines.
 - Strong Community and Ecosystem: Extensive support and integration with tools like GitHub, GitLab, and Bitbucket

2. Subversion
 - Centralized Version Control: Single central repository that clients check out and commit to.
 - Atomic Commits: Ensures that commits are atomic, meaning either all changes are committed, or none are.
 - Access Control: Fine-grained control over who can read and write to the repository.

3. Mercurial
 - Distributed Version Control: Similar to Git, every developer has a complete copy of the repository.
 - Performance: Designed for high performance, handling large codebases efficiently.
 - Integrated Tools: Comes with a set of integrated tools for managing repositories, history, and patches.

4. Perforce

 - Centralized Version Control: Central repository that developers check out files from and submit changes to.
 - File Locking: Allows locking of files to prevent conflicts on binary files and other non-mergeable content.



Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

1. Planning and Coordination
 - Define project scope, objectives, and deliverables.
 - Coordinate tasks among team members.
2. Risk Management
- Identify potential risks and develop mitigation strategies. 
- Monitor risks throughout the project lifecycle.

3. Quality Assurance
- Define quality standards and processes.
- Conduct reviews and inspections.

  **Challenges**
  - Handling unexpected changes or delays.
  - Managing risks without compromising project goals.
  - Navigating conflicting viewpoints.
  - Ensuring consistent code quality.
  - Budget constraints and changing resource availability.


Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Software maintenance is the process of modifying and updating software applications after their initial deployment to correct faults, improve performance, adapt to new environments, or enhance features.
 **Types of maintenance activities**
 - Corrective Maintenance: - To fix bugs and errors found in the software after it has been released.
 - Adaptive Maintenance - To modify the software to keep it usable in a changing environment.
 - Perfective Maintenance - To enhance and improve the functionality, performance, and usability of the software.
 - Preventive Maintenance - To identify and address potential issues before they become actual problems, thereby preventing future faults.

   **Importance of mainteinance**
- Maintenance extends the life of the software by keeping it relevant and functional in the face of changing user requirements and technological advancements.
- Ongoing maintenance activities can optimize and enhance the performance and efficiency of the software, making it more responsive and reliable.
- Regular maintenance helps to identify and fix security vulnerabilities, protecting the software from potential threats and attacks.


Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
 
1. Data Privacy
  - Handling user data responsibly is crucial.
  - Engineers should follow privacy regulations and prioritize user consent

2. Accessibility
 - Ensuring equal access to technology for all users
 - Addressing diverse needs, such as disabilities or language barriers.

3. Algorithmic Bias
- Algorithms can perpetuate biases (e.g., racial, gender, or socioeconomic).
- Engineers must mitigate bias during development and testing.

4. Software Security
- Ethical obligation to create secure software.
- Neglecting security can harm users and organizations.

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
