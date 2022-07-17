# Challenge 1.3 - Git Workflow

<details>
<summary>🧰 Before you begin</summary>

* Check out the detailed setup guide [here](/Setup/readme.md)
* Every challenge is dependent on the previous challenges, make sure you work through them in order
* Don't leave your team mates behind! See if anyone else needs a hand before you start a new challenge
</details>

## Overview

In a basic git workflow you work through the following steps:
1. Create a branch for your work in progress (done)
2. Clone the remote branch (in Azure Repos) to make a local copy of it (this challenge)
3. Stage and commit your work as you complete it (this challenge)
4. Push your work to the remote branch to back it up and collaborate with others (this challenge)
5. Create a Pull Request/Merge Request to request your changes be deployed to production (next challenge)

Your challenge is to create a local copy of your feature branch, update the readme file, commit and push your changes. Once you have finished this challenge you will have an understanding of:
* How to clone a remote git branch to create a local copy
* How to stage and commit files
* How to push your changes to a remote branch

## Objectives

1. Clone the remote feature branch to your local computer with `git clone`

    <details>
    <summary>💡 Tips and Tricks</summary>
    <ul>
        <li>Ensure your branch is selected on Repos page of your Azure DevOps project and click <b>Clone</b></li>
        <li>Copy the URL</li>
        <li>Open the vscode command palette with Ctrl + Shift + P.</li>
        <li>Type: git clone <em>&lt;url&gt;</em> and press enter</li>
        <li>Select a local location for the git repository</li>
    </ul>
    </details>
    <br>

2. Check which branch you are currently working in with `git branch`

    
    <details>
    <summary>💡 Tips and Tricks</summary>

     * git-branch <a href="https://git-scm.com/docs/git-branch">documentation</a>
    </details>
    <br>

3. Switch to your feature branch with `git checkout <your feature branch name>`

    <details>
    <summary>💡 Tips and Tricks</summary>

     * git-checkout <a href="https://git-scm.com/docs/git-checkout">documentation</a>
    </details>
    <br>

3. Update the readme file locally by adding your name to a new heading called `Contributors`. Add your name as a contributor in an unordered list (bullet points). You can remove all the other content. **Save** the file.

    <details>
    <summary>💡 Tips and Tricks</summary>

     * Use markdown to format your readme file. Markdown is a set of rules that formats text on webpages, it allows you to easily format a page like the readme file.
     * Markdown syntax <a href="https://www.markdownguide.org/basic-syntax#headings">Headings</a> and <a href="https://www.markdownguide.org/basic-syntax#lists-1">Lists</a>

    </details>
    <br>

4. Stage your changes with `git add`

    <details>
    <summary>💡 Tips and Tricks</summary>
    <ul>
        <li>You can stage all of your files with <code>git add .</code> or stage individual files with <code>git add &lt;filename&gt;</code></li>
        <li>If you skip this step, VS Code will ask you if you want to stage your changes when you run <code>git commit</code>. So you might not end up running <code>git add</code> too often in the real world, but it's an important step to know, because you need to <b>stage</b> your changes before you can <b>commit</b> them
        </li>
    </ul>
    </details>
    <br>

5. Commit your changes with `git commit`

    <details>
    <summary>💡 Tips and Tricks</summary>
    <ul>
        <li>You can stage all of your files with <code>git add .</code> or stage individual files with <code>git add &lt;filename&gt;</code></li>
    </ul>
    </details>
    <br>

6. Push your work from the **local** branch to the **remote** branch with `git push`

    <details>
    <summary>💡 Tips and Tricks</summary>

     * git-push <a href="https://git-scm.com/docs/git-push">documentation</a>
    </details>
    <br>

## Success Criteria

You will have an updated readme file in the remote branch with a **Contributors** section.

[< Previous Challenge](../1.2/readme.md) | [Next Challenge >](../1.4/readme.md)