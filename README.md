# UnityGithubTest
Repo for testing github plugin for Unity 2018.2.14f1 in macOS High Sierra

1. Import Unity github to unity from the asset store
2. Inside Unity github window, in settting tabs, fill all the information about your account and your remote origin URL for your
github repo
3. Make a commit in the History tab
4. Push the commit to the github repo

Solving
fatal: could not read Username for 'https://github.com':Device not configured

1. Open a terminal 
2. Go to the folder of your project using cd directory
3. use the command git remote add origin https://github.com/angelhdz45/UnityGithubTest.git
4. use the command git push -u origin master
5. Github ask for your username and password
6. Maybe there will be the next message, "This repository is configured for Git LFS but 'git-lfs' ....... and more
(Ignore the message error and)
7. Try again to push the commit inside Unity 
8. Commit already publish to your github repo
