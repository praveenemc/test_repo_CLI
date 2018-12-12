# test_repo_CLI

HTTPS:
https://github.com/praveenemc/test_repo_CLI.git

SSH:
git@github.com:praveenemc/test_repo_CLI.git

To create a new repository on the command line
echo "# test_repo_CLI" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:praveenemc/test_repo_CLI.git
git push -u origin master


…or push an existing repository from the command line
git remote add origin git@github.com:praveenemc/test_repo_CLI.git
git push -u origin master

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

###NOTE:
You would need to create the repo on GitHub before pushing to it.
You may create a repository on GitHub either from an internet browser or using the GitHub command line API as follows:
curl -u 'USER' https://api.github.com/user/repos -d '{"name":"REPO"}'
