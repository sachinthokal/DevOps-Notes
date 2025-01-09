# Initialize a Git Repository

```bash

cd path/to/your/project  # Navigate to your project folder

```

# Initialize a new Git repository and add files and commit on local :

```bash

--> git init                                #This creates a hidden .git folder in your project directory.
--> git add .                               #Add files to the staging area:
--> git commit -m "Initial commit"          #Commit the changes:

```

# Connect to a Remote Repository (e.g., GitHub)


```bash

--> git remote add origin https://github.com/your-username/your-repo.git        #Add a remote repository URL:

--> git push -u origin main         #Push the changes to the remote repository:

--> git status     #Check the status of the repository:

--> git pull origin main    #Pull the latest changes from the remote repository:

--> git clone https://github.com/your-username/your-repo.git    #Clone an existing repository:

```
