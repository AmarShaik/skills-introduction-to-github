# GitHub Foundations Certification Guide  
## Domain 1: Introduction to Git and GitHub

### Git and GitHub Basics

- **Describe version control**  
  A system that tracks changes to files over time and allows developers to collaborate and revert to previous states.

- **Define distributed version control**  
  Each contributor has a full copy of the repository and its history, enabling offline work and parallel development.

- **Describe Git**  
  A distributed version control system used to manage and track changes in source code.

- **Describe GitHub**  
  A cloud-based platform built around Git, offering tools for collaboration, pull requests, issues, and more.

- **Explain the difference between Git and GitHub**  
  Git is a tool for version control; GitHub is a platform for hosting and collaborating on Git repositories.

- **Describe a GitHub repository**  
  A project space containing files, commit history, branches, and collaboration features.

- **Describe a commit**  
  A snapshot of changes made to the repository, typically accompanied by a message explaining the changes.

- **Describe branching**  
  A way to work on different versions of a project independently from the main codebase.

- **Define a remote in Git terminology**  
  A remote is a hosted version of your repository (e.g., on GitHub) you can push to or pull from.

- **Describe the GitHub flow**  
  A lightweight workflow: create a branch → commit changes → open pull request → review → merge.

---

### GitHub Entities

- **Describe the different GitHub accounts**  
  - **Personal**: Individual account for users  
  - **Organization**: Shared account for teams  
  - **Enterprise**: Advanced account for large-scale business needs

- **Describe GitHub’s products for personal accounts**  
  - **Free**: Unlimited repos, community support  
  - **Pro**: Advanced features, Copilot, insights

- **Describe GitHub’s products for organizations**  
  - **Free for orgs**: Basic collaboration  
  - **Team**: Access control, advanced tools

- **Describe GitHub Enterprise deployment options**  
  - **Enterprise Cloud**: GitHub-hosted  
  - **Enterprise Server**: Self-hosted  
  - **GitHub AE**: Advanced compliance

- **Describe user profile features**  
  Includes bio, location, achievements, profile README, pinned repos, followers, stars.

---

### GitHub Markdown

- **Identify the text formatting toolbar**  
  Located above the comment box in issues and PRs; used for styling text.

- **Describe Markdown**  
  A lightweight markup language for formatting text using plain text symbols.

- **Identify basic formatting syntax**  
  - Headings: `# Heading`  
  - Bold: `**text**`  
  - Italic: `_text_`  
  - Links: `[text](url)`  
  - Lists: `- item`  
  - Task list: `- [ ]`  
  - Comments: `<!-- comment -->`

- **Explain where to use slash commands**  
  In issues, PRs, and discussions to trigger GitHub Actions (e.g., `/assign`, `/close`).

---

### GitHub Desktop

- **Difference between GitHub Desktop and github.com**  
  GitHub Desktop is a local app for managing repositories; github.com is the web platform.

- **Available features in GitHub Desktop**  
  Clone, push, pull, view changes, manage branches, and commit—all through a GUI.

---

### GitHub Mobile

- **Features of GitHub Mobile**  
  View issues/PRs, comment, merge PRs, manage notifications, assign issues.

- **Manage notifications in the app**  
  Use push settings, mute threads, and access inbox to manage activity on the go.

---
---
## Domain 2: Working with GitHub Repositories

### Understanding GitHub Repositories

- **Describe the components of a good README and recommended repository files**  
  A good README includes project description, setup instructions, usage, and contribution guidelines. Key files include:
  - `LICENSE`: Defines legal use of the code.
  - `CONTRIBUTING`: Guidelines for contributors.
  - `CODEOWNERS`: Specifies default code reviewers.

- **Explain basic repository navigation**  
  Users can navigate code, commits, branches, issues, pull requests, and settings through the repo’s tabs on GitHub.

- **Explain how to create a new repository**  
  Click "New" under the Repositories tab, choose a name, select visibility, and initialize with a README if needed.

- **Describe repository templates**  
  Templates allow you to create a new repository with pre-defined files, structure, and settings.

- **Describe the different features to maintaining a repository**  
  Includes branching, issues, PRs, labels, discussions, actions, insights, and wikis.

- **Describe how to clone a repository**  
  Use `git clone <URL>` to copy a repository locally. You can also use GitHub Desktop or the Code dropdown.

- **Describe how to create a new branch**  
  Use GitHub UI or `git checkout -b <branch-name>` to create and switch to a new branch.

- **Explain how to add files to a repository**  
  Add files via upload on GitHub, through GitHub Desktop, or using `git add`, `commit`, and `push`.

- **Identify how to view repository insights**  
  The “Insights” tab shows traffic, contributors, commits, and community standards.

- **Explain how to save a repository with stars**  
  Click the ⭐ button at the top-right of the repository page to bookmark and support it.

- **Explain feature previews**  
  GitHub occasionally offers early access to upcoming features, which can be enabled from your account settings.

---
---
## Domain 3: Collaboration Features

### Issues

- **Describe how to link a PR to an issue**  
  Use keywords like `Fixes #issue_number` or `Closes #issue_number` in the PR description to auto-link and close the issue on merge.

- **Describe how to create an issue**  
  Go to the “Issues” tab and click “New issue”; fill in the title and description.

- **Difference between issue, discussion, and pull request**  
  - **Issue**: Bug/feature/task tracker  
  - **Discussion**: Open-ended conversation  
  - **Pull Request**: Proposed code changes

- **Explain how to create a branch from an issue**  
  Use the “Create branch” option linked to the issue or do it manually using Git.

- **Identify how to assign issues**  
  Use the sidebar on an issue to assign users.

- **Describe how to search and filter issues**  
  Use filters like `is:open is:issue` or labels, milestones, and assignees in the search bar.

- **Describe how to pin an issue**  
  Organization owners/admins can pin issues to keep them at the top of the issue list.

- **Explain basic issue management**  
  Includes labeling, assigning, commenting, closing, locking, and converting to discussion or PR.

- **Difference between issue templates and issue forms**  
  - **Templates**: Markdown-based default issue formats  
  - **Forms**: Structured issue creation using YAML with dropdowns, required fields, etc.

- **Explain how to use keywords in issues**  
  Use action keywords like `fix`, `close`, `resolve` to auto-close linked issues in PRs.

---

### Pull Requests

- **Describe a pull request**  
  A request to merge code changes from one branch to another.

- **Explain how to create a new pull request**  
  Go to the “Pull Requests” tab → “New pull request” → select branches and describe the changes.

- **Describe the `base` and `compare` branches in a PR**  
  `base`: branch you want to merge into; `compare`: branch with changes.

- **Explain relationship of commits on a PR**  
  Commits are the individual changes grouped in a PR; each commit shows a snapshot of progress.

- **Describe draft pull requests**  
  Draft PRs signal work-in-progress that isn't ready for review yet.

- **Purpose of pull request tabs**  
  - **Conversation**: General discussion  
  - **Commits**: Commit list  
  - **Checks**: CI/CD results  
  - **Files changed**: File-level changes

- **Identify how to link activity in PR**  
  Mention commits, issues, or users using `#`, `@`, or commit hashes.

- **Explain different PR statuses**  
  - Open  
  - Closed  
  - Merged  
  - Draft  
  - Approved/requested changes

- **Recognize how to comment on specific lines of code**  
  In the “Files changed” tab, click the `+` beside a line to add inline comments.

- **Describe code review with a CODEOWNERS file**  
  Specifies users or teams who must review PRs to specific files or directories.

- **Options for providing a code review**  
  - **Comment**: Leave feedback  
  - **Approve**: Accept the changes  
  - **Request changes**: Ask for improvements  
  - **Suggest changes**: Propose edits directly

---

### Discussions

- **Difference between discussions and issues**  
  Discussions are for open-ended or community conversations; issues track specific work/tasks.

- **Options available in discussions**  
  - Announcements  
  - Q&A  
  - Show and Tell  
  - Polls  
  - Ideas

- **How to mark a comment as an answer**  
  Click the “Mark as answer” button on a reply in a Q&A discussion.

- **How to convert a discussion to an issue**  
  Use the “Convert to issue” option from the discussion’s sidebar or comment menu.

- **How to pin a discussion**  
  Maintainers/admins can pin discussions to appear at the top.

---

### Notifications

- **How to manage notification subscriptions**  
  Use the “Watch” button on repos and issues to set notification levels.

- **How to subscribe to notification threads**  
  Click “Subscribe” on a specific issue, PR, or discussion.

- **How to find threads where you're @mentioned**  
  Go to your Notifications page → filter by “Participating” or “Mentioned”.

- **Notification filtering options**  
  Filter by reason (mention, author, subscribed), repo, type (issue, PR), or custom labels.

- **Notification configuration options**  
  Customize delivery method (web, email, mobile) and frequency (immediate, daily digest, etc.)

---

### Gists, Wikis, and GitHub Pages

- **How to create a GitHub Gist**  
  Go to gist.github.com → create a new snippet of code/text and save it.

- **How to fork and clone a gist**  
  Click “Fork” on a gist to copy it; use `git clone` with the gist URL to download locally.

- **Explain GitHub Wiki pages**  
  A built-in documentation tool for repos with pages linked like a wiki.

- **How to create, edit, and delete wiki pages**  
  Use the Wiki tab on a repo → “New Page” to create → edit or delete using the UI.

- **Explain the visibility of wiki pages**  
  Follows repo visibility: if repo is public/private, wiki inherits that.

- **Describe GitHub Pages**  
  A feature to host static websites directly from a repo (typically from `docs/` or root).

---
---
## Domain 4: Modern Development

### GitHub Actions

- **Describe GitHub Actions (basic understanding)**  
  GitHub Actions is a CI/CD tool that automates workflows such as building, testing, and deploying code.

- **Explain where you can use GitHub Actions within GitHub (general event types)**  
  You can trigger workflows on events like `push`, `pull_request`, `issue`, `schedule`, `release`, and more.

- **Explain where you can find existing GitHub Actions**  
  You can explore prebuilt Actions in the GitHub Marketplace: [https://github.com/marketplace/actions](https://github.com/marketplace/actions)

---

### GitHub Copilot

- **Describe GitHub Copilot**  
  GitHub Copilot is an AI-powered coding assistant that suggests code and functions in real-time inside your IDE.

- **Describe the difference between Copilot for Individuals and Copilot for Business**  
  - **Individuals**: Personal use with basic completion and suggestions.  
  - **Business**: Adds team policies, usage analytics, and enterprise-level compliance.

- **Explain how to get started using GitHub Copilot**  
  Install the Copilot extension (e.g., for VS Code), sign in with GitHub, and activate the subscription.

---

### GitHub Codespaces

- **Describe GitHub Codespaces**  
  Cloud-based development environments hosted by GitHub that let you code without setting up your local machine.

- **Identify how to start a GitHub Codespace**  
  Click the **Code** dropdown in a repo → click **Codespaces** tab → **Create codespace** on the desired branch.

- **Describe the Codespace lifecycle**  
  A codespace is created, paused when idle, resumed later, and can be deleted when no longer needed.

- **Describe different customizations you can personalize with GitHub Codespaces**  
  Customize with `devcontainer.json` files to set up environment (tools, extensions, settings).

- **Recognize how to add and configure dev containers**  
  Use the **dev container specification** to define Docker-based development environments with specific tooling.

- **Identify how to share a deep link to a GitHub Codespace**  
  Use the browser URL of an active codespace session to share direct access (if permissions allow).

- **Explain how to use the github.dev editor**  
  Press `.` in a repo or use `github.dev/<user>/<repo>` to open a lightweight web-based editor.

- **Explain differences between github.dev editor and GitHub Codespaces**  
  - **github.dev**: Lightweight, no backend processing or terminals  
  - **Codespaces**: Full cloud-based development environment with terminal and compute resources

---
---
## Domain 5: Project Management

### Manage Your Work with GitHub Projects

- **Describe GitHub Projects**  
  GitHub Projects is a planning and tracking tool integrated into GitHub, used to organize issues, pull requests, and notes in a customizable view.

- **Explain the layout options for projects**  
  Projects offer layout options like table, board (Kanban-style), and roadmap views to visualize and manage tasks.

- **Describe the configuration options for projects**  
  Projects can be configured with custom fields, filters, views, and workflows to fit different team needs.

- **Explain the difference between projects and projects classic**  
  - **Projects**: Built using GitHub's flexible, spreadsheet-like views with advanced filters and workflows  
  - **Projects (classic)**: The older Kanban-style board tied to a single repo

- **Explain the use of labels**  
  Labels categorize and tag issues or pull requests, helping with filtering, prioritizing, and organizing tasks.

- **Explain the use of milestones**  
  Milestones group issues and pull requests by goals, often used to track progress toward a version or deadline.

- **Describe how to use and create template repos**  
  Repositories can be marked as templates to allow others to generate new repos with the same structure and files.

- **Explain how to create, edit, and delete saved replies**  
  Saved replies are prewritten responses that can be reused in issues and PRs. Set them up under your GitHub settings > Saved replies.

- **Describe the benefits of using a saved reply**  
  Increases efficiency and ensures consistency when responding to common questions or requests.

- **Recognize how to add assignees to issues and pull requests**  
  Use the sidebar in an issue or pull request to assign collaborators responsible for the task.

- **Explain how to use project workflows**  
  Workflows automate the movement or status of items in a project board, such as moving issues when PRs are merged.

- **Describe project insights**  
  Project insights provide visual analytics and reports about item progress, statuses, and team contributions.

---
