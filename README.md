# 🚀 GitHub Learning Program Notes

### Hi friends! 👋  
I'm starting a GitHub repo so we can collaborate on an awesome and complete set of notes.  

Feel free to Fork or create a Pull Request and PLEASE STAR! ✨

## Git and GitHub Learning Plan

- [GitHub Foundations Certification Prep Course](insert-link-here) complete with prep materials and sample questions is now live - visit the [Discussion](insert-link-here) to start your certification journey! See you there 😎

## Week One (March 31 - April 4): Foundations of Foundations 🧱
- Introduction to Git
- Introduction to GitHub
- Introduction to GitHub’s Products

## 🚀 Introduction to Git

### 🌟 What is Version Control?
Version Control Systems (VCS) are programs that track changes to a collection of files. The main goals of a VCS are:

- 🔄 Easily recall earlier versions of individual files or the entire project.
- 👥 Enable collaboration between team members, even on the same files, without interfering with each other’s work.

Also known as **Software Configuration Management (SCM)**, a VCS can be used for more than just software, including books and tutorials.

### 📝 Version Control
- A crucial development practice to track changes and revisions made by multiple developers working on the same project.

## 💡 Key Benefits of VCS:
- 📝 Track changes made to your project (when and by whom).
- 🗒️ Attach a message to each change to explain why it was made.
- 🔙 Retrieve previous versions of files or the whole project.
- 🌿 Create branches for experimental changes, which can be merged later.
- 🏷️ Tag versions, e.g., marking a new release.

## 🐙 Git: A Powerful VCS
Git is:
- ⚡ Fast
- 💪 Versatile
- 📏 Highly scalable
- 💸 Free and open-source

### 🌐 Git: The Most Popular VCS!
- ✅ A **distributed version control system** that allows multiple copies of a project to remain synchronized and up-to-date.
- 🌐 **GitHub** is a cloud-based platform that works hand in hand with Git, serving as a remote repo.
- 💼 Other features:
  - 👥 Collaboration
  - 📂 Management
  - 🤖 Automation
  - 📜 Revision
  - 🌟 Showcasing

#### 📌 Tracking Changes
- **Commits** are like snapshots of our code at specific points in time.
  - Each commit has a unique hash capturing changes.
  - **Branches** are chains of linked commits, allowing for multiple branches at a time to work on different features while keeping the main branch stable.
  - **GitHub Flow** - A lightweight, branch-based workflow that supports continuous deployment.

#### 🗂️ Commands Used
- `git --version` - Check the installed version of Git.
- `git config --global user.name "<username>"` - Set the global username for Git commits.
- `git config --global user.email "<email@example.com>"` - Set the global email for Git commits.
- `git config --list` - View the current Git configuration.
- `mkdir <directory_name>` - Create a new directory.
- `cd <directory_name>` - Change to the specified directory.
- `git init --initial-branch=main` - Initialize a new Git repository with the main branch.
- `git status` - Show the current status of the working directory.
- `ls` - List files and directories in the current location.
- `git --help` - Show help for Git commands.

#### 🗃️ Basic Git Commands
- `git status` - Check the status of your working tree and staging area.
- `git add <file>` - Stage changes for commit (move to the staging area).
- `git commit -m "message"` - Save staged changes as a new version (commit).
- `git log` - View the history of commits.
- `git help` - Access help for Git commands. Use `git <command> --help` for specific commands.

#### 👤 GitHub Accounts
1. Personal - General, customizable with a profile picture, bio, followers, and pinned repositories.
2. Organization - Group accounts to manage projects, grant permissions, and collaborate.
3. Enterprise - Professional accounts for companies, managing policies, administration, and billing.
   - 🛠️ Benefits: Support, action minutes, codespace core-hours, package storage, security features, deployment features, and access control features.

#### 📝 Markdown
- GitHub's primary formatting syntax for documentation.

#### 📱 GitHub Mobile
- Triage, manage notifications, review issues, PRs, and enable multi-factor authentication (MFA).

#### 💻 GitHub Desktop
- Git-based actions for local work, syncing, and managing repositories.

## 🌍 Distributed Version Control
Older VCSes (like CVS, SVN, Perforce) used a centralized server, risking a **single point of failure**. In contrast, **Git is distributed**:
- 🗂️ A complete project history is stored both on the client and server.
- ✈️ You can work offline and sync changes when online.
- 💾 You don’t need a server to use Git, although servers make sharing easier.

## 📝 Git Terminology
- **Working Tree** 🌳: The project files and folders you’re working on.
- **Repository (Repo)** 📁: Top-level directory where Git stores project history and metadata.
- **Hash** 🧮: Unique identifier for file contents, enabling change detection.
- **Object** 📦: Four types (Blob, Tree, Commit, Tag) identified by SHA-1 hash.
- **Commit** ✅: Save a version of changes, similar to committing changes to a database.
- **Branch** 🌿: A linked series of commits; the main branch is often called **main** or **master**.
- **Remote** 🌐: A reference to another Git repository, often called **origin** by default.
- **Commands and Subcommands** 💻: Git actions like `git push` and `git pull`, with options (`-` or `--`).

## 💻 Git Command Line vs. GUIs
- Many GUIs are available (e.g., GitHub Desktop), but the **Git command line** offers complete functionality.
- Developers often resort to the command line when GUIs fall short.

## 🌐 Git and GitHub
- **Git**: A distributed VCS for version control and collaboration.
- **GitHub**: A cloud platform built on top of Git, enhancing collaboration with features like:
  - 🐛 Issues
  - 💬 Discussions
  - 📂 Pull requests
  - 🔔 Notifications
  - 🏷️ Labels
  - 🛠️ Actions
  - 🍴 Forks
  - 📅 Projects

GitHub makes teamwork easier and more efficient while using Git for version control.


---

## Week Two (April 7 - 11): Copilot 🧑‍✈️
- Introduction to GitHub Copilot
- Using GitHub Copilot with Python

## Week Three (April 14 - 18): Repositories 📦
- Manage repository changes by using PRs on GitHub
- Search and organize repository history by using GitHub
- Maintain a secure repository by using GitHub best practices

## Week Four (April 21 - 25): GitHub Features and Open Source 🌐
- Code with GitHub Codespaces
- Manage your work with GitHub Projects
- Contribute to an open-source project on GitHub
- Communicate effectively on GitHub using Markdown

## Week Five (April 28 - May 2): Enterprise Essentials 💼
- Manage an Inner Source program by using GitHub
- Introduction to GitHub administration
- Authenticate and authorize user identities on GitHub
