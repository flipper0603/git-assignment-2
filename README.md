# git-assignment-2

1. To start, fork this repository on your github.
2. Then, open VSCode, open a terminal, and clone the fork you just made
3. Then, run: cd git-assignment-2
4. Then, open the folder git-assignment-2 in VSCode
5. Open the README.md file, which is this file, you will edit this on VSCode
6. INDUSTRY VOCAB: Origin = your fork (your_user/git-assignment-2)  &nbsp;&nbsp;&nbsp;  Upstream = my repo (josephor1271/git-assignment-2)

## Part 1 (Branch then merging within your fork)
1. First, you will make a branch named writing
2. To do this, you can run, git checkout -b writing
3. To check which branch you are on, you can run git status, it should say on branch: writing
4. Push this branch to GitHub using git push -u origin writing
5. Then, you will make some changes to the line below.
6. *WRITE YOUR SCHOOL + INTENDED MAJOR HERE*
7. Add, commit, and push those changes to GitHub using your terminal
8. Now, make a pull request on GitHub from origin's (your fork's) writing branch, to your origin's (your fork's) main branch. Make sure that you are not pull requesting upstream (my copy of the repository), my username should not appear at all in the pull request. Will look something like main <- writing
9. Merge the pull request on GitHub (if it doesn't let you, then you pull requested upstream, instead of origin)
10. Now, on GitHub, your main branch and your writing branch should look identical
11. Congrats, you have made changes using a branch, and merged them into the main branch!

## Part 2 (Making a pull request to my repository)
1. At this point, GitHub reflects the changes you made merging your main branch and your writing branch. However, if you switch to your main branch on VSCode using git checkout main, you will not see the new changes. In order to get the changes from GitHub onto your local copy, you run git pull. Before running git pull, make sure you are on the main branch by using git status. Now you have the changes from GitHub and you are on the main branch.
2. *WRITE A CONTROVERSIAL OPINION YOU HAVE HERE*
3. Add, commit, and push those changes to GitHub using your terminal
4. Now your controversial statement should show up on the main branch of your fork on GitHub
5. On GitHub, on your fork, navigate to pull requests and open a new pull request. This pull request should be from the main branch of your fork to the main branch of my repository. So it will be something like josephor/git-assignment-2 main <- your_username/git-assignment-2 main
6. Make sure you send the pull request
7. All done
8. After the due date, I will accept someone's pull request, ideally a controversial opinion I agree with

## Submission
Submit a link to your fork of this repository to google classroom

## Optional Challenge (Fix a Typo Using a Branch)

This part is optional, but recommended if you finish early.

1. Make sure you are on the `main` branch:
git status
If not:
git checkout main

2. Create a new branch called `typo-fix`:
git checkout -b typo-fix

3. Find **any typo or wording you think could be improved** in this README and fix it.

4. Add, commit, and push your changes:
git add README.md
git commit -m "Fix typo in README"
git push -u origin typo-fix

5. On GitHub, open a pull request **from `typo-fix` to `main` within your fork**  
(do **not** include my repository in this pull request).

6. Merge the pull request.

7. After merging, your `main` branch and your `typo-fix` branch should be identical.

If you complete this, you have now practiced the full GitHub workflow twice:
branch → commit → push → pull request → merge.
   
