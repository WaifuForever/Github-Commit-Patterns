# Github-Commit-Patterns
Principles and patterns intended to standardize github commits.

## Why and when you should commit changes?


## What are the benefits of standardizing commits?

## Commmit Pattern:

Let's split commits in 5 differents types:

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
  git commit -m "update - page url"
  ```
  
### Refactor
  When you make major changes in the code, like remake all logic in certain file or feature;
  
  ```
  git commit -m "refactor - profile page layout"
  ```

## Documenting issues
  When you identify a issue in the code and you're not capable do solve this in the moment.
  Every unsolved issue needs to be documented somewhere, you can keep this inside readme.md or another file.   
 
  Example:
  ```
  {
  "001" : sending duplicated user_id back to the client"
  }
  
  ```
  
  if you still not solve this issue and want to send another commits you should do as shown:
  
  ```
  git commit -m "add - user controller delete function [001]"
  ```
  
  always inform if the documented issue is solved or not in the current commit  
  if all documented issues are solved you can type empty square brackets [] or just omit them

  ```
  git commit -m "add - user controller delete function []"
  ```
  
  also right:
  ```
  git commit -m "add - user controller delete function"
  ```
  
  Never delete a documented issue from the file where you are store them, this is way you will always know which fixed or unfixed issues are in the commit

## Conventions
  Always use Present-continuous
  ```
  git commit -m "update - using cors"
  ```
  
  Using text inside commit:
  ```
  git commit -m "add - 'admin/index' route"
  ```

