# Inventory Management System, a Salesforce Project

### Sprint Antarctica ( Feb 11 2022 - Feb 26 2022 )
    Overall goal: I will implement a basic version of inventory counting in a silo
        - Create a Lightning App for the Inventory System - complete
        - Create a custom page skeleton to handle all inventory interactions - complete
        - Create logic to capture inventory acquisition - not complete
        - Create logic needed to update inventory allocations - partially complete
            For removing inventory, this actually needs to be logged for analysis and reclaiming.
            For adding inventory, I have to be able to add a new location on demand.
            In order to need only one flow, I will have to refactor the flow in order to include all options (adding, removing, transfering, and reclaiming)
        - Create a permission set for this app and the objects - complete
        - Write test classes for logic with 100% coverage - not needed at this time
        - Create a video demo and post on social media so I can be judged by real experts in the field - complete
            [Inventory Management System Ad 1](https://youtu.be/ZvB5hMlyqqU)

        - If I do not finish everything, give reasons why in documentation, although I will still give myself a pay raise in the form of time off from personal Salesforce projects.

    Sprint Notes:
        I will need an object in order to capture when inventory is brought into the company, and when inventory is removed from the company. This is to actually capture this information in a manner to report on and allow rich data to be captured rather than a simple number.

        Even though the ERD is valid for this sprint, the ERD will have to be updated to include these new objects. The processes will have to be documented as well so it is apparent what the flows are doing. I also need documents on the user interface. So these documents are the core documents that will have to be updated as the project progress and the use cases increase.

        The flow then would be designed after the model, control, and view document updates.

        In addition, I need to ignore the admin profile when pulling and pushing because I only want the Inventory permissions to be handled through the permission set.

        I will have to research inventory management problems that are generally faced, and provide a Salesforce solution to them.

        I am Tech Lead for this project as well as the Senior and Junior developer. I will incorporate Sr. Level Tasks within this project though it is unconventional to my knowledge.

        I did not finish the proposed functionality, and will delay it until I am certain that the flow is the best method for this project.

        At the end of the sprint, I had to make a decision whether to continue developing or to understand the development process better. In the end, I believe practicing documentation, understanding the process, and aloowing myself to relearn and revisit topics I once thought obvious would make me a more suitable candidate for more projects going forward on the Salesforce platform and potentially other platforms as well. With that said, because I feel insecure, I will add some development tasks as well to the next sprint.

### Sprint Berkeley ( Feb 27 2022 - Mar 12 2022 )
    Overall goal: I will increase my knowledge about the SDLC. I will focus on the planning aspect of this project (What is software without a plan for use?). In addition, I will do some self-study to refresh and relearn relevant topics. I will also add a few components to the project to not feel lazy. Hopefully I get this done.

        1. Create project documentation for this software package. Fill in as much as possible.
            Product documentation
                System documentation
                    Requirements Documentation - business rules, user stories, use cases
                        Roles and responsibilities, Business objective, Assumptions, User stories, User interactions and design, Questions, Backlog, + diagrams/images/graphs/etc.
                Stakeholder Document
                User documentation: Manager User Guide, Standard User Guide, + Support resources
                System archicture: Platform, Architecture designs, Optimization, backup, and security concerns
                Quality Assurance: Test Strategy, Test Plan, Test case specification, Test checklists
            Process documentation
                Plans, estimates, and schedules
                Reports and metrics of project development
                Working papers/ Project Journal
                Standards
                Tools Used and associated documentation

        2. Create technical documentation in order to show how object data is manipulated for each current use case. Publish the process documentation. Then update the ERD to handle the process requirements. Publish the ERD.

        3. Create SDLC documentation for how you will document, design, develop, deploy, and support the project in a multi-developer environment. This document will be added to the Process Documentation

        4. Do an assessment on how the tools used (Git, SFDCX, etc.) will enable to the development, and document best practices for the project (as well as source). Add this file called "Best Practices" in order to document the standards.

        5. Create objects according to ERD.
        6. Create individual flows in order to add inventory, remove inventory, and reclaim inventory.

        7. Create sprint notes and have sprint notes added to process notes (Yay! No more giant README's). Hopefully after this sprint, documentation will be nicely tucked away and do most of the talking.

        8. Plan next sprint.

        Self Study:
            Agile methodolgy
            Scrum methodology
            Git handling version control and repository best practices
            SFDX development best practices
            Software development and project management best practices
        
        Sources of Knowledge (used in this Sprint):
            https://blog.prototypr.io/software-documentation-types-and-best-practices-1726ca595c7f
