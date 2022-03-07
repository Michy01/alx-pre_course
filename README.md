My first readme

# 1. Create a new directory called 0x01-git in your alx-pre_course repo.

Make sure you include a non empty README.md in your directory:

at the root of your repository alx-pre_course
AND in the directory 0x01-git
And important part: Make sure your commit and push your code to Github - otherwise the Checker will always fail.

Repo:

GitHub repository: alx-pre_course
    
#  2. Coding fury road
mandatory
Score: 50.00% (Checks completed: 100.00%)
For the moment we have an empty project directory containing only a README.md. It’s time to code!

Create these directories at the root of your project: bash, c, js
Create these empty files:
c/c_is_fun.c
js/main.js
js/index.js
Create a file bash/alx with these two lines inside: #!/bin/bash and echo "ALX"
Create a file bash/school with these two lines inside: #!/bin/bash and echo "School"
Add all these new files to git
Commit your changes (message: “Starting to code today, so cool”) and push to the remote server
Repo:

GitHub repository: alx-pre_course
Directory: 0x01-git
File: bash/alx, bash/school, c/c_is_fun.c, js/main.js, js/index.js
     
# 3. Collaboration is the base of a company
mandatory
Score: 50.00% (Checks completed: 100.00%)
A branch is like a copy of your project. It’s used mainly for:

adding a feature in development
collaborating on the same project with other developers
not breaking your entire repository
not upsetting your co-workers
The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.

For this project, create a branch update_script and in this branch:

Create an empty file named bash/98
Update bash/alx by replacing echo "ALX" with echo "ALX School"
Update bash/school by replacing echo "School" with echo "The school is open!"
Add and commit these changes (message: “My personal work”)
Push this new branch Tips
Perfect! You did an amazing update in your project and it’s isolated correctly from the main branch.

Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:

Change branch to main
Update the file bash/alx by replacing echo "ALX" with echo "ALX School is so cool!"
Delete the directory js
Commit your changes (message: “Hot fix”) and push to the origin
Ouf, hot fix is done!

Repo:

GitHub repository: alx-pre_course
Directory: 0x01-git
File: bash/alx, bash/school, bash/98
