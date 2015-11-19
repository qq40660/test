how?
===
1. **git push** 本地分支--->远端库  
 ###两个参数

 > * 远端库名,如origin
 > * 本地分支，如master

 ###用例

 `git push origin master` 

 ---

2. **重命名分支**

 `git push <remote name> <local branch name>:<remote branch name>`

 > 此操作在远端库建立一个以remote-branch-name命名的新的分支 

3. **标签**

 `git push <remote-name> <tag-name>`
 