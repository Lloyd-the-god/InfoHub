# Contribution Guidelines📃

This documentation contains guidelines that should be followed while making your contribution(s):

### Fork the repository
Use the fork button at the top right of the repository to fork this repository. By doing this, a copy of the project is created in your personal account.

### Clone the repository
Making a copy of a repository on your local machine is known as "cloning" it. Once you've forked the repository, you can clone it by clicking the green "code" button, copying the repository's URL from the drop-down box, and then running the following command in your git bash terminal: ```git clone https://github.com/Topman-14/InfoHub.git```

### Change directory
After that, enter the following command in your terminal to switch to the repository's directory (folder) that we just cloned:             `cd InfoHub`

### Add an Upstream Repo
Upstream basically refers to the original repo or a branch. When you clone a repo from Github, for instance, the remote Github repo is upstream for the cloned local copy. We use the following command to add the upstream to our repository using the main project repo URL:
`git remote add upstream https://github.com/Topman-14/InfoHub.git`

### Create a new branch
To create a new branch where you will make changes, use this command: `git checkout -b <branch-name>`. After creating the branch, switch to the newly created branch using: `git checkout -b <branch-name>`

### Making changes
- If you have any feature that you'd love to be added to the app or you noticed any bug, kindly use these [templates](.github/ISSUE_TEMPLATE) to open an issue.
- If you have been assigned an issue, endeavour to create a new branch and make your changes. For your code to be merged, refrain from pushing from the main branch.
- Upon making a pull request, your pull request should only contain a change at a time. Raise different pull requests for the other changes you will like to make.
- Kindly be informed that any PR that modifies someone else's lines(s) of code won't be merged unless it is absolutely necessary.
- Contributions of any kind will be much appreciated too, be it fixing grammatical errors, fixing broken links, etc. If the contribution is  minimal, go ahead to create a pull request, else raise an issue before making your contribution.

### Commit messages
- When writing your commit messages:
    - Keep it short and concise. 
    - Also, write your commit messages in the imperative: "add navbar" and not "added navbar" or "adds navbar". This convention matches up with commit messages generated by commands like git merge and git revert.
    - Your commit message should not end with a period `.`

#### Finally, if you are just getting started to open-source contributions, here is a [repository](https://github.com/Mannuel25/Nutshell-GitHub) that could come in handy.

##### Happy Contribution 🚀