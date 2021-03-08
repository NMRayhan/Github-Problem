# Github-Problem
1/Problem
#remote: Repository not found.
#fatal: repository 'https://github.com/MyRepo/project.git/' not found
Solution
I uninstalled the git credentials manager and reinstalled it and then I could easily pull and push to the repository. Here are the commands

$ git credential-manager uninstall
$ git credential-manager install
