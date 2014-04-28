# Download a new reps from remote server

git clone XXX

# Create a new branch (feature-XXX), and set the current branch to the new one.

git checkout -b feature-quizui develop

# Commit via GitX

stage --> add commit message --> commit

# Switch to develop branch, and merge your changes

git checkout develop

git merge --no-ff feature-XXX

# Push your codes to remote server

git push origin develop

# If your local develop is out of date

git pull origin develop (fetch + merge)

# Delete a branch that is not needed

git branch -d feature-quizui

# Change Reps

git remote add name url
