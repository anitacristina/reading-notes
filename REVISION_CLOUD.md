# Revisions and the Cloud

**Git** is a version control system that lets you manage and keep track of your source code history

**GitHub** is a cloud-based hosting service that helps you to manage Git repositories.

**Repository** is a collection of files that we have told Git to pay attention to. It is also called repo.

        Usually, one project is equal to one repository
        
 ## Steps to Create and Manage Git Respository on my local computer
 
 1) Open your GitHub repository and click the green "Code" button and copy the URL that ends with .git
           https://github.com/anitacristina/HTML-Learning-Journal.git
           
 2) Open the terminal application on the computer and type "**pwd**" to show the current working directoy. The terminal will output as shown below:
 
            /Users/anitacristina$
            
 3) Next, copy the repository on the local computer by typing **git clone https://github.com/anitacristina/HTML-Learning-Journal.git** on the terminal.
 
 4) Now, move to the repo directory using the command "**cd HTML-Learning-Journal**"
 
 5) Type "**code .**" to open the files inside the **HTML-Learning-Journal** in VS code. 
 
 6) Update the any of the **.md** inside the **HTML-Learning-Journal** . After updating the **.md** files , type the following commands in the terminal
 
        6a) `git status` to see the changes made to the repository on the my local computer
        6b) `git add <filename.md>  - to tell git what changes to commit. This tells git to include changes in the next snapshot
        6c) `git commit -m "Reason for change"  - is the shutter-button to take the snapshot. -m specifies the message included wiht the commit.
        6d) `git push origin master` - to synch the change in the local computer to the repo on the GitHub. This sends any new commits to GitHub
        
  7) Finally, go the Git repositroy and see the changes are updated correctly.
  
        
 
 ## My Learnings from DeltaV Code 102
- [Home](README.md)
- [Growth Mindset](GROWTH_MINDSET.md)
- [Learning Markdown](LEARNING_MARKDOWN.md)
- [Coder's Computer](CODERS_COMPUTER.md)
- [Revision Cloud ACP](REVISION_CLOUD.md)
- [MORE TO COME]...

  
