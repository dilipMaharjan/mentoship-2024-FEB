# mentoship-2025-FEB
Repo for tracking learning 


### **1️⃣ Fork the Repository**  
- Go to the GitHub repo.  
- Click **Fork** (top-right corner).  
- This creates a **copy** under your own GitHub account.  

### **2️⃣ Clone Your Fork**  
```bash
git clone https://github.com/dilipMaharjan/mentoship-2025-FEB.git
cd mentoship-2025-FEB
```

### **3️⃣ Create a New Branch**  
- Before updating, make sure you have the latest branches:
  ```
  git fetch --all
  ```
- Switch to the Child Branch (not main)
 ```
git checkout initial-setup-and-understanding

```
- Follow this **branch naming convention**:  
  ```
  <JIRA-TICKET-NUMBER>-<short-title>-<your-github-username>
  ```
  **Example:**  
  ```bash
  git checkout -b JIRA-123-github-integration-username
  ```

### **4️⃣ Create a Unique File (Include Your GitHub Username)**  
If multiple users are contributing the same type of file (e.g., `daily_learning.md`), **use your GitHub username to avoid conflicts**.  

🔹 **Filename Format:**  
```
daily_learning_<your-github-username>.md
```

🔹 **Example:**  
```bash
touch daily_learning_johndoe.md
```

### **5️⃣ Make Changes & Push to Your Fork**  
```bash
git add .
git commit -m "JIRA-123: Added daily learning for johndoe"
git push origin JIRA-123-github-integration-username
```

### **6️⃣ Raise a Pull Request (PR) to the Original Repo**  
- Go to your fork on GitHub.  
- Click **Compare & pull request**.  
- Select **the original repo’s `main` branch** as the target.  
- **PR Title Example:**  
  ```
  JIRA-123: Added daily learning for @johndoe
  ```
- Click **Create Pull Request**.  

### **7️⃣ Review & Merge PR**  
- The repository maintainers will review the PR.  
- If everything looks good, they will **merge** it into the main branch.  

---

## **✅ Why Use Your Username in Filenames & Branches?**  
✅ **Avoids conflicts** when multiple users create similar files.  
✅ **Helps maintainers track individual contributions.**  
✅ **Prevents accidental overwriting of someone else’s work.**  

