Nexa Solutions Pvt Ltd - Frontend Repository
Welcome to the official Frontend repository of Nexa Solutions Pvt Ltd. This repository is crucial for our frontend development workflow. Please ensure that you follow the instructions below carefully to maintain a smooth and efficient development process.

Branching Strategy
We follow a structured branching strategy to ensure that our code is organized, tested, and deployed efficiently. There are three main branches in this repository:

Main/Master Branch

Purpose: This is the primary branch that contains all the deployment-ready code.

Usage: Only code that has been thoroughly tested and approved should be merged into this branch.

Develop Branch

Purpose: This branch is used for integrating features that have been developed but not yet fully tested or reviewed.

Usage: All feature branches should be merged here after initial development and basic testing.

Feature Branches

Purpose: These branches are created for individual features or tasks.

Naming Convention: Feature branches should be named as feature/<feature-name>. For example, if you are working on the homepage layout, the branch should be named feature/homepage-layout.

Usage: Each developer should create a feature branch for the specific task they are working on. Once the feature is developed, it should be merged into the develop branch via a pull request (PR).

Workflow Instructions
To ensure a consistent and error-free workflow, please follow these steps:

Clone the Repository

Clone the repository to your local machine using the following command:

bash
Copy
Edit
git clone <repository-url>
Switch to the Develop Branch

Navigate to the develop branch using the following commands:

nginx
Copy
Edit
git checkout develop
git pull
This ensures that your local develop branch is up-to-date with the latest changes.

Create a Feature Branch

Create a new branch for your feature using the following command:

css
Copy
Edit
git checkout -b feature/<feature-name>
Example: If you are working on the homepage layout, use git checkout -b feature/homepage-layout.

Develop Your Feature

Make your changes, ensuring your code is responsive, accessible, and works across different browsers.

Once you're done, add and commit your changes:

sql
Copy
Edit
git add .
git commit -m "Description of your changes"
Push Your Changes

Push your feature branch to the remote repository:

perl
Copy
Edit
git push origin feature/<feature-name>
Create a Pull Request

Go to the GitHub repository GUI and create a pull request (PR) from your feature branch to the develop branch.

Ensure your PR includes screenshots or video demos of the frontend changes, along with a clear explanation of what was done.

If there are any merge conflicts, you must resolve them manually before the PR can be merged.

Review and Merge

The team will review your pull request. Once approved, your feature will be merged into the develop branch.

After thorough testing, including cross-browser testing, the changes will be merged from the develop branch to the main branch for deployment.

Final Notes
Attention to Detail: Please carefully follow the above instructions to avoid any issues in the development process.

Descriptive Commits and PRs: Ensure that your commit messages and pull requests are clear and descriptive, making it easy for others to understand the changes.

Design Consistency: Ensure that all frontend changes adhere to the design guidelines and maintain consistency across the application.

Handle Merge Conflicts: If any merge conflicts arise, handle them promptly and effectively.

Happy coding, team!
