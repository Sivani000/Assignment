# Git Continuation Assignment

## Objective
This assignment demonstrates Git version control operations including cloning a repository, creating a new repository, linking it to GitHub, and performing basic Git operations.

## 1. Clone an Existing GitHub Repository

```bash
git clone https://github.com/Sivani000/Day4.git
```

## 2. Create a New Local Repository

```bash
mkdir Assignment
cd Assignment
git init
```

## 3. Add Files

```bash
git add .
```

## 4. Commit Changes

```bash
git commit -m "Initial commit"
```

## 5. Link Local Repository to GitHub

```bash
git remote add origin https://github.com/Sivani000/Assignment.git
```

## 6. Push Changes

```bash
git push -u origin master
```

## 7. Verify

### Local Repository

```bash
git status
```

Output:

```
On branch master
nothing to commit, working tree clean
```

### GitHub Repository

Repository Link:

https://github.com/Sivani000/Assignment

The README.md file and the Initial Commit are successfully available on GitHub.
