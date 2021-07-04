# Github-Commit-Patterns
Principles and patterns intended to standardize github commits.

## Why and when you should commit changes?


## What are the benefits of standardizing commits?

## Commmit Pattern:

Always use Present-continuous


Let's split commits in 6 differents types:

### Fix
  When you solve a previously or not identified issue
  ```
  git commit -m "fix - user controller index function"
  ```
 
  
### Add
  When you add a new feature into your project
  ```
  git commit -m "add - user controller sign-up function"
  ```
  
### Remove
  When you remove a feature, comments or function from your project
   ```
  git commit -m "remove - user controller like function"
  ```
  
  ```
  git commit -m "remove - user controller blank spaces"
  ```
  
### Update
  When you make minor changes in the code, like change variables name, change loop logic

  ```
  git commit -m "fix - confirm password not showing"
  ```
  
### Refactor
  When you make major changes in the code, like remake all logic in certain file or feature;
  
  ```
  git commit -m "refactor - profile page layout"
  ```

### Issue
  When you identify a issue in the code and you're not capable do solve this in the moment.
  ```
  git commit -m "issue - 001 sending duplicated user_id back to the client"
  ```
