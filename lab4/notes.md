### Question 1

Using `--global` applies the setting across all Git repositories on my computer so I don't have to re-type it. If I leave it out, it only applies to the current project.

### Question 2

Running `ls -a` showed the `.git` folder, which was hidden before because it starts with a dot. Inside, Git stores all the internal files, settings, and commit history fo	r this project.

### Question 3

Git listed around dozens of untracked files and folders. The `.venv` folder definitely wasn't something I wrote since it contains Python package dependencies.

### Question 4

The `.venv`, `__pycache__`, `*.pyc`, and `.DS_Store` files disappeared from the untracked list. Git is now ignoring them like we told it to.

### Question 5

Yes, `.gitignore` should definitely be committed. That way, anyone else working on the project shares the same rules for ignoring junk files.

### Question 6

`README.md` moved from "Untracked files" to "Changes to be committed". Running `git add` moved it from my working folder into the staging area.

### Question 7

Git showed a brief summary with the commit hash, commit message, and changed files. It listed the exact count of files recorded into the local commit.

### Question 8

They are the short version of the commit hash, which acts as a unique ID for that specific commit.

### Question 9

The four steps are making your edits, staging them with `git add`, committing them with `git commit`, and repeating as you keep working.

### Question 10

It has a special name because sites like GitHub automatically display `README.md` on the main repo page to give people an overview of the project.

### Question 11

`gh auth login` saved an authentication token on my system so GitHub knows who I am without asking for my password every time I push.

### Question 12

`README.md` shows up on the front page because GitHub automatically picks it up and renders it as the main homepage for the repository.

### Question 13

No, running `git push` just uploaded a copy of my commits to GitHub. It didn't alter my local history at all.

### Question 14

A private repo exists online on GitHub, but only authorized people can see it. A non-existent repo isn't uploaded anywhere, so there's no online version or backup at all.
