# MTP Website

A modern, responsive website built with HTML, CSS, and JavaScript.

## Version Control Workflow

This project uses Git for version control. Follow these guidelines for maintaining the codebase:

### Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rayfrank/MTPWebsite.git
   cd MTPWebsite
   ```

2. **View the website:**
   Open `index.html` in your web browser to view the website locally.

### Development Workflow

#### Creating Feature Branches
Always create a new branch for any feature or bug fix:
```bash
git checkout -b feature/your-feature-name
# or
git checkout -b bugfix/bug-description
```

#### Making Changes
1. Make your changes to the code
2. Test your changes by opening `index.html` in a browser
3. Stage your changes:
   ```bash
   git add .
   ```
4. Commit with a descriptive message:
   ```bash
   git commit -m "Add responsive navigation menu"
   ```

#### Branch Naming Conventions
- `feature/feature-name` - for new features
- `bugfix/bug-description` - for bug fixes
- `hotfix/critical-fix` - for urgent fixes
- `docs/documentation-update` - for documentation changes

### Commit Message Guidelines

Write clear, concise commit messages:
- Use present tense ("Add feature" not "Added feature")
- Limit the first line to 50 characters
- Include details in the body if necessary

**Examples:**
```
Add responsive mobile navigation
Fix header alignment on mobile devices
Update contact form validation
Improve page load performance
```

### File Structure

```
MTPWebsite/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Main stylesheet
├── js/
│   └── main.js         # Main JavaScript file
├── assets/
│   └── images/         # Image files
├── .gitignore          # Git ignore rules
└── README.md           # Project documentation
```

### Best Practices

1. **Keep commits small and focused** - Each commit should represent one logical change
2. **Write descriptive commit messages** - Help others understand what changed and why
3. **Test before committing** - Always test your changes in a browser
4. **Use .gitignore** - Don't commit unnecessary files (build artifacts, dependencies, etc.)
5. **Review your changes** - Use `git diff` to review changes before committing

### Common Git Commands

```bash
# Check status of your files
git status

# View changes made to files
git diff

# View commit history
git log --oneline

# Switch to a different branch
git checkout branch-name

# Create and switch to a new branch
git checkout -b new-branch-name

# Merge a branch (after switching to main/master)
git merge feature-branch-name

# Push changes to remote repository
git push origin branch-name

# Pull latest changes from remote
git pull origin main
```

### Deployment

This is a static website that can be deployed to any web server or static hosting service:
- GitHub Pages
- Netlify
- Vercel
- Traditional web hosting

### Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Commit with clear messages
6. Push to your fork
7. Create a pull request

### Support

For questions about the codebase or version control workflow, please create an issue in the repository.