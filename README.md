#### UsingGitHubRepos
Doco on how to clone / add / commit / push a GitHub repo using the "git" command on a Linux
- Rough procedure that needs to be tested \ checked

# Get copy of http URL of GitHub repo using 'Clone or Download' button.
1. On local Linux machine execute command 'git clone https://github.com/wedgetaileagle/UsingGitHubRepos.git'
2. git log
3. git status

# Add new file to Git repo
4. git add 'File Name'
# Confirm your CWD is the directory of the repo
## Use git add to add to the current git repo new files. Note that this only add the files to the local repo, not the github cloud based repo

5. git log
6. git status

# Commit updated files to the local git repo
7. git commit -a -m "Message with details of updates"
# Use git commit to save the updates to the local repo

8. git log
9. git status
# Use git status to view the differences between the local git repo and the master repo

# Push local repo to Master repo
10. git push
# Will need "MyGitHubCredentials"

11. git log
# Use to check log file for update to master repo

12. git status
# Use git status to confirm that the master repo has been synchronised with the updates to the local repo
