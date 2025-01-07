# CLI (Command Line Interface) commands

- Tell your computer what to do
- commands 
    - ls -> Lists out the contents of the current directory. 
    - cd (directory name) -> changes the directory. 
        - .. -> goes up one directory
        - / -> seperates navigating multiple directories
    - mkdir (directory name) -> creates a new directory.
    - touch (filename.extension) -> creates a new file. 
    - mv and rm -> move, rename | remove command
        - NEVER RUN THIS COMMAND -> rm -rf
    - code (directory name) -> open VSCode at the target directory.
        - . -> refers to the current directory. 
    - && -> do one command after another finishes

- Flags
    - Extensions of commands
    - Example: ls -a (shows all fiels and directories in the current folder)

# Git vs Github

- Git -> version control system using git commands that keep track of the history of files. 
    - initial commit is starting of the project.
- Github -> place to store all of our projects (Repository/ "Repo")

- git commands. 
    - git init -> allows a project to use git commands.
    - git status -> shows what has been added/changed/deleted since the last commit. 
    - git add (file names) - moves the files and folders from the working directory to the staging area
    - git commit -> takes everything from the staging area and makes it permanent*
        - -m "message" -> This is where you type in the message of the changes made otherwise VIM will open if no -m is included.
    - git remote -> another location
        - add -> add connection
        - nickname -> name of connection (Most commonly origin)
        - location -> where is teh actual location (url)
    - git branch -> tells us which branch we are on. 
        - -> -M (branch name) -> renames teh main branch to the branch name specified. 
    - git push -> send code from local computer to somewhere ( github )
        - nickname -> nickname of the place that you want to send your code to. 
        - branch name -> which branch you want to push
    
- 3 Stages
    - Working directory (red) Still working on it
    - stagging area (green) Are you sure you want to commit this to the project
    - project

# File naming and Structure HTML and CSS Files 

 - Don't use special characters (!, @, #, $,%, ^,&,*) Except for hyphens. 
 - Don't use spaces, use hyphens. 
 - Start the file name with a letter.
 - Use all lowercase letters seperated by hyphens.
 - Keep your file names short and descriptive.
 - ALWAYS put a file extension on files.

 # Feature Branches

-  git checkout -> Move to a new branch
    - -b -> create a new branch
    - [branch name] -> name of feature you're adding

- Steps 
    - Make a feature branch
    - make changes in code
    - push up the feature branch to GitHub
    - make a pull request in Github
    - code review the changes
    - If good, mere feature branch with main. 
    - in VS Code go to the main branch (git checkout main)
    - Pull the latest changes from Github (git pull nickname main)
