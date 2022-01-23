# GIT 
 - It's a version control software.
 - [Udemy course link https://www.udemy.com/course/learngit/learn/lecture/6853274#overview]
 - Download link : https://git-scm.com/download/
 - Next to update
    - Enter 'got clone hhtps://github.com/git/git' in the terminal.
****
## Commands 
 - Create repository
   - git init => to initialise .git folder in the location.
   - git status => to show the files in the current folder
 - Add file in the repository
   - add file which already located with .git folder in the same location
   - git add filename.type
   - git add . => it will add every single files, can use this if there's more then one files
 - Commiting the change
   - git commit -m "what's the change" 
 - Branching
   - git branch filename => inorder to have the backup[* master] and the same one for change[filename]
   - git checkout filename => to switch over form master to name[new one to commit change here]
   - git checkout -b filename => I t simplifies the above two commands to one line command
   - git add . => to add our changes
   - git commit -m "made the change"
 - merging
   - git merge filename => Be in master branch then add change file[filename]
 - Deleting
   - git branch filename -d => for deleting
   - git branch filename -D => if the above not works use this called force delete
 - Riverting
   - git revert <commitid> => it's just like undo process
   - git log => to get the commit id
   


    

