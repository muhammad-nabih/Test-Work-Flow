# Task 2: Create a New Feature Branch and Implement a Bug Fix

### Objective:
You are tasked with fixing a bug in the HTML file provided. To ensure a smooth workflow, follow the steps below carefully to avoid any conflicts with other contributors working on the same repository.

### Workflow:

1. **Clone the Repository:**
   - Clone the repository to your local machine using the following command:
     ```bash
     git clone [repository_url]
     ```

2. **Create a New Feature Branch:**
   - Each participant must create a new feature branch with a unique name based on your task and name format. This avoids conflicts when pushing changes.
   - Use the following naming convention: `[your-name]-[feature-bug-fix]`. For example:
     ```bash
     git checkout -b mohamed-fixHeadingBug
     ```

3. **Implement the Bug Fix:**
   - Open the `fix-head-bug.html` file located in the repository.
   - Apply your fix according to the bug description (fix heading increment issue, etc.).
   - Do **NOT** create new folders. Apply changes directly to the `fix-head-bug.html` file provided.

4. **Commit Your Changes:**
   - Once the bug is fixed, stage the changes and commit them using a descriptive message.
     ```bash
     git add fix-head-bug.html
     git commit -m "Fixed heading increment bug in HTML file"
     ```

5. **Push Your Changes to the Feature Branch:**
   - Push the changes to your newly created feature branch:
     ```bash
     git push origin mohamed-fixHeadingBug
     ```

6. **Create a Pull Request (PR):**
   - Go to GitHub and create a Pull Request (PR) for your feature branch to merge with the main branch.

