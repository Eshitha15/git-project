# Conflict Resolution Report

**Branches involved:** feature-A, feature-B → merged to main  
**File with conflict:** README.md

**What caused the conflict:**
Both feature-A and feature-B modified the same line in README.md.

**Resolution (UI):**
1. Opened PR: feature-B → main.
2. Clicked "Resolve conflicts" on the PR.
3. Edited the conflict block and replaced it with:
   HELLO FROM FEATURE A AND FEATURE B — conflict resolved.
4. Clicked "Mark as resolved" and then "Commit merge".
5. Merged the PR into main.

**Final README.md (excerpt):**
HELLO FROM FEATURE A AND FEATURE B — conflict resolved.

**Verification:**
- PR: (link to the PR)
- Commit: (commit hash shown in the PR)
