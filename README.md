🔹 Steps Followed:
Created a repository named collab-practice from Account A (Vishwajeet1001).

Initialized a local Git repository, added index.html, and pushed it to GitHub.

Made an update in the same repo from the local machine and pushed the commit.

Logged in to Account B (AbhiSingh111111) and forked the collab-practice repo.

Cloned the forked repo locally, created a new branch feature-update, and made changes to README.md.

Committed and pushed the changes from Account B to its forked GitHub repo.

Created a Pull Request from Account B’s fork to Account A’s original repo.

Logged back into Account A, reviewed, and merged the pull request.

🔹 Challenges Faced:
❌ Got a permission denied error when trying to push changes from Account B.

✅ Solution: Made sure the remote URL was pointing to Account B’s fork, not Account A’s original repo.

⚠️ Git showed a CRLF vs LF line ending warning while adding files.

✅ Solution: Ignored it, since it doesn't affect functionality and is common on Windows systems.
