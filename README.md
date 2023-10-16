---
author: hasp, web
topic: git, github, project management, survival
date: 2023
---

> BEWARE! Work in progress...

# Mastering ITP and SEW Projects like a Pro

## Team-Members (and Link to ProgressReports)

- [Batman](./doc/progress_reports/Batman.md)
- [Robin](./doc/progress_reports/Robin.md)

---

## Why You Need to Listen Carefully for the Next Hour

*(maybe a bit more than one hour, but we will try to keep it short...)*

#### Have you ever had the feeling some answers are missing in your life? Like the ones to the following questions...

- What do I really use my github account for?
- What the :skull_and_crossbones: :anger: :boom: :right_anger_bubble: are 
  - merge conflicts,
  - git branches, 
  - pull requests, and
  - git issues???
- How can I work with others on my coding project without going insane?
- How do I survive project management and task planning without falling into a depression?

#### THIS COURSE MIGHT GIVE YOU SOME ANSWERS TO QUESTIONS YOU NEVER EVEN DARED TO ASK!

To "freshen up"  you might want to look at: [Git Handbook · GitHub Guides](https://guides.github.com/introduction/git-handbook/) - or not...

---

## Step 0 to a Better Life - Structuring your Repository

A file and folder structure to feel secure and find your way around:

```
[root repo folder]
  |
  + [.git] // folder - contains all infos our version system needs (do NOT delete)
  + .gitignore // always needed - content depends on programming tools/language
  + README.md // you always need that one!
  + [doc] // folder - containing detailed project documentation
  |   |
  |   + [progress_reports] // folder containing your status reports
  |                        // optional - only if you dont use "github projects"
  + [src] // folder - containg your source code
```

For`.gitignore`-creation see [gitignore.io - Create Useful .gitignore Files For Your Project (toptal.com)](https://www.toptal.com/developers/gitignore). 

---

## Step 1 to a Better Life - Mastering README.md

The `readme.md` is the entry-point for every  visitor to your repository (repo). It needs to contain all necessary information for the "user" to get an idea what is going on here. So add:

- a "catching" title
- what is the goal of this project (short explanation)
- who is working on this project
- a detailed explanation of the project 
- how to install/build and run the code/project
- [optional] what hardware is used/needed and how to set it up

### Information is Everything!

- A guide from github: [Documenting your projects on GitHub · GitHub Guides](https://guides.github.com/features/wikis/) (stop reading when explanation of wiki-pages starts - we don't need those)

- For additional Information (**especially concerning ITP projects at litec**)  see [Projektdokumentation auf Github](./doc/Projektdokumentation_auf_GitHub.md).  (Sadly in German, but we hope you can live with that.)
- **No idea what `md` (markdown) is? See [Mastering Markdown · GitHub Guides](https://guides.github.com/features/mastering-markdown/).**

---

##  Step 2 to a Better Life - Branching

Some citations:

> **"It's a.... it's a TREE!" :deciduous_tree: **
>
> (*source: unknown*)

> **"Don't your f...ing dare to mess up my code!"  **
>
> (*source: EVERY programmer working within a team*)

Branching is an essential skill every versioning tool user has to learn some day, and... today is YOUR day!

So, let's get started:

- We will fall astray and have a look at the github-competition: [Git Branch | Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/using-branches), 
  - maybe also have a look at the following tutorials: `checkout` and `merge`...

- Detailed information (if you really want to know): [Git - Branches in a Nutshell (git-scm.com)](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)
- Now. let's have a look at the github workflow: [Understanding the GitHub flow · GitHub Guides](https://guides.github.com/introduction/flow/)
- Step By Step: [How to Create a Pull Request on Github: 15 Steps (with Pictures) (wikihow.com)](https://www.wikihow.com/Create-a-Pull-Request-on-Github)

### A Small Cheat-Sheet for the CommandLine-User in You

- Clone the project
- `cd` into that project
- Create a new branch with `git branch my-improvements`
- Use that branch with `git checkout my-improvements`
- Make all the changes you want
- When you’re finished, use `git add ` and `git commit` as usual
- Switch back to `master` (or `main`) with `git checkout master`
- Push the changes back to Github with `git push origin my-improvements`
- Go to the link git gives you to complete the pull request process

Source: [How-to: Steps to create a Github pull request (git branch, etc.) | alvinalexander.com](https://alvinalexander.com/git/how-to-create-pull-request-on-github-notes-steps/)

---

## Step 3 to a Better Life - Resolving Merge Conflicts

Let's assume:

- you and your best pal (or greatest enemy/villain) were working on the same sourcecode-file (*by the way - why would you do that???*),

- you finished your work and want to push your new code to the github repo.

  -  It all starts with a small message: your local repo is behind the github main branch, so you need to pull the latest version from the githubserver.
  - You do that, and **BAM!** :boom:- your best pal (or villain) already pushed his version of the file to the server, so now you have a **MERGE CONFLICT!!!** 

- What to do now? Ask for example: [Git merge conflicts | Atlassian Git Tutorial](https://www.atlassian.com/git/tutorials/using-branches/merge-conflicts)

- Most importantly search your file for the following patterns and choose wisely which part to keep:

  ```
  <<<<<<< HEAD
  ...
  =======
  ...
  >>>>>>> <some text>
  ```

---

## Step 4 to ... (*you know the drill...*) - Project Management with GitHub

[Project management, made simple (github.com)](https://github.com/features/project-management)

Working together we will use:

- ISSUES - see [Mastering Issues · GitHub Guides](https://guides.github.com/features/issues/)
- PULL REQUESTS - see above (we already talked about that)
  - Combination: [Linking a pull request to an issue - GitHub Docs](https://docs.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue)
- *Aaaaaaand finally*:  git PROJECTS - [About project boards - GitHub Docs](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)

> :warning: As already mentioned... work in progress :construction:

- Have a look around at this repo (especially the `progress_reports` and `src` folder)

---

## Useful Links

- markdown Emojis: 
  - [ikatyang/emoji-cheat-sheet: A markdown version emoji cheat sheet (github.com)](https://github.com/ikatyang/emoji-cheat-sheet)
  - [Complete list of github markdown emoji markup](https://gist.github.com/rxaviers/7360908)









