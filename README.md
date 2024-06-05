# Branch in Github

1. git branch ---> to check branch
2. git branch -M main ---> rename branch
3. git checkout <branch_name> ---> to out from a git branch and enter to another branch
4. git checkout-b <new_branch_name> ---> create new branch
5. git branch-d <branch_name> ---> delete branch

if you're in branch1 and tried to delete branch1 than it will throw an error as you are currently in branch1 so can't delete branch1 but you can delete other branches.

if you create or modifies any files and commit changes from a branch then it will be dissapeared for another branch.

to know difference between two branches run command "git diff <branch_name>"

run command "git merge <other_branch_name>" to merge two branches and whenver there's conflict occurs merge by terminal instead of pull request on github webpage.
