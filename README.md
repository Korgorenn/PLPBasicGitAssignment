# PLPBasicGitAssignment
This is for my software engineering assignment.
The steps the commands I used for this assignments are
# Navigate to your local repository
cd path/to/PLPBasicGitAssignment

# Initialize a new Git repository
git init

# Add the remote URL of your GitHub repository
git remote add origin https://github.com/your-username/PLPBasicGitAssignment.git

# Create a new text file with a simple message
navigate Inside your local folder, create a new text file  `hello.txt`

  - Add a simple text message  "Hello, Git!"

# Stage the new file
git add hello.txt

# Commit the new file
git commit -m "Add hello.txt with a greeting"

# Fetch and merge remote changes
git pull origin main --allow-unrelated-histories

# Save and close the editor if prompted (follow the instructions for your editor)

# Push the changes to GitHub
git push -u origin main
