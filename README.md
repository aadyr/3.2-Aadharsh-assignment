# 3.2-Aadharsh-assignment

# Aadharsh-3.2

# what is GitHub Authentication and how what methods available to be implemented?

To keep your account secure, you must authenticate before you can access certain resources on GitHub. When you authenticate to GitHub, you supply or confirm credentials that are unique to you to prove that you are exactly who you declare to be.

You can access your resources in GitHub in a variety of ways: in the browser, via GitHub Desktop or another desktop application, with the API, or via the command line. Each way of accessing GitHub supports different modes of authentication.

`Username and password with two-factor authentication`
`Personal access token`
`SSH key`



# Authenticating in your browser

If you're a member of an enterprise with managed users, you will authenticate to GitHub in your browser using your IdP. For more information, see "About Enterprise Managed Users" in the GitHub Enterprise Cloud documentation.

If you're not a member of an enterprise with managed users, you will authenticate using your GitHub.com username and password. You may also use two-factor authentication and SAML single sign-on, which can be required by organization and enterprise owners.


# Update the Readme file to contain least 15 github commands and what are the usage of them?


Git Command |   Used for | 
| :--- | ---: | 
`git add [file]` | add a file as it looks now to your next commit (stage)| 
`git status `| show modified files in working directory, staged for your next commit | 
`git diff `| diff of what is changed but not staged|
`git clone` [url]| retrieve an entire repository from a hosted location via URL|
`git branch`|list your branches. a * will appear next to the currently active branch|
`git branch `[branch-name]|create a new branch at the current commit|
`git checkout`|switch to another branch and check it out into your working directory|
`git merge` [branch]|merge the specified branch’s history into the current one|
`git pull`|fetch and merge any commits from the tracking remote branch|
`git push` [alias] [branch]|Transmit local branch commits to the remote repository branch|
`git fetch` [alias]|fetch down all the branches from that Git remote|
`git reset` [file]|unstage a file while retaining the changes in working directory|
`git commit` -m “[descriptive message]”|commit your staged content as a new commit snapshot|
`git init`|initialize an existing directory as a Git repository|      
`git log`|show all commits in the current branch’s history|

# What are the 4 Github commands that you think you will use the most in the real project and why? Explain it on the readme file.

Git pull, 
Git push,
Git commit,
Git branch.

`Git pull, Git push, Git commit`
Since changes to any repository involves fetching and merging any commits from the remote brance, making changes to it, and pushing the changes back these commands will be frequently used.
`Git branch [branch-name]`
Also in an  real life scenario there is likely more than one person working on a given repository working on a different feature and hence Git brance will be used as well