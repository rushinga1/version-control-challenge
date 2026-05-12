# Learning Resources

## Official Documentation
- **Git Official Site**: https://git-scm.com/
  - Comprehensive Git documentation and tutorials
  - Git book available free online: https://git-scm.com/book/en/v2

- **GitHub Learning Lab**: https://lab.github.com/
  - Interactive courses for learning GitHub workflows
  - Free hands-on training

## Useful Guides
- **GitHub Guides**: https://guides.github.com/
  - Hello World (intro to GitHub basics)
  - Understanding the GitHub flow
  - Forking Projects

- **Atlassian Git Tutorials**: https://www.atlassian.com/git/tutorials
  - Beginner to advanced Git concepts
  - Visual explanations of workflows

## Interactive Learning
- **Git Visualization**: https://git-school.github.io/visualizing-git/
  - Visualize how git commands work
  - Great for understanding branching and merging

- **Learn Git Branching**: https://learngitbranching.js.org/
  - Interactive sandbox for practicing Git commands
  - Progressive difficulty levels

## Best Practices
- **GitHub Flow**: Simple workflow ideal for continuous deployment
  - Create a branch → Make changes → Open a PR → Review → Merge → Deploy

- **Commit Message Best Practices**:
  - Write clear, descriptive messages
  - Use imperative mood (e.g., "Add feature" not "Added feature")
  - Keep first line under 50 characters
  - Add detailed description if needed

## Common Git Commands Cheat Sheet
```
# Setup and Configuration
git config --global user.name "Your Name"
git config --global user.email "your@email.com"

# Creating & Cloning
git init                          # Initialize a new repo
git clone [url]                   # Clone a repository

# Branching
git branch                        # List branches
git branch [branch-name]          # Create a new branch
git checkout [branch-name]        # Switch to a branch
git checkout -b [branch-name]     # Create and switch in one command
git branch -d [branch-name]       # Delete a branch

# Making Changes
git status                        # See status of files
git add [file]                    # Stage a file
git add .                         # Stage all changes
git commit -m "message"           # Commit staged changes

# Pushing & Pulling
git push origin [branch]          # Push branch to remote
git pull origin [branch]          # Fetch and merge remote changes
git fetch                         # Download changes from remote

# Merging
git merge [branch-name]           # Merge branch into current branch

# Undoing Changes
git restore [file]                # Discard changes in working directory
git reset HEAD [file]             # Unstage a file
git revert [commit]               # Create new commit that undoes changes
```

## Tips for Beginners
1. **Start with the basics**: Master add, commit, push before advanced features
2. **Use descriptive branch names**: Makes it clear what you're working on
3. **Commit frequently**: Small, logical commits are easier to review and revert if needed
4. **Write good commit messages**: Helps your teammates understand your changes
5. **Review before pushing**: Always check what you're committing
6. **Create backups**: Push your work regularly to avoid losing progress
7. **Practice on a test repo**: Experiment without fear in a practice repository

## Troubleshooting
- **"fatal: not a git repository"**: Run `git init` in your project directory
- **"Permission denied"**: Check your SSH keys or use HTTPS with personal access token
- **Merge conflicts**: Read both versions carefully, resolve conflicts, then commit
- **Accidentally deleted a branch**: You can usually recover it from reflog with `git reflog`
