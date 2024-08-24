# day-3-assignment

**Creating a New Repository:**

1. `echo "# se-assignment-day-3-environment-setup-mphats" >> README.md`: 
    - This line creates a new file called "README.md" (a markdown file) if it doesn't exist. 
    -  `echo` is a command to print text. 
    - `# se-assignment-day-3-environment-setup-mphats` is the text being printed, which likely serves as a title for the README file.
    - `>>` is the append operator, which adds the text to the end of the file.

2. `git init`: 
    - This command initializes a new Git repository in the current directory. 
    - This creates a hidden folder called ".git" which stores all the version control information.

3. `git add README.md`: 
    - This command tells Git to track the changes made to the "README.md" file. 
    - It adds the file to the staging area, which is a temporary area where you can review the changes before committing them.

4. `git commit -m "first commit"`: 
    - This command captures the changes currently in the staging area and creates a permanent snapshot of the project's state. 
    - The `-m` flag specifies a message describing the changes ("first commit" in this case).

5. `git branch -M main`: 
    - This command renames the default branch (usually named "master") to "main". 
    - The `-M` flag forces the rename if the branch already exists with changes. This seems to be a preference for using "main" instead of "master". 

6. `git remote add origin https://github.com/Powerlearnproject/se-assignment-day-3-environment-setup-mphats.git`: 
    - This command defines a remote repository hosted on GitHub. 
    -  "origin" is the name given to this remote repository for reference.
    - The URL points to the specific repository on GitHub.

7. `git push -u origin main`: 
    - This command pushes the local "main" branch to the remote repository named "origin" (defined in the previous step). 
    - The `-u` flag sets "origin" as the default upstream branch for pushing future changes.

**Pushing an Existing Repository:**

These commands assume you already have a Git repository initialized in your local directory with some changes. 

1. `git remote add origin https://github.com/Powerlearnproject/se-assignment-day-3-environment-setup-mphats.git`: (This is the same as step 6 in the first scenario)
    - Defines a remote repository on GitHub.
