\# Lab 4 — Git \& GitHub



\## Question 1

`--global` applies the Git configuration to all repositories for my Windows user account. If I leave it out, the setting applies only to the current repository when run inside one.



\## Question 2

The `.git` directory appeared in `ls -a` but not in a normal `ls` listing because it is hidden. It stores Git's repository data, including commit history and configuration.



\## Question 3

Before staging, Git listed the files that were untracked. In this new folder, there were only a small number of files, and neither `README.md` nor `.gitignore` was code written by someone else.



\## Question 4

After creating `.gitignore`, files matching its rules would no longer appear as untracked files. In our folder, there was no `.venv/` or Python cache directory, so there were no such entries to disappear.



\## Question 5

`.gitignore` should be committed because it tells Git which generated or unnecessary files to ignore. Committing it ensures that other people working on the repository use the same ignore rules.



\## Question 6

`README.md` moved from \*\*Untracked files\*\* to \*\*Changes to be committed\*\* after `git add README.md`. This means it moved from the working directory into Git's staging area.



\## Question 7

Git reported that two files changed and five insertions were made. The two files were `.gitignore` and `README.md`.



\## Question 8

The first seven characters of the commit hash are `d6d83f4`. They provide a short identifier that can be used to refer to that particular commit.



