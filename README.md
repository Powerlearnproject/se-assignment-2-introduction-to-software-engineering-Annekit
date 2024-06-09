[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15238586&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:is the systematic application of the principles,methods and tools of engineering to develop and maintain high quality software systems

What is software engineering, and how does it differ from traditional programming?
Software Development Life Cycle (SDLC):software engineering is the systematic application of the principles,methods and tools of engineering to develop and maintain high quality software systems
difference between software engineering and tradditional programming
   -traditional programming focuses on creating a code to serve a specific task while SDLC focuses on creating large and complex systems to meet users needs and can be maintained and scaled over time

   -traditional programming may involve ad-hoc or informal approaches to coding and problem-solving emphasising on quick fixes or small-scale solutions while software engineering utilizes structured methodologies and processes e.g.Agile and Waterfall to ensure that all aspects of software development are planned, executed, and reviewed systematically

   -traditional programming often involves individual programmers or small teams working independently while software engineering involves larger, multidisciplinary teams working collaboratively e.g project managers, systems analysts, architects, designers, testers, and more

   -traditional programming testing and debugging may be done by the programmer with limited formal QA processes while software engineering incorporates rigorous testing, quality assurance, and validation processes to ensure the software meets specified requirements and standards

   -traditional programming documentation is minimal while software engineering emphasizes thorough documentation throughout the development process to facilitate maintenance, updates, and knowledge transfer.

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Agile vs. Waterfall Models:the phases of SDLC include the following
   -planning:identifying the project objectives and establishing a plan

   -requirements:gathering all the documents and information needed

   -design:Creating design documents, diagrams (e.g., UML diagrams)

   -implimentation:translate design specifications into executable code by writing the code according to design specifications and coding standards

   -testing:this is the process of checking whether the software is functioning and fixing the errors

   -deployment:the software is released to the users

   -maintainance:it includes updating the software

-agile model:is an iterative and incremental approach that emphasizes flexibility, collaboration, and customer feedback focusing on delivering small, functional pieces of software frequent

-waterfall model:is a linear and sequential approach where each phase must be completed before the next begins

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?Key Differences
Approach:

Agile: Iterative and incremental, focusing on flexibility and customer collaboration.
Waterfall: Linear and sequential, with an emphasis on planning and documentation.
Flexibility:

Agile: Highly adaptable to changes at any stage of development.
Waterfall: Rigid, with changes being difficult and costly to implement once phases are completed.
Customer Involvement:

Agile: Continuous engagement with customers throughout the project.
Waterfall: Limited to initial requirements gathering and final delivery.
Documentation:

Agile: Lightweight, with a focus on essential documentation.
Waterfall: Extensive, with detailed documentation for each phase.
Delivery:

Agile: Frequent delivery of working software increments.
Waterfall: Single delivery after the entire project is completed.
Risk Management:

Agile: Risks are mitigated through iterative development and frequent reassessment.
Waterfall: Risks are identified and planned for upfront, with limited flexibility to address new risks.

preferrable scenerios
agile
Projects with dynamic requirements and high uncertainty.
Environments where quick delivery and feedback are critical.
Teams that benefit from high levels of collaboration and communication.
Projects requiring regular reassessment and adaptation to changing market conditions.

waterfall
Projects with well-defined, stable requirements.
Environments where changes are unlikely or discouraged.
Projects where rigorous documentation and clear milestones are essential.
Large-scale projects with multiple dependencies and a need for a structured approach.
Situations where regulatory compliance requires detailed documentation and phase approvals.

requirements Engineering:
Agile:
requirements are gathered and refined continuously through user stories and backlog management.
Prioritization of requirements is based on customer feedback and business value.
Flexibility allows for changes and additions to requirements at any stage

Waterfall:
requirements are gathered upfront and documented in detail.
Changes to requirements are managed through a formal change control process.
Clear and thorough documentation ensures that all requirements are addressed before moving to the next phase.

What is requirements engineering? Requirements engineering is the process of defining, documenting, and maintaining the requirements for a software system
Describe the process and its importance in the software development lifecycle.
Process of Requirements Engineering:

Requirements Elicitation:

Objective: Gather requirements from stakeholders, including customers, users, and other parties involved.
Techniques: Interviews, surveys, questionnaires, workshops, brainstorming sessions, and observations.
Outcome: A list of initial requirements.
Requirements Analysis:

Objective: Analyze and refine the gathered requirements to ensure they are clear, complete, consistent, and feasible.
Techniques: Requirement prioritization, conflict resolution, feasibility studies, and trade-off analysis.
Outcome: Refined and validated requirements.
Requirements Specification:

Objective: Document the requirements in a clear and detailed manner.
Techniques: Use of requirement specification documents, user stories, use cases, and functional specifications.
Outcome: A formal requirements specification document that serves as a reference throughout the development process.
Requirements Validation:

Objective: Ensure that the documented requirements accurately reflect the stakeholders' needs.
Techniques: Reviews, walkthroughs, inspections, and prototyping.
Outcome: Validated requirements that are approved by stakeholders.
Requirements Management:

Objective: Manage changes to requirements over the course of the project.
Techniques: Version control, change impact analysis, traceability matrices, and requirements tracking tools.
Outcome: Controlled and managed requirements that adapt to changes and maintain consistency.
Importance in the Software Development Lifecycle:

Alignment with Stakeholder Needs:

Ensures the software meets the expectations and needs of all stakeholders, reducing the risk of delivering a product that does not fulfill its intended purpose.
Foundation for Design and Development:

Provides a clear and detailed blueprint for developers and designers to follow, ensuring that all necessary features and functionalities are included.
Improved Quality and Usability:

Thoroughly analyzed and validated requirements lead to higher quality and more user-friendly software.
Risk Mitigation:

Identifying and addressing potential issues early in the requirements phase can prevent costly changes and rework later in the development process.
Cost and Time Efficiency:

Clear requirements reduce ambiguity, leading to more accurate project planning, budgeting, and scheduling, ultimately saving time and resources.
Facilitates Communication:

Provides a common understanding and reference point for all team members and stakeholders, improving collaboration and communication.

Software Design Principles:Separation of Concerns:

Description: Divide a software system into distinct sections, each addressing a specific concern or functionality.
Benefit: Improves modularity and makes the system easier to understand and maintain.
Single Responsibility Principle (SRP):

Description: A class or module should have one, and only one, reason to change.
Benefit: Enhances cohesion and reduces the impact of changes.
Open/Closed Principle (OCP):

Description: Software entities should be open for extension but closed for modification.
Benefit: Allows the system to be extended without altering existing code, reducing the risk of introducing bugs.
Liskov Substitution Principle (LSP):

Description: Subtypes must be substitutable for their base types without affecting the correctness of the program.
Benefit: Ensures that derived classes extend the functionality of base classes without changing their behavior.
Interface Segregation Principle (ISP):

Description: Clients should not be forced to depend on interfaces they do not use.
Benefit: Promotes the creation of more specific and relevant interfaces, enhancing modularity.
Dependency Inversion Principle (DIP):

Description: High-level modules should not depend on low-level modules. Both should depend on abstractions.
Benefit: Reduces coupling between components and improves flexibility and reusability.
DRY (Don't Repeat Yourself):

Description: Avoid duplication of code by abstracting common functionality.
Benefit: Simplifies maintenance and reduces the risk of inconsistencies.
YAGNI (You Aren't Gonna Need It):

Description: Do not add functionality until it is necessary.
Benefit: Prevents over-engineering and keeps the system simple and focused.
KISS (Keep It Simple, Stupid):

Description: Strive for simplicity in design and avoid unnecessary complexity.
Benefit: Enhances readability and maintainability.
Encapsulation:

Description: Bundle the data with the methods that operate on the data, and restrict direct access to some of the object's components.
Benefit: Protects the internal state of the object and reduces system complexity.
Modularity:

Description: Design the system as a set of distinct modules that can be developed, tested, and understood independently.
Benefit: Simplifies development, testing, and maintenance

Explain the concept of modularity in software design.
Modularity refers to the design principle of dividing a software system into distinct, independent units or modules, each encapsulating a specific piece of functionality. These modules interact with each other through well-defined interfaces. The goal of modularity is to break down a complex system into smaller, manageable parts that can be developed, tested, maintained, and understood independently.

Key Characteristics of Modularity:

Separation of Concerns: Each module addresses a specific aspect or concern of the system, promoting focus and clarity.
Encapsulation: Modules hide their internal implementation details and expose only what is necessary through public interfaces.
Reusability: Modules can be reused across different parts of the application or even in different projects.
Interchangeability: Modules can be easily replaced or upgraded without affecting other parts of the system, as long as the interfaces remain consistent.
Cohesion and Coupling: High cohesion within modules (each module performs a single task) and low coupling between modules (dependencies are minimized) are essential for effective modularity.

 How does it improve maintainability and scalability of software systems?

Maintainability:

Isolation of Changes:

Benefit: Changes in one module do not affect others if interfaces remain unchanged, reducing the risk of introducing bugs.
Example: Fixing a bug or adding a feature in a user authentication module does not impact the payment processing module.
Simplified Debugging and Testing:

Benefit: Modules can be tested and debugged independently, making it easier to identify and fix issues.
Example: Unit testing a data processing module without involving the user interface logic.
Clear Structure and Documentation:

Benefit: Well-defined modules and interfaces make the system architecture clearer and easier to understand for new developers.
Example: A developer can understand and work on a specific module without needing to know the entire system.
Parallel Development:

Benefit: Different teams can work on different modules simultaneously, speeding up development.
Example: One team works on the backend services while another team focuses on the frontend.
Scalability:

Efficient Resource Management:

Benefit: Modules can be deployed and scaled independently based on demand.
Example: Scaling the database module separately when there is a high volume of transactions.
Flexible Deployment:

Benefit: Modules can be deployed on different servers or environments, optimizing performance and resource utilization.
Example: Deploying compute-intensive modules on powerful servers and lightweight modules on less powerful servers.
Service-Oriented Architecture (SOA) and Microservices:

Benefit: Modular design aligns well with SOA and microservices architectures, which are inherently scalable.
Example: Each microservice handles a specific business function and can be scaled independently.
Load Distribution:

Benefit: Workloads can be distributed across multiple modules, preventing bottlenecks.
Example: Load balancing incoming requests among several instances of a web service module.

Testing in Software Engineering:
Testing in software engineering is the process of evaluating a software application to ensure that it meets the specified requirements and is free of defects. It involves executing the software to identify any gaps, errors, or missing requirements contrary to the actual requirements.

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing).
.1 Unit Testing:

Description:

Scope: Tests individual components or units of code, such as functions or methods, in isolation from the rest of the system.
Objective: Ensure that each unit functions correctly and as intended.
Performed By: Developers.
Tools: JUnit (Java), NUnit (.NET), pytest (Python), Jasmine (JavaScript).
Benefits:

Early Bug Detection: Catches bugs early in the development process.
Simplifies Debugging: Easier to pinpoint the exact location of a bug.
Code Quality: Promotes writing cleaner, more modular code.
Example:

Testing a single function in a library that calculates the square root of a number to ensure it handles all edge cases correctly.
2. Integration Testing:

Description:

Scope: Tests the interaction between integrated modules or components to ensure they work together as expected.
Objective: Detect issues in the interfaces and interaction between modules.
Performed By: Developers and sometimes dedicated testers.
Tools: Postman, SoapUI, JUnit, pytest.
Benefits:

Interface Validation: Ensures that modules communicate correctly.
Detects Interaction Issues: Identifies problems that arise from the integration of different parts of the system.
Smooth Integration: Facilitates the smooth integration of modules developed by different team members or teams.
Example:

Testing the interaction between a user authentication module and a database to ensure user data is correctly validated and retrieved.
3. System Testing:

Description:

Scope: Tests the complete and integrated software system as a whole.
Objective: Validate the end-to-end functionality and behavior of the system against the specified requirements.
Performed By: Dedicated testing teams.
Tools: Selenium, QTP (QuickTest Professional), LoadRunner.
Benefits:

Comprehensive Coverage: Ensures that the entire system functions correctly under various scenarios.
Requirement Validation: Validates that the system meets all specified requirements.
Defect Identification: Identifies defects that were not found during unit or integration testing.
Example:

Testing a complete e-commerce application to ensure all features, such as product search, shopping cart, and payment processing, work together seamlessly.
4. Acceptance Testing:

Description:

Scope: Tests the system against user requirements and business needs.
Objective: Ensure the system is ready for deployment and meets the acceptance criteria set by the stakeholders.
Performed By: End-users, clients, or QA teams.
Tools: Cucumber, FitNesse.
Benefits:

User Validation: Ensures that the system meets the users' needs and expectations.
Final Verification: Acts as the final verification before the system goes live.
Customer Satisfaction: Increases confidence in the system’s readiness for production use.
Example:

Conducting tests with real users to validate that a new feature in a mobile banking app meets their needs and performs as expected in a real-world environment.

 Why is testing crucial in software development?
 Quality Assurance: Ensures that the software meets the required quality standards and functions correctly.
Defect Detection: Identifies and fixes defects before the software is deployed, reducing the risk of failures in production.
Requirement Validation: Confirms that the software meets the specified requirements and user needs.
Performance Verification: Ensures the software performs well under various conditions and workloads.
Security Assurance: Identifies and mitigates security vulnerabilities to protect the software and its users.
Cost Reduction: Detecting and fixing defects early in the development process is less costly than addressing them after deployment.
User Satisfaction: Ensures a positive user experience by delivering reliable and functional software.

Version Control Systems:Version Control Systems are tools that help manage changes to source code over time. They are essential for collaborative software development and provide a systematic way to track and manage code changes.

What are version control systems, 
Version Control Systems (VCS) are tools that help manage and track changes to software code over time. They allow multiple developers to collaborate on a project, maintain different versions of the codebase, and ensure that changes can be reversed if necessary. VCS are essential for coordinating work among team members, maintaining historical records of code changes, and supporting parallel development efforts.

and why are they important in software development?

Importance of Version Control Systems in Software Development
Collaboration: VCS enable multiple developers to work on the same codebase simultaneously without overwriting each other's changes. They facilitate collaborative development by providing mechanisms to merge changes from different developers.

Change Tracking: Every change made to the code is recorded, along with metadata such as who made the change, when it was made, and why. This historical record is invaluable for understanding the evolution of the codebase and for debugging.

Version Management: VCS allow developers to create branches for new features, experiments, or bug fixes. This makes it easy to manage different versions of the software and integrate changes when they are ready.

Backup and Recovery: Code is stored in a repository, which acts as a backup. If a mistake is made, developers can revert to a previous version of the code. This ensures that the project can recover from errors without losing significant work.

Release Management: VCS facilitate the management of software releases. Developers can tag specific versions of the codebase to correspond with release versions, making it easy to deploy, maintain, and support different versions of the software.
 Give examples of popular version control systems and their features.
 1. Git
Description: Git is a distributed version control system known for its performance, flexibility, and powerful branching and merging capabilities.

Features:

Distributed Architecture: Each developer has a complete copy of the repository, enabling offline work and reducing the risk of data loss.
Branching and Merging: Supports complex workflows by allowing developers to create and merge branches easily.
Staging Area: Changes can be added to a staging area before committing, allowing for more control over the commit process.
Performance: Designed for speed and efficiency, even with large codebases.
Community and Ecosystem: Extensive documentation, active community support, and integration with numerous tools and platforms (e.g., GitHub, GitLab, Bitbucket).
2. Subversion (SVN)
Description: Subversion (SVN) is a centralized version control system that is known for its simplicity and straightforward approach to version control.

Features:

Centralized Repository: A single repository where all changes are stored and managed.
Atomic Commits: Ensures that commits are atomic, meaning that either all changes are committed, or none are.
Versioned Directories: Tracks changes to directories, as well as files.
Branching and Tagging: Supports creating branches and tags, though branching is less flexible than in Git.
Access Control: Fine-grained access control to manage permissions for different parts of the repository.
3. Mercurial
Description: Mercurial is a distributed version control system known for its simplicity, performance, and ease of use.

Features:

Distributed Architecture: Similar to Git, each developer has a complete copy of the repository.
Performance: Optimized for handling large repositories efficiently.
Simple Commands: User-friendly command syntax that is easy to learn.
Branching and Merging: Supports branching and merging, though it is generally considered simpler than Git's model.
Extensibility: Supports extensions to add custom functionality or integrate with other tools.

Software Project Management:Software Project Management involves planning, organizing, and managing resources to bring about the successful completion of specific software project goals and objectives. It includes a variety of tasks, such as defining the project scope, scheduling, resource allocation, risk management, and communication.

Discuss the role of a software project manager. 
A Software Project Manager (SPM) is pivotal in guiding a software project from its initial concept to final delivery. Their primary role is to ensure the project is completed on time, within budget, and meets the required quality standards. They act as the bridge between the development team and stakeholders, ensuring effective communication and alignment of project goals.

What are some key responsibilities and challenges faced in managing software projects?
Key Responsibilities of a Software Project Manager
Project Planning and Scheduling:

Defining project scope and objectives.
Creating detailed project plans, including timelines, milestones, and deliverables.
Allocating resources and setting realistic deadlines.
Team Management:

Leading and motivating the project team.
Assigning tasks based on team members' skills and strengths.
Facilitating communication and collaboration among team members.
Risk Management:

Identifying potential risks and issues.
Developing mitigation strategies and contingency plans.
Monitoring and managing risks throughout the project lifecycle.
Budget Management:

Estimating project costs and managing the budget.
Tracking expenditures and ensuring the project stays within financial constraints.
Reporting financial status to stakeholders.
Quality Assurance:

Ensuring the software meets quality standards and requirements.
Implementing testing strategies and overseeing the testing process.
Facilitating reviews and audits.
Stakeholder Communication:

Keeping stakeholders informed about project progress.
Managing expectations and ensuring stakeholder requirements are met.
Handling feedback and addressing concerns.
Change Management:

Managing changes to project scope, schedule, and resources.
Assessing the impact of changes and updating plans accordingly.
Ensuring all changes are documented and communicated to the team.
Documentation and Reporting:

Maintaining project documentation, including plans, reports, and records.
Preparing regular status reports for stakeholders.
Documenting lessons learned and best practices for future projects.
Challenges Faced in Managing Software Projects
Scope Creep:

Uncontrolled changes or continuous growth in project scope.
Managing stakeholder expectations to prevent scope creep.
Balancing new requirements with project constraints.
Resource Constraints:

Limited availability of skilled personnel.
Managing resource allocation efficiently.
Dealing with competing priorities for shared resources.
Time Management:

Meeting tight deadlines.
Handling delays and ensuring timely delivery.
Balancing speed and quality.
Technical Challenges:

Addressing technical complexities and issues.
Ensuring the team has the necessary technical skills and knowledge.
Keeping up with rapidly evolving technologies.
Communication Gaps:

Ensuring effective communication among team members, especially in remote or distributed teams.
Overcoming language and cultural barriers.
Keeping all stakeholders aligned and informed.
Risk and Uncertainty:

Managing unexpected risks and uncertainties.
Developing robust risk management strategies.
Maintaining flexibility to adapt to changes.
Quality Assurance:

Ensuring the software meets all quality requirements.
Balancing quality with time and budget constraints.
Implementing effective testing and review processes.

Software Maintenance:Software maintenance involves modifying and updating software applications after delivery to correct faults, improve performance, or adapt the software to a changed environment. It is a critical aspect of the software lifecycle and ensures the longevity and relevance of the software.

Define software maintenanceSoftware maintenance involves modifying and updating software applications after delivery to correct faults, improve performance, or adapt the software to a changed environment. It is a critical aspect of the software lifecycle and ensures the longevity and relevance of the software.
 
explain the different types of maintenance activities.
Types of Maintenance Activities
Corrective Maintenance:

Purpose: To fix bugs and errors discovered after the software is deployed.
Activities: Debugging, patching, and repairing defects that affect software functionality.
Adaptive Maintenance:

Purpose: To modify the software to work in a new or changing environment.
Activities: Updating the software to be compatible with new hardware, operating systems, or other software, and ensuring it meets new regulations or standards.
Perfective Maintenance:

Purpose: To enhance and improve the software beyond its original requirements.
Activities: Adding new features, improving user interface design, optimizing code for better performance, and enhancing documentation.
Preventive Maintenance:

Purpose: To identify and address potential issues before they become serious problems.
Activities: Code refactoring, updating documentation, and conducting regular reviews to ensure the software remains robust and efficient.

 Why is maintenance an essential part of the software lifecycle?
 Importance of Maintenance in the Software Lifecycle
Maintenance is an essential part of the software lifecycle for several reasons:

Longevity and Relevance:

Ensures the software remains useful and relevant in the face of evolving user requirements and technological advancements.
Reliability and Performance:

Improves software reliability and performance by fixing bugs and optimizing code, which enhances user satisfaction and trust.
Cost-Effectiveness:

Regular maintenance can prevent major failures that are costly to fix, making it a more economical approach in the long run.
Compliance and Security:

Ensures the software complies with new regulations and standards and addresses security vulnerabilities, protecting user data and maintaining legal compliance.
User Satisfaction:

By adding new features and improving existing ones, maintenance ensures that the software continues to meet user needs and expectations, leading to higher satisfaction and loyalty.

Ethical Considerations in Software Engineering:Ethical considerations are crucial in software engineering to ensure that software is developed and maintained responsibly and transparent

What are some ethical issues that software engineers might face?
Privacy:

Protecting user data from unauthorized access and ensuring data is collected, stored, and used responsibly and transparently.
Security:

Implementing robust security measures to protect software from malicious attacks and ensuring the integrity and confidentiality of data.
Quality:

Delivering high-quality software that meets user requirements and performs reliably, avoiding harm caused by defective or substandard software.
Transparency:

Maintaining clear and honest communication with stakeholders about the capabilities, limitations, and risks associated with the software.
Accountability:

Taking responsibility for the software’s impact, including addressing any issues that arise post-deployment and being accountable for the decisions made during development.
Sustainability:

Considering the long-term impact of the software on society and the environment, promoting practices that support sustainable development.
Fairness:

Ensuring the software does not discriminate against or unfairly disadvantage any group of users and promoting inclusivity and accessibility.
Intellectual Property:

Respecting intellectual property rights by ensuring the software does not infringe on patents, copyrights, or trademarks and properly crediting the contributions of others.

 How can software engineers ensure they adhere to ethical standards in their work?
 Stay Informed: Keep abreast of ethical guidelines, codes of conduct, and professional standards relevant to software engineering. This includes understanding the ethical implications of emerging technologies and staying informed about regulatory requirements related to privacy, security, and data protection.

Ethical Design and Development: Incorporate ethical considerations into the design and development process from the outset. This involves identifying potential ethical issues associated with the software or system being developed and proactively addressing them through ethical design principles and practices.

Informed Consent: Obtain informed consent from users before collecting or using their data. Ensure transparency regarding how user data will be collected, processed, stored, and shared, and provide users with clear and accessible information about their rights and options for controlling their data.

Privacy Protection: Prioritize the protection of user privacy by implementing privacy-enhancing technologies and practices. Minimize the collection of unnecessary personal data, use strong encryption and authentication mechanisms to safeguard sensitive information, and regularly assess and mitigate privacy risks.

Security Measures: Prioritize security in software design and implementation to protect against unauthorized access, data breaches, and cyberattacks. Follow best practices for secure coding, encryption, authentication, and access control, and conduct regular security audits and vulnerability assessments to identify and address potential security risks.

Diversity and Inclusion: Promote diversity and inclusion within the software development team and consider diverse perspectives and experiences in design decisions. Minimize biases and stereotypes in software design and development to ensure equitable outcomes for all users.

Accountability and Transparency: Take responsibility for the ethical implications of software engineering decisions and actions. Foster a culture of transparency and accountability within the organization, where ethical issues are openly acknowledged and addressed, and mistakes are learned from rather than ignored or covered up.

Continuous Improvement: Regularly evaluate and update ethical standards and practices in response to evolving technologies, societal values, and regulatory requirements. Encourage ethical reflection and critical thinking among software engineers through ongoing training, discussions, and professional development opportunities.

references(class recordings,google and chatgpt)

Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
