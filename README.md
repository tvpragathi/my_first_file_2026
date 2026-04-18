# Cursor Setup Assignment

## Tools Installed
- Cursor IDE
- Claude Code Extension
- Codex Extension
- Node.js
- Git

## Steps Completed 
1. Installed Cursor IDE
2. Installed Node.js
3. Installed Git
4. Opened Cursor IDE
5. Installed Claude Code extension from Extensions tab
6. Installed Codex extension from Extensions tab
7. Fixed PATH environment variable issue (for Node.js)
8. Logged into both extensions successfully
9. Created a public GitHub repository
10. Cloned the repository into Cursor IDE
11. Created README.md file
12. Added project details
13. Committed changes using Source Control
14. Pushed the repository to GitHub

## Issues Faced & Solutions

### Issue 1: Extension login failed in terminal (Claude Code & Codex)
- Cause: Node.js was not properly detected due to PATH environment variable misconfiguration.
- Solution:
  - Installed Node.js and configured PATH correctly
  - Restarted Cursor IDE
  - Retried login successfully after environment refresh

### Issue 2: Git push error (src refspec main does not match any)
- Cause: No initial commit was created in the repository.
- Solution:
  - Added project files using `git add .`
  - Created first commit using `git commit -m "Initial commit"`
  - Pushed successfully using `git push -u origin main`

### Issue 3: Pathspec error while adding files
- Cause: Files were not present in the correct directory or not created properly.
- Solution:
  - Created/added files inside the correct project folder
  - Verified using `git status`
  - Added files again successfully using `git add .`
