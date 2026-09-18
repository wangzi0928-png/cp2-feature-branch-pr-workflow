# Checkpoint 2 Submission

Name:Bhavin
GitHub Username:wangzi0928-png
Required Branch:cp2-wangzi0928-png
Pull Request Number:

## Commands Used

Write the commands you used, one per line, in the order you used them.
git clone https://github.com/wangzi0928-png/cp2-feature-branch-pr-workflow .
git branch cp2-wangzi0928-png
git switch cp2-wangzi0928-png
git status
git add .
git commit -m "answer"
git push origin -u cp2-wangzi0928-png

```text

```

## Question 1 — Branch Safety

Why should you avoid doing this checkpoint directly on `main`?

Answer: If there is no independent check in the branch, operating directly on the main branch may directly compromise the stability of the project and make it impossible to track historical versions

## Question 2 — Stage vs Commit

What is the difference between `git add` and `git commit`?

Answer: Git add is to prepare your changes and move to that file, and git commit is to complete the changes to a checkpoint in the project's history.

## Question 3 — Commit vs Push vs Pull Request

Explain what changes when you commit locally, when you push the branch, and when you open a Pull Request.

Answer:A commit records changes to one or more files in your branch locally. Push the branch updates branches, tags, or other references in remote repositories from your local repository, and sends all necessary data that isn’t already on the remote. And once the repository maintainer has approved a pull request, the developer's new updates in the forked repository are merged with the main project repository.

## Reflection

What Git command or checkpoint helped you understand the repository state most clearly, and why?

Answer: It is git status, it will command informs you about what has changed in your local repository checkout compared to the moment you first checked it out or last did an update via git pull. It does not compare it to the contents of the Git server.
