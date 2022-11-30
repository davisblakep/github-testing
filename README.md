# github-testing

Wow, this is great!

1. Clone the repo into whatever folder you would like:
   git clone [url]

2. Get into the directory that was created from the clone from Terminal, Command Line, etc.

3. If you want to create a branch and use it:
   git checkout -b [name of branch]

4. Once you save your code files:
   git add .

5. Next, add a commit message:
   git commit -m [description of what you did]

6. To push the branch code to Github (or any other Git repo site):
   git push origin [branch name]

7. If you want to merge that branch into the main branch, use Github and go to the pull requests tab.
   Click on the Create Pull Request option, then use the Merge Pull Request option to merge into Main.

8. On your local machine, switch back to main if you would like to update your local main:
   git checkout main

9 Pull latest code back into your main branch:
git pull

Tips:
-Add then commit often
-Push at least once a day (helps if anything on your computer gets corrupted after pushing)
-Merge main into your working branch at least once a day in the morning if other people are merging into main (will help prevent merge conflicts)

-Steps to merge main into your working branch:

1. git checkout main
2. git pull
3. git checkout [name of your working branch]
4. git merge main
