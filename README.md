# Git Workshop: Intro to Version Control

Welcome! This hands-on workshop is designed to help you learn version control concepts using Git and GitHub.

We'll use simple text documents to simulate real-world collaboration and explore:
- Commits
- Branching
- Merging

## Instructions

### Part 1:
1. Install `git` and verify it is working
2. Configure user information using `git config --global user.name "[firstname lastname]"`
3. Clone this repository to your laptop `git clone [url]`

### Part 2:
1. Create a new branch and name it after yourself using `git switch -c "[branch-name]"`
2. Open `mission-statement.txt`
3. Add your name and one sentence about what you are working on
4. Verify your changes using `git diff`
5. Add your changes to the staging area using `git add [file]`
6. Commit your changes adding a useful message using `git commit -m "[commit-message]"`
7. Verify your commit using `git log --oneline`
8. Push your changes with `git push`
9. Open a pull request on GitHub

### Part 3:
1. Switch back to the `main` branch using `git switch main`
2. Pull latest changes from GitHub using `git fetch`
3. Merge the latest changes into your local `main` branch using `git rebase` or `git merge`
4. Switch back to your personal branch using `git switch "[branch-name]"`
5. Merge the `main` branch into your personal branch using `git rebase "[branch-name]"` or `git merge "[branch-name]"`
6. Resolve potential conflicts and add your result using `git add [file]`
7. Either continue the rebase using `git rebase --continue` or add merge commit `git commit -m "[merge-message]"`
8. Push your updates to your branch with `git push`
