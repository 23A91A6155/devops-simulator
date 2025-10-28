# 🧩 DevOps Simulator Project  

## 📘 Objective  
To practice resolving **Git merge conflicts** between `main` and `feature` branches using Git commands.  

## 🛠 Tools Used  
- **Git** → Version control system  
- **VS Code / Command Prompt** → For editing and running Git commands  
- **GitHub** → To store and share the repository  

## 🧾 Steps Performed  

### 1️⃣ Initialize Repository  
```bash
git init
2️⃣ Create and Commit in Main Branch
echo "Welcome to DevOps Simulator - main branch" > simulator.txt
git add .
git commit -m "Initial commit on main branch"

3️⃣ Create and Commit in Feature Branch
git checkout -b feature-branch
echo "Welcome to DevOps Simulator - feature branch version" > simulator.txt
git add .
git commit -m "Feature branch changes"

4️⃣ Merge Branches and Resolve Conflict
git checkout main
git merge feature-branch


Then manually edited the conflict:

Welcome to DevOps Simulator - merged version (main + feature)

5️⃣ Commit Resolved Conflict
git add simulator.txt
git commit -m "Resolved merge conflict between main and feature-branch"

6️⃣ Push to GitHub
git push origin main

✅ Result

Successfully resolved merge conflicts and pushed final code to GitHub.
Repository now contains:

simulator.txt → merged version

README.md → documentation
