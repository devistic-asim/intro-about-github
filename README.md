## Welcome to intro-about-github!

This repository is designed for practice and learning purposes.

## Lecture Notes:              

* Introduction to Version Control and GitHub.     
* Understanding version control and its importance.   
* Github Authentication or First-Time Usage Commands
* Introduction to Git and GitHub.                 
* Creating a GitHub account.                      
* Initializing a repository.                      
* Basic Git commands (clone, status, add, commit, push, pull).                                        
* Collaborative workflows (fork, branch, pull request).

## Git/Github Authentication:
For first-time usage, we need to configure authentication for our Git account. To do this, we use the following commands:

```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
Note:

* "Your Name" represents the name you want to display on commits in your repositories.        
* "your.email@example.com" is the email associated with your GitHub account.

## Workflow:

* Introduction to Git and GitHub:     
    Initializing a repository   

```
1. git clone    
4. git status   
5. git add .    
6. git commit -m "name"     
7. git push origin main     
8. git pull origin main     
```

## Scenarios
```
1) 2 Different Files Changes | -> auto-merge | :q for quiting the warning window

if 2 or more persons working on the same repo. Person 1 pushed the code, and Person 2 is coding in his folder and wants to push the code, then a 'rejected' warning will be shown:

in this case, Person 2 should pull the code first and then push its own code.
```

```
2) Same File Changes | manual-merge:

if 2 or more persons working on a same repo in same file. Auto-Merge failed in this case, so maually accept the changes and after accepting, add, commit and push the code.

```
## Github Branches:

                      [Main-Branch]
                            |
                [Dev-Branch OR Test-Branch]
                     |                |
            [Design-Branch]    [Backend-Branch]

```
git checkout {branch name}
``` 

## Resources Url:
* https://www.youtube.com/watch?v=qeXnsqbzBCU&ab_channel=Codanics
