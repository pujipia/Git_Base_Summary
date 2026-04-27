# Git_Base_Summary
This is a summary of basic usage for Git, which could help you to get a quick understanding. For the further development, readers can log in the Git website to read their instruction
## There is a simple introduction of Working Flow
1. Open Terminal on your desk
2. Use mkdir to make a directory
3. Enter the directory and use ni .\directory_name\file_name to create a file
4. Add a new repository on the github, and you can find its address in a blue button "code<>"
5. Open terminal in your file:
   1. Input "git init" to create a .git file (you can't see it)
   2. Check your online REMOTE status first, if there were some files in it, you should connect it: "git remote add short_name link_of_REMOTE" and pull it down to your local file first by: "git pull short_name branch_name"   
   3. Input "git add ." to add all of the files in the folder to be controlled by Git
   4. You can also use "git status" to check the current status of your files or even get a hint for the next step
   5. Input "git commit -m "your_comment" "to commit your change with a comment
   6. Input "git push -u short_name branch_name" to push your local file to the online REMOTE
