# Homework 2 — Part 2 Submission

Student name: Estefany Pena

GitHub username: estefanypena06

## 1. Git Command Observations

| Command or workflow | What did you observe? | What was the user trying to accomplish? | What problem or risk did it address? |
|---|---|---|---|
| 1. | git status | I observed the listed modified and untracked files, and which changes were staged and unstaged |  I was trying to get a picture of what was changed before deciding what to do next | It fixed the problem of forgetting what was edited or assuming that everything was in perfect working order |

| 2. | git diff  | It displays line by line changes for unstaged changes | verifying exactly what content changed, not just which files were touched |it fixed the problem of committing unintended edits, and it allows me to double check work before finalizing |

| 3. | git commit -m “message” | It creates a permanent snapshot of staged changes   | It saves a version of the work that can be identified and returned to later |  it addressed the issue of losing work and having no record of what changed or why |

| 4. | git log --oneline -3 | This displays the three most recent commits, each with short ID and its commit message | allows for reviewing of recent project history to confirm what has been saved and in what order |It solves the problem of losing track of progress over time and being unable to locate a specific prior version or explain what changed between saves. |



## 2. User Needs

### UN-GIT-01 — Short descriptive title

> A student developer needs a way to see which parts of their project have changed since the last changed version, because losing track of edits made during a project runs the risk of saving incomplete or unintended work

### UN-GIT-02 — Short descriptive title

> A student developer needs a way to choose exactly which changes are included in a saved version, because unrelated or unfinished edits should not be bundled into one single version

### UN-GIT-03 — Short descriptive title

> A student developer needs a way to review a chronological record of saved versions and their descriptions, because they need to be able to locate specific past work and understand how the project has evolved over time

## 3. User Requirements

| ID and short title | User requirement | Source user need | Rationale |
|---|---|---|---|
| UR-GIT-01  - View Changed content |  A student developer shall be able to view a summary of everything that has been changed in their project at any time | UN-GIT-_01_ | lets the user assess the current state before deciding what to do next |
| UR-GIT-02  - Inspect exact changes | A student developer shall be able to view the specific changes for any changed file before saving it | UN-GIT-_01__ |  Confirms the exact change, not just the file that was touched, preventing the saving of unintentional edits |
| UR-GIT-03 - Select changes for saving | A student developer shall be able to choose which specific changes to include in a saved version, without including unfinished edits | UN-GIT-_02__ | keeps each saved version focused on one purpose, instead of mixing unrelated changes together  |
| UR-GIT-04  - Review saved version history | A student developer shall be able to view a list of previously saved versions, each with its own description | UN-GIT-__03_ | Allows the user to locate specific past work and understand how the project has evolved over time  |

