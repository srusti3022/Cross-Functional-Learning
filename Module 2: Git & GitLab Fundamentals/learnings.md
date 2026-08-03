# Lab Assignment – GitHub Workflow

## Tasks

### 1. Clone Repository
```bash
git clone <repository-url>
cd <repository-name>
```

### 2. Create Feature Branch
```bash
git checkout -b feature/my-changes
```

### 3. Modify Code
Make the required code changes and save the files.

### 4. Stage and Commit Changes
```bash
git add .
git commit -m "Implemented required changes"
```

### 5. Push Branch
```bash
git push -u origin feature/my-changes
```

### 6. Create Pull Request
1. Open the repository on GitHub.
2. Go to **Pull Requests** → **New Pull Request**.
3. Select:
   - Base Branch: `main`
   - Compare Branch: `feature/my-changes`
4. Create the Pull Request.

### 7. Resolve Review Comments
After receiving comments:
```bash
git add .
git commit -m "Addressed review comments"
git push
```

### 8. Merge Branch
Once approved, click **Merge Pull Request** and confirm the merge.

### 9. Update Local Repository
```bash
git checkout main
git pull origin main
```

### 10. View Git Log
```bash
git log --oneline
```

---

## Deliverables

1. Screenshot of the Pull Request (Merge Request)
2. Screenshot of `git log --oneline`
3. Repository URL

---

## Command Summary

```bash
git clone <repository-url>
cd <repository-name>

git checkout -b feature/my-changes

git add .
git commit -m "Implemented required changes"

git push -u origin feature/my-changes

git log --oneline

git checkout main
git pull origin main
```
