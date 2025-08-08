# DevOps Task 3 – Version Control Project

## 📌 Objective
To demonstrate the use of Git & GitHub in a version-controlled DevOps project.

## 🛠 Tools Used
- Git (Local version control)
- GitHub (Remote hosting)

## 🌿 Branching Strategy
- `main`: Final code
- `dev`: Development/integration branch
- `feature-1`: Used to add new features

## 🔁 Workflow
1. Created `main`, `dev`, and `feature-1` branches.
2. Made changes in `feature-1` (e.g., `hello.sh`).
3. Merged `feature-1` ➝ `dev` via Pull Request.
4. Merged `dev` ➝ `main` via Pull Request.
5. Added `.gitignore` file to exclude unnecessary files.
6. Created Git tag `v1.0` to mark the first release.

## 📁 Files
- `hello.sh`: Simple shell script
- `.gitignore`: Lists files/folders Git should ignore
- `README.md`: Project documentation

📷 Screenshots
<img width="1920" height="1080" alt="Screenshot (111)" src="https://github.com/user-attachments/assets/4a64f8eb-e054-4f8f-889a-3e41990e8045" />

<img width="1920" height="1080" alt="Screenshot (110)" src="https://github.com/user-attachments/assets/5a7bd967-1d4a-4fdf-86ba-1f5b707a2ed0" />

## 🧾 Git Commands Used
```bash
git init
git branch
git checkout -b branch-name
git add .
git commit -m "message"
git push origin branch-name
git tag -a v1.0 -m "Initial version"
🔖 Git Tag
v1.0 – First stable release

📷 Screenshots
