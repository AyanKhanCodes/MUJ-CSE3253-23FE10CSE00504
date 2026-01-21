# Git Workflow Documentation

## 1. GitFlow vs GitHub Flow
- **GitFlow:** A robust framework for large projects. It uses two main branches (\`main\` and \`develop\`) and supporting branches (\`feature\`, \`release\`, \`hotfix\`). It is great for strict release schedules.
- **GitHub Flow:** A simpler workflow where everything branches from \`main\` and is deployed immediately. It is better for Continuous Deployment (CI/CD).

## 2. Rebase vs Merge
- **Merge:** Use when merging features into shared branches like \`develop\`. It preserves history and shows exactly when a feature was integrated.
- **Rebase:** Use locally to clean up your own feature branch before sharing it. It keeps history linear but rewrites commits (dangerous on shared branches).

## 3. Commit Message Conventions
- **Feat:** New feature (e.g., "Feat: Added login page")
- **Fix:** Bug fix (e.g., "Fix: Resolved CSS conflict")
- **Docs:** Documentation changes
- **Style:** Formatting/Style changes

## 4. Pull Request Template
### Summary
Briefly describe the change.

### Type of Change
- [ ] New feature
- [ ] Bug fix
- [ ] Refactor

### Checklist
- [ ] Tests passed
- [ ] Documentation updated