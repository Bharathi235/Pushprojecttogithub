# Pushprojecttogithub
How to push Projects to github Step by Step

Step 1:Be In the Project directory that you want to push
Step 2: to initialize a repository 
        $ git init
Step 3: to check git Status  
       $ git status
step 4: $ git add .
Step 5: again check git Status to check files added or not 
       $ git status
Step 6:$ git commit -m "initial commit"
     
     For bigginners here you will encounter an error like
     Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.
**follow the below Steps to resolve**
     1.Mention your github email id  in the place of user@gmail.com
             $ git config --global user.email "user@gmail.com"
     2.Mention your github username in the place of USER
             $ git config --local user.name "USER"
     3. To check if its Added or not
              $ git config --list
              
Step 7: Again use commit command your error got resolved Already
       $ git commit -m "initial commit"
Step 8: Create a Repository in your github account and copy the link from download button on your newly created repository then paste it in the beloow command
       $ git remote add origin https://github.com/user/sampleProject.git
Step 9 : use push command 
       $ git push -f origin master





