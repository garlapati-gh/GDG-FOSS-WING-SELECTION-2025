### Answer the following questions in you own words.

> It's not necessary that you havee to know and answer all the questions. Just answer the ones
> you know and write in your own words.

1. Give the difference between the remotes - upstream and origin - with an example.

You answer:

2. You have two branches A and B and you have currently made some changes in branch A.
You want to move into branch B but do not want to commit the current changes in branch A.
What will you do?

You answer:

3. You were assigned a work to implement a feature and create a PR to your organization's remote repository.
For this you made a branch (say A) and made some changes and commited them. Now you moved to some other branch 
(say B) to do some other assigned work. But later you realisd that have to complete the task assigned earlier 
first and commited some changes in branch B which are meant for branch A. How will you use git to bring the 
changes from branch B to branch A?

You answer:

3. What is the difference between fetching changes and pulling changes?

Your answer: fetch is used when something is updated and we get the changes from repos to our pc. but git pull is used when it not only fetch changes but also merge to our repo, like it is used when we also want to have the changes in our branch not only just seeing them.

4. What does -i flag stand for? What is it's significance in git?

You answer:

5. You are working in an organization that follows very strict guidelines for PRs and commits.
You made three commits in your PR and the maintainer says you were supposed to make a single commit.
What will you do in this case?

You answer:

6. Explain `git merge` and `git rebase` with example(s).

You answer: 

7. Write the flow how you create a repository and push changes to it. Also mention the commands used at each step.

You answer:
    firstly we create a new repo in our github profile by putting a name to it (assume it to be https://github/name/project-name.git)

    Then we start by initialising the git locally by using "git init", which creates a folder for us to work on.

    After our code is written and and all files are done we add i.e. "git add ." (if autosave is not there we save it by CTRL+S)

    then we commit our changes just like we did for profile.md, documentation.md i.e. "git commit -m "Add profile.md to  repo"" is an example which saves our changes with a message, here it is Add profile.md to  repo.

    now we copy the new repo we creaed link which is ib github then we link the locally did work to online ie.e "git remote add origin https://github/name/project-name.git"
    
    now we push our changes to github i.e. "git push -u origin main"
    

8. How would you prevent a file or folder from getting tracked by git?

Your answer: 

9. You did not implement the step you mentioned in question 8 and now you have committed and pushed your database's
secret key to the github. How will you remove the key from your git's commit history to avoid any misuse?

You answer:

---