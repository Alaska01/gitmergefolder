# Tutorial On Git Merge

- This is just a brief tutorial on how to work on multiple branches while working on a single project with multiple features.

- A video link will be added
- This tutorial is majorly meant for beginers in programming who are trying to understand various ways on how to navigate the git.
- There are various other ways of doing git merge, this is just one of the ways using the terminal.
- Thanks

# Commands
- create you repo
- checkout of the main branch to development with `$ git checkout -b development`
- create a commit and push to the development branch
- checkout to the feature branch i.e navigation-feature with `$ git checkout -b navigation-branch`
- develop the feature of the navigation bar. Once you are done with development, checkout to the topic branch which in our case is the development branch where we would create our pull request later.
- Do `$git checkout development` to exit the **navigation-branch** and go to the **development branch**
- Now we are on the development branch, we can merge our completed feature into development
- This can be done with git `$ merge navigation-branch`
- after this the content of the navigation is added to the development branch and the development branch is up to date with the navigation-branch
- we can push to github to have the details remotely. 
- We can now check out again to another topic branch i.e `$ git checkout -b footer-branch`
- Once we are done with the footer we can now repeat the above process.
- We can assume we are done developing and create a pull request and submit for Review.
-Thanks