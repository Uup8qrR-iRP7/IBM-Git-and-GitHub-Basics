# IBM-GGB_006_GitHub Branches


## GitHub Branches Overview (Precise)

### Purpose of Branches
- **Definition**: Branches in GitHub allow for parallel development and experimentation without affecting the main codebase.
- **Main Branch**: 
  - The definitive branch that stores the deployable version of the code.
  - Created by default, but any branch can be designated as the main finished version.

### Creating and Using Branches
1. **Creating a New Branch**:
   - Click the dropdown menu next to the branch name (default is "Main").
   - Enter a descriptive name for the new branch.
   - Select **"Create Branch"**.
   - The new branch starts as an exact copy of the original branch.

2. **Working on a Branch**:
   - As changes are made, the new branch holds the modified code.
   - Developers work on source files within their respective branches.

### Merging Changes
- **Merging Process**:
  - When development is complete, branches can be merged.
  - Each branch's code is identified as a "tip."
  - Merging combines the tips into a third branch.

### Committing Changes
1. **Making Changes**:
   - Select the file to edit.
   - Click the pencil icon to enter edit mode.
   - Make your changes and commit them.

2. **Commit Process**:
   - A commit indicates a stable platform for the developed features.
   - Developers must write a meaningful and descriptive comment for each commit.
   - Options to commit to the current branch or create a new branch.

3. **Best Practices for Commit Messages**:
   - Avoid ending messages with a period.
   - Keep messages under 50 characters.
   - Use the extended window for details.
   - Write in an active voice.

### Pull Requests
- **Definition**: Pull requests initiate the merging of branches and allow others to review proposed changes.
- **Creating a Pull Request**:
  1. Click **"Pull requests"** and select **"New pull request."**
  2. Choose the new branch from the compare box.
  3. Review the changes and confirm they are correct.
  4. Add a title and description for the pull request.
  5. Click **"Create pull request."** 

- **Approval Process**:
  - Pull requests require approval from a user (could be the author or another team member).
  - GitHub automatically creates a pull request if changes are made on a branch that the user does not own.
  - The log files are immutable, allowing tracking of who approved merges.

### Merging Pull Requests
- To merge the committed code changes into the main branch:
  1. Click **"Merge pull request."**
  2. Click **"Confirm merge."**

### Deleting Obsolete Branches
- Once all changes for a branch are complete, that branch should be deleted as it becomes obsolete.

### Summary of Key Points
- All files in GitHub exist on a branch.
- The main branch contains the finished deployable version of the code.
- Create new branches for code changes; they start as exact copies of the original.
- Multiple branches can undergo changes simultaneously.
- Saved changes are referred to as commits.
- Pull requests enable review and integration of proposed changes into the main branch.

--- 
____



## GitHub Branches Overview (Detailed)


![Screenshot 2024-09-05 171803.png](../_resources/Screenshot%202024-09-05%20171803.png)


### Purpose of Branches
- **Definition**: Branches in GitHub are used to facilitate parallel development. They allow developers to work on features, fixes, or experiments independently without affecting the main codebase.
  
### Main Branch
- **Main Branch Characteristics**:
  - The **main branch** (often called "main" or "master") is the definitive branch that stores the deployable version of your code.
  - It is created by default when a repository is initialized.
  - While the main branch is typically the stable version, any branch can be designated as the main finished version if needed.
  - **Example**: In an e-commerce application, the main branch might contain the stable version that users interact with, while feature branches are used for developing new functionalities.

### Creating and Using Branches
1. **Creating a New Branch**:
   - **Steps**:
     - Click the dropdown menu next to the current branch name (default is "Main").
     - In the text box that appears, enter a descriptive name for the new branch (e.g., `feature/add-login`, `bugfix/fix-typo`).
     - Select **"Create Branch"** to finalize creation.
   - **Initial State**: The new branch starts as an exact copy of the original branch, capturing its current state. This ensures that you can develop new features without disrupting the existing code.

2. **Working on a Branch**:
   - As changes are made in the new branch, it holds the modified code while the original branch remains unchanged.
   - Developers can switch between branches to work on different features or fixes.
   - **Example**: A developer might create a branch called `feature/payment-integration` to work on integrating a payment gateway without affecting the main branch.

### Merging Changes


![Screenshot 2024-09-05 171913.png](../_resources/Screenshot%202024-09-05%20171913.png)


- **Merging Process**:
  - When development on a branch is complete, it is time to merge the changes back into the main branch or another branch.
  - Each branch's code is identified as a **"tip,"** representing the latest commit on that branch.
  - **Tip**: The tip is essentially the most recent state of a branch after the last commit. For instance, if you commit changes to the `feature/payment-integration` branch, the tip of that branch reflects those latest changes.
  - Merging combines the tips of the branches into a third branch, often the main branch.

### Committing Changes


![Screenshot 2024-09-05 172231.png](../_resources/Screenshot%202024-09-05%20172231.png)


1. **Making Changes**:
   - To edit a file in a branch:
     - Navigate to the file you want to change.
     - Click the pencil icon to enter edit mode.
     - Make the necessary changes to the code.

2. **Commit Process**:
   - After making changes, you must commit them to save your work.
   - A **commit** indicates that the developer believes the code represents a stable version of the feature being developed.
   - **Commit Message**: Each commit requires a meaningful and descriptive comment explaining the changes made.
     - You can commit to the current branch or create a new branch for the changes.
   - **Example**: If a developer fixes a bug in the payment integration, the commit message could be "Fix null pointer exception in payment processing."

3. **Best Practices for Commit Messages**:
   - **Formatting**: 
     - Avoid ending the commit message with a period.
     - Keep the subject line under 50 characters.
     - Use the extended window for detailed descriptions if necessary.
   - **Writing Style**: 
     - Always write in an active voice to convey clarity and immediacy.

### Pull Requests


![Screenshot 2024-09-05 174043.png](../_resources/Screenshot%202024-09-05%20174043.png)


- **Definition**: A pull request (PR) is a request to merge changes from one branch into another. It facilitates code review and collaboration.
- **Creating a Pull Request**:
  1. Click on the **"Pull requests"** tab in your repository.
  2. Select **"New pull request."**
  3. Choose the branch you want to merge from in the compare box.
  4. Review the changes to ensure they are correct.
  5. Add a title and description to provide context about the changes.
  6. Click **"Create pull request."**
  - **Example**: A developer creates a PR titled "Add payment gateway integration" to merge changes from the `feature/payment-integration` branch into the main branch.

- **Approval Process**:
  - Pull requests require approval from one or more users before merging.
  - The approver can be the author of the changes or another team member.
  - GitHub automatically creates a pull request if changes are made on a branch that the user does not own, facilitating collaboration.
  - Log files are immutable, allowing tracking of who approved the merge. This means you can always see who made changes and who approved them.

### Mging Pull Requests


![Screenshot 2024-09-05 174258.png](../_resources/Screenshot%202024-09-05%20174258.png)



![Screenshot 2024-09-05 174359.png](../_resources/Screenshot%202024-09-05%20174359.png)


- To merge the committed code changes into the main branch:
  1. Navigate to the pull request you created.
  2. Click **"Merge pull request."**
  3. Confirm the merge by clicking **"Confirm merge."**
  - This action integrates the changes from the branch into the main codebase.
  - **Example**: After reviewing the changes and ensuring they are correct, a team leader merges the `feature/payment-integration` branch into the main branch, making the new feature live.

### Deleting Obsolete Branches
- Once all changes for a branch are complete and merged, that branch becomes obsolete and should be deleted to maintain a clean repository.
- Deleting branches helps prevent confusion and keeps the project organized.
- **Example**: After merging `feature/payment-integration`, the developer deletes the branch to keep the repository tidy.

### Summary of Key Points


![Screenshot 2024-09-05 174542.png](../_resources/Screenshot%202024-09-05%20174542.png)


- All files in GitHub exist on a branch; every change is tracked within the context of a branch.
- The main branch contains the finished, deployable version of the code.
- Create new branches for code changes to keep development organized.
- Each new branch starts as an exact copy of the original, isolating changes until they are ready to be merged.
- Multiple branches can undergo changes simultaneously, allowing for parallel development.
- Saved changes are referred to as commits, each with a meaningful message.
- Pull requests enable other users to review and integrate proposed changes into the main branch.
- Merging requires approval and can be tracked through immutable log files.

--- 
