# Exercise Files for Learning GitHub Actions

The exercise files are located in folders named to match the chapter and lesson they accompany.

- *PREREQUSITES: You'll need to have the `git` command line tool installed for your system and access to a terminal program like [GitBash](https://gitforwindows.org/) on Windows or [iTerm2](https://www.iterm2.com/) on macOS.  The default terminal program for your system will work as well as long as the git program is in your PATH.*

## Using Exercise Files with Repositories

Follow these steps if you want to use the exercise files the same way they are used within the course.

We'll use the exercise files from Chapter 1, Lesson 1 for this example.

- Create a repository on GitHub using the [New Repository](https://github.com/new) page.  Name it something that relates to the lesson like `ch01-01-01`.

- Download the exercise files and unzip the archive.  If you are reading this, you have most likely completed this step! :D

- Open a terminal window and change directories to the location where you unzipped archive.  "CD" into the directory with the lesson you want to work with; for this example, we'll use Ch01/01_01.

        cd Ch01/01_01

- Run the following commands to initialize the directory as a git repository.

        git init
        git add .
        git commit -m 'first check in'

- Now add the new repository you created as a remote for the local repo.

        git remote add origin git@github.com:YOUR_GITHUB_USER_NAME_HERE/ch01-01-01.git

- After the remote is added, push the files to the remote.

        git push -u origin master

 - Browse to the repository on GitHub.com and reload the page to confirm the files have been properly pushed.

Once the files are hosted on GitHub.com, you're ready to start making changes locally and pushing them to the remote repo.
"# lesson-01-01" 
"# github-action" 









# github-action

This repository is designed to help you learn about GitHub Actions and related automation concepts. The repo is structured into chapters, each focusing on different aspects and practical exercises of GitHub Actions.

## Repository Structure

- `.github/`  
  Contains GitHub-specific configuration files, such as workflows and actions definitions. These files are essential for automating tasks, running CI/CD pipelines, and customizing repository behaviors.

- `Ch01/`  
  The first chapter is broken down into subfolders:
  - [`01_01`](https://github.com/TharushaZebra/github-action/tree/main/Ch01/01_01): Contains introductory examples or exercises.
  - [`01_02`](https://github.com/TharushaZebra/github-action/tree/main/Ch01/01_02): Continues with additional tasks or concepts for beginners.
  - [`README.md`](https://github.com/TharushaZebra/github-action/blob/main/Ch01/README.md): Explains the content and objectives of Chapter 1.

- `Ch02/`  
  The second chapter dives deeper:
  - [`02_01`](https://github.com/TharushaZebra/github-action/tree/main/Ch02/02_01): Intermediate exercises or workflows.
  - [`02_02`](https://github.com/TharushaZebra/github-action/tree/main/Ch02/02_02): Additional automation concepts.
  - [`README.md`](https://github.com/TharushaZebra/github-action/blob/main/Ch02/README.md): Describes Chapter 2’s focus.

- `Ch03/`  
  This chapter expands the learning with more complex examples:
  - [`03_01`](https://github.com/TharushaZebra/github-action/tree/main/Ch03/03_01)  
  - [`03_03`](https://github.com/TharushaZebra/github-action/tree/main/Ch03/03_03)
  - [`03_04`](https://github.com/TharushaZebra/github-action/tree/main/Ch03/03_04)
  - [`03_05`](https://github.com/TharushaZebra/github-action/tree/main/Ch03/03_05)
  - [`03_06`](https://github.com/TharushaZebra/github-action/tree/main/Ch03/03_06)
  - [`README.md`](https://github.com/TharushaZebra/github-action/blob/main/Ch03/README.md): Overview of Chapter 3.

- `Ch04/`  
  Advanced topics and workflows:
  - Subfolders from [`04_01`](https://github.com/TharushaZebra/github-action/tree/main/Ch04/04_01) to [`04_06`](https://github.com/TharushaZebra/github-action/tree/main/Ch04/04_06) cover specialized actions and advanced CI/CD.
  - [`README.md`](https://github.com/TharushaZebra/github-action/blob/main/Ch04/README.md): Details about advanced workflows.

- `Ch05/`  
  Final chapter with comprehensive exercises:
  - Subfolders from [`05_04`](https://github.com/TharushaZebra/github-action/tree/main/Ch05/05_04) to [`05_12`](https://github.com/TharushaZebra/github-action/tree/main/Ch05/05_12) present practical, real-world scenarios.
  - [`README.md`](https://github.com/TharushaZebra/github-action/blob/main/Ch05/README.md): Wraps up the chapter and gives directions for further learning.

- `actions-cheat-sheet.pdf`  
  A useful reference document summarizing key GitHub Actions commands, syntax, and best practices.

## Languages Used

- Python (43.1%)
- Makefile (23%)
- Shell (14.9%)
- Dockerfile (14.6%)
- Go (4.4%)

## Getting Started

1. Explore each chapter in order, starting from `Ch01`.
2. Read the README in each chapter for guidance.
3. Check the `.github` folder for workflow examples.
4. Refer to the `actions-cheat-sheet.pdf` for quick help.

## Purpose

This repository is ideal for developers looking to learn or teach GitHub Actions step by step, with hands-on exercises and structured progression.

