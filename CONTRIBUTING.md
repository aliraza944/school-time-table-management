
## Contributing

Hi there! We're thrilled that you'd like to contribute to this project. Your help is essential for keeping it great.


## Issues and PRs

If you have suggestions for how this project could be improved, or want to report a bug, add a feature, open an issue! We'd love all and any contributions. If you have questions, too, we'd love to hear them.

We'd also love PRs. If you're thinking of a large PR, we advise opening up an issue first to talk about it, though! Look at the links below if you're not sure how to open a PR.

## How to Contribute

- Take a look at the Existing [Issues](https://github.com/aliraza944/school-time-table-management/issues) or create your own Issues!
- Fork the Repo and create a Branch for any Issue that you are working upon.
- Create a Pull Request which will be promptly reviewed and suggestions would be added to improve it.
- Add Screenshots to help us know what this is all about.

## How to make a Pull Request

**1.** Fork the repository by clicking on the <a href="https://github.com/aliraza944/school-time-table-management"><img src="https://img.icons8.com/ios/24/000000/code-fork.png"></a> symbol at the top right corner.

**2.** Clone the forked repository.

```
   cd Desktop
```

```
   git clone https://github.com/aliraza944/school-time-table-management.git
```

**3.** Navigate to the project directory and initialize the git.

```
   cd school-time-table-management
```

```
   git init
```

**4.** Create a new branch:

```
   git checkout -b YourBranchName
```

**5.** Make changes in source code.

**6.** Stage your changes and make a commit

```
   git add .
```

```
   git commit -m "<your_commit_message>"
```

**7.** Push your local commits to the remote repo.

```
   git push origin YourBranchName
```

**8.** Create a [PR](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)

**9.** If anyone contribute to this repository, then the changes will not reflect in your local repository. For that:

**10.** Setup a reference(remote) to the original repository to get all the changes from the remote.

```
   git remote add upstream https://github.com/aliraza944/school-time-table-management.git
```

**11.** Check the remotes for this repository.

```
   git remote -v
```

**12.** Fetching from the remote repository will bring in its branches and their respective commits.

```
   git fetch upstream
```

**13.** Make sure that you're on your master branch.

```
   git checkout master
```

**14.** Now that we have fetched the upstream repository, we want to merge its changes into our local branch. This will bring that branch into sync with the upstream, without losing our local changes.

```
   git merge upstream/master
```

**15.** Or you can club step 12th and 14th together using:-

```
   git pull upstream main
```

