# GitHub Commands Used for This Repository

This document records the typical commands used to create and publish this repository.

## 1. Create and enter the repository folder

```bash
mkdir research-projects-ualbany-hector-castillo-phd
cd research-projects-ualbany-hector-castillo-phd
```

## 2. Initialize git

```bash
git init
git branch -M main
```

## 3. Create the remote GitHub repository

If GitHub CLI is available and authenticated:

```bash
gh repo create research-projects-ualbany-hector-castillo-phd --public --source=. --remote=origin --push
```

If the remote repository is created first in the GitHub web interface:

```bash
git remote add origin https://github.com/<your-username>/research-projects-ualbany-hector-castillo-phd.git
```

## 4. Stage files

```bash
git add .
```

## 5. Commit

```bash
git commit -m "Initial commit: fraud classification and house price regression projects"
```

## 6. Push

```bash
git push -u origin main
```

## 7. Future updates

```bash
git status
git add .
git commit -m "Describe the update"
git push
```

## Notes

- The fraud dataset is included directly in the repository.
- The full real-estate dataset is not included because it exceeds GitHub's normal single-file size limit.
- To rerun the full regression notebook, place the original file at:

```text
usa-house-price-regression/data/USA Real Estate Dataset.csv
```
