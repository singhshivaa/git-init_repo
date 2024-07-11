# Pushing Code to GitHub

Follow these steps to push your code to GitHub using the command line:

1. **Initialize Git Repository** (if not already initialized):
   ```sh
   git init
2. **Add Remote Repository** (if not already added):
   ```sh
   git remote add origin https://github.com/your-username/your-repository.git

4. **Check Status:**
    ```sh
   git status
6. **Add Files to Staging Area:**
    ```sh
   git add .
8. **Commit Changes:**
    ```sh
   git commit -m "Your commit message"
    
10. **Push to Remote Repository:**
     ```sh
    git push origin main

**Note: Replace main with the appropriate branch name if you're using a different branch.**








Example:
**Here's a full example of pushing code to GitHub:**
```sh
cd /path/to/your/project
git init
git remote add origin https://github.com/your-username/your-repository.git
git status
git add .
git commit -m "Initial commit"
git push origin main

Certainly! Here are the steps to push code to GitHub using command line:

1. **Initialize Git Repository** (if not already initialized):
   ```sh
   git init
   ```

2. **Add Remote Repository** (if not already added):
   ```sh
   git remote add origin https://github.com/your-username/your-repository.git
   ```

3. **Check Status**:
   ```sh
   git status
   ```

4. **Add Files to Staging Area**:
   ```sh
   git add .
   ```

5. **Commit Changes**:
   ```sh
   git commit -m "Your commit message"
   ```

6. **Push to Remote Repository**:
   ```sh
   git push origin main
   ```
   *Note*: Replace `main` with the appropriate branch name if you're using a different branch.

### Example:
Here's a full example of pushing code to GitHub:

```sh
cd /path/to/your/project
git init
git remote add origin https://github.com/your-username/your-repository.git
git status
git add .
git commit -m "Initial commit"
git push origin main
```

Make sure you replace `https://github.com/your-username/your-repository.git` with the URL of your GitHub repository. If you haven't set up your GitHub credentials, you may be prompted to enter your username and password or a personal access token.


