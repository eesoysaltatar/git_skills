2023-02-20 EESOYSALTATAR git Added git root alias along with the titles. (This line should create a merge conflict with the changes from feature/person_1)
  
Basic git commands and configurations that I use:  
  
# commands  
git pull  
git branch new_branch_name  
git checkout branch_to_go  
git push origin branch_to_publish                    <-- To push the branch for the first time  
git push --set-upstream origin feature/eesoysaltatar <-- Set the origin representation of the local  
git status  
git add .  
git commit -m "my commit message"  
git log  
git push  
git diff  
git mergetool  
git diftool  
git difftool --cached                                <-- If your changes are staged  
  
# configurations  
git config --global user.email "john.doe@gmail.com"  
git config --global name "John Doe"  
git config --global diff.tool meld                         <-- Alternative: bcompare  
git config --global difftool.prompt false                  <-- Don't ask if open with meld  
git config --global alias.root 'rev-parse --show-toplevel' <-- $git root command goes to top level  
git config --global --get difftool.prompt                  <-- To remove use --unset  