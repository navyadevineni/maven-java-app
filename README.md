# maven-java-app
Basic maven java project

## Requirements

1. Java version
1. Maven version

### Project 
Steps to build a basic maven java project:

-  First create a repository in GitHub and initialize it with me README.md and .gitignore(select maven).
-  Clone the repository to your local.
-  Create a temp folder outside the cloned repository folder.
-  Open the temp folder with PowerShell by running as an administrator.
-  Run below command to generate all the archetypes available in mvn.
```
mvn archetype:generate 
```
-  Choose an archetype number you want to work on from the list generated.
-  Enter  unique 'groupId' and 'artifactId' should be the name of your repository.
-  Let the version and package be default by pressing ENTER.
-  Now, it asks you to confirm whether the configurations are correct or not.  [Y: :]
   If YES, type Y.
-  This creates a new folder in C:\temp\new_folder
-  Open the temp folder in VS Code. Review all the files in the folders.
-  Open PowerShell as an Admin in C:\temp
-  Run below commands and see the changes.
```
mvn clean
```
```
mvn compile
```
-  Now, run 'mvn clean'
-  Copy src and pom.xml files from the temp folder to the cloned repo folder.
-  Use Git Bash to add the files to source control, create a commit, and push them to the cloud repo.
```
git add --all
git commit -m "add maven archetype"
git push origin master
```
