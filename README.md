

<h1>Make your first Contribution.!  </h1>

![forthebadge](https://forthebadge.com/images/badges/open-source.svg)

<h2> ❓ What To Do </h2>
<ul><li>Add your name with profile link (as per markdown) in the <code>Contributors.md</code> file to make your first pull request 🚀</li></ul>

### How to make a Pull Request


<ul><li>Open Git Bash Here</li></ul>

<ul><li>Create a Git repository</li></ul>

<ul><li>Run command</li></ul>

     git init
     
<ul><li>Fork the repository</li></ul>
<ul><li>Clone your forked repository of the project</li></ul>

     git clone https://github.com/<your_username>/repository_name.git
     
<ul><li>Navigate to the project directory</li></ul>
<ul><li>Add a reference(remote) to the original repository</li></ul>

     git remote add upstream https://github.com/repository_owner/repository_name.git
     
<ul><li>Check the remotes for this repository</li></ul>

      git remote -v
     
<ul><li>Always take a pull from the upstream repository to your main branch to keep it updated</li></ul>

     git pull upstream main
     
<ul><li>Create a new branch (prefer a branch name)</li></ul>
     
     git checkout -b <YOUR_BRANCH_NAME>
     
   <ul><li>Perform your desired changes to the code base </li></ul>
   
   
   
  ### Check your changes
     git status
     git diff
  ### Stage your changes
     git add . <\files_that_you_made_changes>
  ### Commit your changes.
     git commit -m "relavant message"
  ### Push the committed changes in your feature branch to your remote repository
     git push -u origin <your_branch_name>
     
  ### To create a pull request, click on <code>compare and pull requests</code>
  ### Add an appropriate title and description to your PR explaining your changes.
  ### Click on <code>Create pull request</code>


*Congratulations🎉*, you have made a PR to the repository. 
Wait for your submission to be accepted and your PR to be merged by a maintainer.

--- 
Show some ❤️ by starring this repository✨
