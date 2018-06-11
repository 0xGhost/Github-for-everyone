# Git for new Developers

## Creating a new repository :

1. Create a new repository from Github
1. On your local terminal navigate to where your repository would be on your machine
1. Type ```$ git init [project name]```
1. Create a local file. Could be done with ```$ touch README.md``` 
1. After creating your file type ```$ git add [file]``` or ```$ git add .```(to add all your changes if u want)
1. When we have all our changes ready we type ```$ git commit -m "[commit name]"``` to commit our changes/files
1. Because this our first commit to the repository before we push our changes to github we need to type  ```$ git remote add origin [our repository link]```
1. Now we are ready to push our repository to github with ```$ git push -u origin master```

## Branches

When working as team
