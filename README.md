# git_practice

git --version  ------> show the version
git --help       ------> git Documentation 
git clear  -----------> clear all the seen command 

Create Name & Email:
 git config --global user.name"username"       ------------------------->To create username
 git config --global user.email"emailname@domain.com"   -------> to create email

Rename Name & Email:
		 git config user.name
		 git config user.email
		 git config --global user.name "User name" 
		 git config --global user.email"enter email"

 To configure editor:
	git config --global core.editor"notepad"    ------> for configure notepad
	notepad test.txt                            -------------------> open the file create in notepad
	git config  --global core.editor"notepad"   ------> for selection of core editor
	notepad test.txt  --------------------------------------> open the create file in notepad 
	git config --list                                    ---------------> display all the available list
		
	
# TRACK FILE 
  1. make directory :          mkdir shop
  2.  change directory :      cd shop
  3. Track this directory :   git init         ------> show the location where the file
	Show the location where it is : 
	
	
	
 4. ls -A     ------------------> move inside the git
 5. ls .git      ----------------> move inside git
 6. touch list.txt    -------> create file inside the shop
 7. rm list.txt        --------> remove the created file
 8. ls         -------------------> display all the available list

	
	

 git status             -----------> display the condition of status 
 git add list.txt     -----------> add to the branch 
 git status : 
	

 git commit -m " Create shopping list"    ------------>commit the file 



git status     ---------------> show the status of the condition




 git log   ------------------->  tell the history of the commit of the  file 
    

	

 git diff               --------------> show current changes
 git add list.txt       ----------> add new element in the file


 git reset HEAD ~1 --mixed    ---> removes the commit and also makes the changes unstaged

Reset options :
	soft
	mixed
	hard 

 Branching     ----------> create sub branch

		

git branch meat    --------> create meat branch
git checkout meat  ------>To enter to the particular branch like meat 
 

 For GitHub
 1. Goto github and sign in 
 2. Copy http link given on there url
  3. Sinchronize our local repository with the new repository on GitHub



Screen clipping taken: 07/11/2022 22:22

<-- this step is called staging
      

Commit hash code is unique email id 
![image](https://user-images.githubusercontent.com/65486178/204134693-4203ebd8-1b90-428d-b35d-8d76f521821a.png)
