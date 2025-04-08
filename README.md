# 🚀 GitHub Learning Program Notes

## Week One (March 31 - April 4): Foundations of Foundations 🧱

[GitHub Community Discussion](https://github.com/orgs/community/discussions/155153)

- Introduction to Git
- Introduction to GitHub
- Introduction to GitHub’s Products

## 🌟 What is Version Control?
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

### 📌 Collaboration in GitHub
Collaboration is at the core of everything GitHub does. Repositories help organize projects and files, while pull requests keep track of changes. In addition to PRs, GitHub also supports collaboration through Issues and Discussions.

#### Issues
GitHub Issues track ideas, feedback, tasks, or bugs. They can be created from various sources: task lists, project notes, PR comments, lines of code, or URL queries.

- To create an issue from a repository:
  - Navigate to the repository's main page.
  - Select **Issues** → **New issue**.
  - Fill in the title and description fields.
  - Optionally, assign it, add to a project, or label it.
  - Click **Submit new issue**.

#### Discussions
Discussions facilitate open conversations not directly related to code, like Q&A, ideas, polls, or announcements. To enable discussions in a repository:

- Navigate to **Settings**.
- Scroll to **Features** and select **Setup discussions**.
- Customize the template for your community.
- Click **Start discussion**.

Discussions can be categorized, and each category must have a unique name and purpose, such as Announcements, General, Ideas, Polls, Q&A, or Show and Tell.

### 🌐 GitHub Platform Management
Managing notifications and subscriptions is essential for staying updated on project activities. You can subscribe to threads or receive updates on issues, PRs, CI activity, and discussions.

#### GitHub Pages
GitHub Pages allows you to host static websites directly from a repository. It takes HTML, CSS, and JavaScript files from your repo and publishes them as a website. Simply edit and push changes to keep your project site updated.

### 🌍 Distributed Version Control
Older VCSes (like CVS, SVN, Perforce) used a centralized server, risking a **single point of failure**. In contrast, **Git is distributed**:
- 🗂️ A complete project history is stored both on the client and server.
- ✈️ You can work offline and sync changes when online.
- 💾 You don’t need a server to use Git, although servers make sharing easier.

### GitHub Account Types and Plans Comparison

| Account Type | Plan               | Storage | Actions Minutes | Codespaces Core Hours | Support            | Advanced Security | Additional Features            |
|-------------|--------------------|--------|----------------|-----------------------|--------------------|------------------|--------------------------------|
| Personal    | Free               | 500 MB | 2,000          | 120                   | Community          | No               | Unlimited Repositories          |
| Personal    | Pro                | 2 GB   | 3,000          | 180                   | Email              | No               | Advanced Tools                  |
| Organization| Free               | 500 MB | 2,000          | 120                   | Community          | No               | Team Access Controls            |
| Organization| Team               | 2 GB   | 3,000          | N/A                   | Email              | No               | Draft Pull Requests             |
| Enterprise  | Enterprise Cloud   | 50 GB  | 50,000         | N/A                   | Enterprise Support | Yes              | SAML/SCIM, Managed Users        |
| Enterprise  | Enterprise Server  | N/A    | N/A            | N/A                   | Enterprise Support | Yes              | Self-Hosted                     |

# GitHub Account Types and Plans Summary

- **Personal Accounts:**
  - Free: 500 MB storage, 2,000 Actions minutes, 120 Codespaces hours, Community support
  - Pro: 2 GB storage, 3,000 Actions minutes, 180 Codespaces hours, Email support, Advanced tools

- **Organization Accounts:**
  - Free: 500 MB storage, 2,000 Actions minutes, 120 Codespaces hours, Community support, Team access controls
  - Team: 2 GB storage, 3,000 Actions minutes, Email support, Draft pull requests

- **Enterprise Accounts:**
  - Cloud: 50 GB storage, 50,000 Actions minutes, Enterprise support, Advanced security, Managed users
  - Server: Self-hosted, Enterprise support, Advanced security



---

## Week Two (April 7 - 11): Copilot 🧑‍✈️
- Introduction to GitHub Copilot
- Using GitHub Copilot with Python

## GitHub Copilot: Revolutionizing Software Development

### AI Impact on Development
- AI is transforming the technology landscape, boosting productivity for developers.
- GitHub Copilot acts as an AI pair programmer, enhancing collaboration, development, testing, and shipping.

#### Productivity Boost:
- Research by GitHub and Microsoft:
  - 46% of new code is now written by AI.
  - 55% faster developer productivity.
  - 74% of developers feel more focused.

#### Technology Behind Copilot:
- Developed by Microsoft and OpenAI.
- Powered by OpenAI Codex with extensive code knowledge.
- Available as an extension for:
  - VS Code
  - Visual Studio
  - Vim/Neovim
  - JetBrains IDEs

### Key Features of GitHub Copilot

- **Copilot for Chat:**
  - Integrated with IDEs like VS Code.
  - Chat interface similar to ChatGPT.
  - Analyzes code, error messages, and suggests fixes.

- **Copilot for Pull Requests:**
  - Uses GPT-4 for AI-powered tags.
  - Automatically fills tags based on code changes.

- **Copilot for the CLI:**
  - Assists with command composition and syntax.

### Subscription Plans

- **GitHub Copilot Free:**
  - For individual developers at no cost.
  - Includes:
    - 2,000 code completions/month
    - 50 chat requests/month
    - Access to GPT-4o and Claude 3.5 Sonnet models

- **GitHub Copilot Business:**
  - For organizations with enhanced productivity and security.
  - Includes:
    - Code completions and chat in IDE/mobile
    - Security vulnerability filter
    - Code referencing and IP indemnity

- **GitHub Copilot Enterprise:**
  - For large organizations via GitHub Enterprise Cloud.
  - Includes all Business features plus:
    - Personalized suggestions based on private code
    - Deeper codebase indexing for custom completions

---

### Setting Up GitHub Copilot

#### Sign Up for GitHub Copilot:
1. Go to your GitHub profile photo > **Settings**.
2. Select **Copilot** from the left menu under **Code, planning, and automation**.
3. Install the extension for your preferred environment (e.g., VS Code).

#### Configure GitHub Copilot in VS Code:
1. Install the **GitHub Copilot** extension from Visual Studio Marketplace.
2. Open VS Code and install the extension.
3. Sign in to GitHub when prompted.

#### Enable/Disable GitHub Copilot in VS Code:
- Bottom pane > Status icon > **Enable/Disable**.
- To disable completions:
  - Globally: **Disable completions**
  - For a specific language: **Disable completions for LANGUAGE**

#### Inline Suggestions:
- File > Preferences > Settings > Extensions > GitHub Copilot.
- Enable/Disable **Auto Completions** and specify languages.

---

### Troubleshooting GitHub Copilot

#### Log Files:
- Open command palette:
  - Mac: `Shift+Command+P`
  - Windows/Linux: `Ctrl+Shift+P`
- Enter **Developer: Open Log File** or **Developer: Open Extensions Logs Folder**.

#### Viewing Electron Logs:
- Help > **Toggle Developer Tools**.

#### Network Issues:
- Use the command palette to collect diagnostics:
  - Enter **Diagnostics** and select **GitHub Copilot: Collect Diagnostics**.


### Week Three (April 14 - 18): Repositories 📦
- Manage repository changes by using PRs on GitHub
- Search and organize repository history by using GitHub
- Maintain a secure repository by using GitHub best practices

### Week Four (April 21 - 25): GitHub Features and Open Source 🌐
- Code with GitHub Codespaces
- Manage your work with GitHub Projects
- Contribute to an open-source project on GitHub
- Communicate effectively on GitHub using Markdown

### Week Five (April 28 - May 2): Enterprise Essentials 💼
- Manage an Inner Source program by using GitHub
- Introduction to GitHub administration
- Authenticate and authorize user identities on GitHub

