# A02
This is a step by step tutorial on how to work git, github, and VScode.

Creating GITHUB Account:
The first step is create an account on Github. If you do not have an account, 
go to https://github.com. On the right, click "Sign Up".
When you click "Sign Up", you will be asked for information such as email, password, username, and county/region. 
There is also an option to sign up with Google or Apple if prefered. 
Once you create your account, you will be in the homepage. 


Downloading and Installing GIT:
Next, you will want to download Git. Go to https://gitforwindows.org/ to download Git.
NOTE: The URL present is for Windows users only. If you are using MAC or Linux,
you will need to find another link or download from the terminal on Linux. 
Once you download GIT, click on the new downloaded file and follow the instructions for installing Git.
After installing Git, you can open the Gitbash terminal. 

Downloading and Installing VScode:
The last piece of software you'll want to download is VScode. Go to https://code.visualstudio.com/download 
to download VScode. There are different options available for different operating systems. 
After you download the VScode file, open it and follow the step for installation. After the
installation process, you can open VScode. 

Making a Github repository:
Going back to Github, create a new repository. You can give the repository a name, choose can access it, have a README file, 
and more. Once your satisified with the settings, you can select "Create repository".

Cloning the repository:
Before cloning the repository, organize your file directory to where you want to clone the repository.
On VScode, click "Open Folder" and choose the file where you want to clone the repository. 
Next, click "Terminal" and select "New Terminal". Once you've done that, click on dropdown button next to the plus sign. From there, 
select Git Bash. You should then be on the Gitbash terminal. 
Use the "cd" command to get to the folder you want. 
After that, go the repository that you created.
IMPORTANT: The URL should have your username and name of the repository. Example: https://github.com/username/repository
In Gitbash, type "git clone URL". Copy and paste the URL of the repository after the "git clone" command.
This will clone the repository into your file directory. 

Updating the Repository:
In VScode, you can create different programming files in the folder of the cloned repository.
Note: To make program files, you need to specify the kind of file. Example: "Website.html"
However, you won't see your changes in the repository in Github. You have to push the changes to Github from Git. 
First, type "git add (names of files you want to push)". You can also do "git add ." to stage all of the files for pushing.
Next, type "git commit" to commit the files to be push. It is a good idea to have a message for commits. You can do this with (git commit -m "message").
Last, type "git push" to push everything to the repository. Everything should be updated in Github.

You can also make changes from Github instead of using the terminal. In the repository, select "Add File". You should see options to 
create a new file or upload files. If you choose to create a new file, you should name the file. On the left, you should see
a blank space to name the file. It should look like "(RespositoryName) / _______ in (branch)". 
Note: To make program files, you need to specify the kind of file. Example: "Website.html"
Once your done designing the file, you can commit the changes by clicking "Commit changes...". 
A pop up should appear. There you can make a commit message and add a description. You can add it to the main branch or create a new branch. Once you've decided, you can select, "Commit changes". Your changes should be made. 
To edit the file, click on the file you want to edit. On the right, you will see an dropdown with a pencil. 
Click on the pencil to edit the file. Then, you can make edits and commit the latest changes. 

Glossary:

**Branch** - different areas that allow you to work on different parts on a project.

**Clone** - a copy of a repository saved on your PC.

**Commit** - records changes in files.

**Fetch** - used to download references and other objects from other repositories.

**GIT** - a version control system that developers used to track changes of code.

**Github** - a version control system that is used for collaboration between developers.

**Merge** - combines two brances to form one.

**Merge Conflict** - when Git doesn't combine changes coming from different branches. 

**Push** - used to update commited changes from local machine to Github.

**Pull** - used to grab code from the repository and make changes.

**Remote** - link repositories that can push and pull updates 

**Repository** - a storage area where you keep files for developing projects.


Soruces:

https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches

https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository

https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits

https://git-scm.com/docs/git-fetch 

https://www.colabcodes.com/post/what-is-github

https://www.geeksforgeeks.org/git/git-merge/ 

https://www.geeksforgeeks.org/git/merge-conflicts-and-how-to-handle-them/ 

https://www.geeksforgeeks.org/git/what-is-git-pull/ 

https://www.geeksforgeeks.org/git/handling-repositories-with-git-remote/ 

https://www.geeksforgeeks.org/git/what-is-a-git-repository/