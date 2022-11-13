&#187; This exercise is about learning how to use git to collaborate.

&#187; You'll have a git repository that the team leader creates, where you have one file that everyone has to edit. 

&#187; This file is a restaurant menu, with a list of foods and drinks people can buy.

&#x2611; The leader creates this new file, commits, then creates a new branch called "develop", and pushes this branch in the repo. 

&#x2610; Everyone else has to create new branches from this develop branch.

&#x2610; Each student has to create a branch called "feature-food-name", where you type in the name of the food, edit the file and add a food and a drink to the menu.

&#x2610; Commit your changes, then push the branch, then make a pull request.

&#x2610; The team leader approves the push requests and merges the work everyone else has done.

&#x2610; In the end, you should have all feature branches merged into "develop", and then merge "develop" into your main branch. You should have a file that looks like this:




        ---Restaurant menu---

        ---Dishes---

        Dish 1
        Dish 2
        Dish 3
        Etc..

        ---Drinks---

        Drink 1
        Drink 2
        Drink 3
        Etc..


&#187; Some useful git commands:
`git switch "branchName"` - Switches to another branch
`git branch -r`
`git checkout -b "newBranchName"` - Create new Branch and checkout to that new branch.