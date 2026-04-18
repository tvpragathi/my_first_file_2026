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

### Issue: Claude Code and Codex login failed in terminal
- Cause: Authentication failed in terminal due to environment configuration (PATH / Node.js setup) and incomplete CLI initialization.
- Solution:
  - Ensured Node.js was properly installed and added to system PATH
  - Restarted Cursor IDE after environment variable changes
  - Reopened terminal and retried login for Claude Code and Codex
  - Login succeeded after environment refresh

### Issue: Unable to push to GitHub
- Cause: Git branch or commit configuration issue (no initial commit / branch mismatch).
- Solution:
  - Added and committed files using Git
  - Ensured correct branch name (`main`)
  - Successfully pushed repository to GitHu
