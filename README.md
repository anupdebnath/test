# Git Commands Reference Repository

A collection of commonly used Git commands for quick reference.

## Repository Operations

```bash
# Clone a repository
git clone https://github.com/username/repository.git

# Check status
git status

# Add files
git add filename.ext
git add .  # Add all files

# Commit changes
git commit -m "Commit message"

# Push to remote
git push origin branch-name

# Pull from remote
git pull origin branch-name
```

## SSH Key Generation

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```

## GPG Key Generation

```bash
gpg --gen-key
```

## Branch Management

```bash
# List branches
git branch
git branch -a  # List all branches including remote

# Create new branch
git branch new-branch-name

# Switch branches
git checkout branch-name
git switch branch-name  # Newer syntax

# Create and switch to new branch
git checkout -b new-branch-name
```

## History and Logs

```bash
# View commit history
git log
git log --oneline
git log --graph --all

# View changes
git diff
git diff --staged
```

## Remote Operations

```bash
# List remotes
git remote -v

# Add remote
git remote add origin https://github.com/username/repository.git

# Merge branches
git merge branch-name
```

## Additional Commands

```bash
# Show current branch and status
git branch --show-current

# Stash changes
git stash
git stash pop

# Reset to previous commit
git reset --hard commit-hash

# View remote branches
git ls-remote --heads origin