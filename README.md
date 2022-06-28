# GIT ##


 
   # > GIT COMMAND 
   * #  creat a new repoistory
1. creat READMe file
   ```bash
   git "devops">> README.md 
   ```
1. initialize
   ```bash
   git init
   ```
1. adding RERADME file 
   ```bash
   git add README.md
   ```
1. commiting 
   ```bash
   git commit -m "first commit"
   ```
1. main branch 
   ```bash
   git branch -m main
   ```
1. connect director with the remote 
   ```bash
   git remote add origin https://github.com/example.git
   ```
1. push the file to hte main branch on remote
   ```bash
   git push -u origin main 
   ```
   or
    ```bash
   git push --set-upstream https://github.com/example.git dev 
   ```  

    >  💡 **NOTE**  
    > dev is the branch name 

* # creat a new branch 

1. creat a new branch, we call it dev2
   ```bash
   git switch -c dev2
   ```
1. push the new branch to repository 
      ```bash
   git push --set-upstream https://github.com/example.git dev2 
   ``` 
* # switch between branches  
   ```bash
   git cheackout dev2 
   ```
* # deleting a local branch 
    ```bash
   git branch -d dev2
   ```
* # deleting a remote branch 
    ```bash
   git push origin --delet dev2
    ```
* # adding all files 
    ```bash
   git add .
    ```
* # adding txt files or specific files
    ```bash
   git add *.txt
    ```
* # some common command
1. show where you are 
    ```bash
   pwd
    ```
1. all list 
    ```bash
   ls
    ```
1. witch branch you at
    ```bash
   git branch
    ```
1. witch usre you are using 
    ```bash 
   whoami
    ```
1. start make change in directory
    ```bash 
   code .
    ```
1. creat a folder (directory)
    ```bash 
   mkdir dev
    ```
