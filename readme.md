1. **Check Git Version:**

```bash
git --version
```

2. **If Not Installed (on Debian/Ubuntu):**

```bash
sudo apt update
sudo apt install git
```

3. **Make New Directory:**

```bash
mkdir project-name
```

4. **Change to That Directory:**

```bash
cd project-name
```

5. **Initialize Git:**

```bash
git init
```

6. **Configure Git Account:**

```bash
git config --global user.name "Shre-05"
git config --global user.email "shre0505@gmail.com"
```

7. **Make or Add Files in Your Directory**

8. **Go to GitHub & Create New Repository**

9. **Add Files to Staging Area:**

```bash
git add filename         # to add specific file
git add .                # to add all files
```

10. **Commit the Changes:**

```bash
git commit -m "Initial commit"
```

11. **Check Git Status (Correct Typo):**

```bash
git status       # ❌ you wrote `git statusa` by mistake
```

12. **Link Local Repo to GitHub Repo:**

```bash
git remote add origin https://github.com/Shre-05/repo-name.git
```

13. **Push Code to GitHub:**

```bash
git push -u origin master     # ❗ for older repos
# OR use:
git push -u origin main       # ✅ Recommended, as most new repos use "main"
```

14. **Removes untracked files**

```bash
git clean -f
```

15. **Copy an existing repo**

```bash
git clone URL
```
16. **Updates last commit**

```bash
git commit --amend -m "new msg"
```

17. **Fetches without merging**

```bash
git fetch origin	
```

18. **Shows commit history**

```bash
git log	
```

19. **Fetch + merge**

```bash
git pull origin master	
```

19. **Pushes changes**

```bash
git push origin master	
```


20. **Linearizes history**

```bash
git rebase main	
```

19. **Shows HEAD changes**

```bash
git reflog		
```

