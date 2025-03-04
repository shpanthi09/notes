# Notes Git and Github

## 1. Print the current Git username and email:
```bash
git config --global user.name    # Prints the global username
git config --global user.email   # Prints the global email
# Or for the current repository-specific user settings (local):
git config user.name    # Prints the username for the current repository
git config user.email   # Prints the email for the current repository
```

## 2. Set a new username and email for the current repository:
```bash
git config user.name "New Username"      # Sets a new username for this repository
git config user.email "newemail@example.com"   # Sets a new email for this repository
```

## 3. 3. Set a new global username and email:
To change the global username and email (applies to all repositories):
```bash
git config --global user.name "New Global Username"
git config --global user.email "newglobalemail@example.com"
```

## 4. Verify the change:
To verify the configuration:
```bash
git config --list    # Lists all the git configurations
````
## 5. Clone using Work/Personal GitHub Account (After SSH setup):
```bash
git clone git@github.com-work:username/repository.git
git clone git@github.com-personal:username/repository.git
```





 
