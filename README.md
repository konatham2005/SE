# Step 1: Switch to main branch and pull latest changes
git checkout main
git pull origin main

# Step 2: Create and switch to a new branch
git checkout -b update-readme

# Step 3: Edit README.md (manually)

# Step 4: Stage and commit changes
git add README.md
git commit -m "Update README file"

# Step 5: Push new branch
git push origin update-readme

# Step 6: Create PR (manually on GitHub)

# Step 7: Delete the branch after merging (optional)
git branch -d update-readme
git push origin --delete update-readme
