# Submitting a pull request

**You said:**

I want to write a blog post about how to send me feedback with a GitHub pull request.  Can you give me an overview of how to download the code from GitHub.  Read markdown files.  Use Git to commit changes to a local repo and how to push code to the remote repo in GitHub.  Can you also give me a set of references for documentation on how to use Git, GitHub, Markdown and mkdocs?  

**ChatGPT said:**

ChatGPT
Overview of the Process
1. Downloading the Code from GitHub

    Clone the Repository:
    To start working on a project, you need to download (clone) the repository to your local machine. You can do this with the following command:

```bash

    git clone https://github.com/your-username/repo-name.git
```
    Replace your-username and repo-name with the appropriate GitHub username and repository name.

2. Reading Markdown Files

    Locate Markdown Files:
    Markdown files typically have a .md extension, like README.md. You can open these files in any text editor (e.g., VSCode, Sublime Text) to read or edit them.
    View Markdown:
    Many text editors have built-in Markdown preview features, or you can use an online Markdown viewer.

3. Using Git to Commit Changes to a Local Repo

    Stage Your Changes:
    After making changes to the Markdown files (or any files in the repo), you need to stage these changes:

```bash

git add filename.md
```
If you want to stage all changed files, you can use:

```bash

git add .
```
Commit Your Changes:
After staging, commit the changes with a descriptive message:

```bash

    git commit -m "Your descriptive commit message"
```
4. Pushing Code to the Remote Repo in GitHub

    Push Your Changes:
    Once your changes are committed locally, push them to the remote repository on GitHub:

```bash

    git push origin branch-name
```
    Replace branch-name with the appropriate branch name (e.g., main, feature-branch).

5. Creating a Pull Request

    After pushing your changes to GitHub, you can create a pull request (PR) from the GitHub website by navigating to your repository, selecting the branch with your changes, and clicking the "New Pull Request" button.

References for Further Reading

    Git Documentation:
        Official Git documentation: https://git-scm.com/doc
        GitHub Learning Lab (interactive tutorials): https://lab.github.com/

    GitHub Documentation:
        Getting started with GitHub: https://docs.github.com/en/get-started
        Creating a pull request: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes/creating-a-pull-request

    Markdown Documentation:
        Markdown Guide: https://www.markdownguide.org/
        CommonMark specification: https://spec.commonmark.org/

    MkDocs Documentation:
        Official MkDocs documentation: https://www.mkdocs.org/

This overview should give you a good starting point for your blog post, and the references will help your readers dive deeper into each topic.

**You said:**

This post is going on a page that has a link to the GitHub repo.  Will you reference this option as something they can use to navigate to the source code.  This is the repo - https://github.com/bweez/Brandon-Reviews

**ChatGPT said:**

ChatGPT
Overview of the Process
1. Navigating to the Source Code

    Using the GitHub Repository Link:
    If you're reading this blog post on my site, you can navigate directly to the source code by clicking this link. This will take you to the GitHub repository where all the code is stored.

2. Downloading the Code from GitHub

    Clone the Repository:
    Once on the GitHub repository page, you can clone the repository to your local machine using the following command:

```bash

    git clone https://github.com/bweez/Brandon-Reviews.git
```
3. Reading Markdown Files

    Locate Markdown Files:
    Markdown files in the repository typically have a .md extension, like README.md. You can open these files in any text editor (e.g., VSCode, Sublime Text) to read or edit them.

4. Using Git to Commit Changes to a Local Repo

    Stage Your Changes:
    After making changes to any files, you need to stage them:

```bash

git add filename.md
```
Or stage all changes with:

```bash

git add .
```
Commit Your Changes:
Commit the staged changes with a descriptive message:

```bash

    git commit -m "Your descriptive commit message"
```
5. Pushing Code to the Remote Repo in GitHub

    Push Your Changes:
    Push your committed changes to the remote repository on GitHub:

```bash

    git push origin branch-name
```
    Replace branch-name with the appropriate branch name, such as main.

6. Creating a Pull Request

    After pushing your changes, you can create a pull request (PR) on the GitHub website. Navigate to the repository, select the branch you worked on, and click the "New Pull Request" button.

References for Further Reading

    Git Documentation:
        Official Git documentation: https://git-scm.com/doc
        GitHub Learning Lab (interactive tutorials): https://lab.github.com/

    GitHub Documentation:
        Getting started with GitHub: https://docs.github.com/en/get-started
        Creating a pull request: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes/creating-a-pull-request

    Markdown Documentation:
        Markdown Guide: https://www.markdownguide.org/
        CommonMark specification: https://spec.commonmark.org/

    MkDocs Documentation:
        Official MkDocs documentation: https://www.mkdocs.org/

This overview should guide your readers on how to contribute feedback through a GitHub pull request, and the references provide additional resources for learning.