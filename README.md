# Git commands helpful, cheat sheet

Short description
Who is author, why created, what tasks he performs, what problems it closes and solves

```bash
# Home directory
~

# Show actual path
pwd

# Change directory
cd ~

# Show everything in the actual directory
ls

# Open file
cat name_file.enlargement

# Create file
touch name_file.enlargement

# Make, Create directory
mkdir name_directory

# Remove file
rm name_file.enlargement

# Remove directory
rmdir name_directory
```

## Git Hash SSH-1

```bash

# Logs hash commit all
git log

# Logs hash commit short
git log --oneline
```

### Status files in Git

Status: untracked/tracked, staged and modified

- Untracked - (z ang. 'niśledzony') - does not track file change (Untracked files);

```bash
git add .
git add -all
git add name_file.enlargement
```

- Staged - (z ang. 'zainscenizowany') - staging area (z ang. 'strefa postojowa') - list of files that will go into the commite
  Staging area or index or cached (Changes to be commit w wejściu git status);

```bash
git commit -m "comment"
```

How write done comments for commits - co było zmienione i dlaczego w danym commit, tworzy się dla szybkiego powrotu do potrzebnej wersji.
Ogólne zasady tworzenia: powinno być krótkie, dla łatwego przeczytania, informacyjne

- Tracked - (z ang. 'śledzony') - in this status all files in which there is a trace of changes

- modified - (z ang. 'zmodyfikowany') - compares with the last saved version and shows the changes that took place (Changes not staged for commit);

Image for file livecycle loop in git [File_livecycle](https://pictures.s3.yandex.net/resources/M2_T5_1686651284.png)

The head shows which commit was made last
.git in this directory service file HEAD
HEAD can be written instead of the last commit hash

## Technologies used in the projects. What makes it different from the same ones?

### Documentation project: detailed instructions on what the project represents

#### Plans project

Example file readme.md [Git](https://github.com/git/git/blob/master/README.md)

##### Useful for readme

[Yandex - lesson](https://practicum.yandex.ru/trainer/git-basics/lesson/c6b9607c-e8bc-4446-89f9-c74522c3492f/)
[Yandex - cheat sheet](https://gist.github.com/fomvasss/8dd8cd7f88c67a4e3727f9d39224a84c)
[Markdown - cheat sheet](https://www.markdownguide.org/cheat-sheet/)
