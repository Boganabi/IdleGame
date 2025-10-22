# Idle Game

An idle game idea

## Some git tips

Basic commands:
- `git add .` prepares all files for committing and pushing to remote (replace the `.` with a filepath to add specific files)
- Use `git status` to see what files you are staging for commit
- `git commit -m "a message"` commits all files added with `git add`, and adds a message so you know what you are committing
- `git push -u origin branchname` pushes all files to remote that you committed with `git commit`. Your progress is now backed up! Remember to be on the branch called branchname

Any files you never want pushed to remote?
- Put their filepath into the `.gitignore` file

Branching
- Use a branch to avoid messing up someone else's work
- Create a branch with `git checkout -b branchname`
- Switch to an already existing branch with `git checkout branchname`
- Merge branches on the Github website (optional)