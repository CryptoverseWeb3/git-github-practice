# git-github-practice

## ⭐ HOW TO MAKE A PULL REQUEST:

**1.** Start by making a Fork of the [**git-github-practice**](https://github.com/cryptoverseWeb3/git-github-practice) repository. Click on the <a href="https://github.com/cryptoverseWeb3/git-github-practice/fork"><img src="https://i.imgur.com/G4z1kEe.png" height="21" width="21"></a>Fork symbol at the top right corner.

**2.** Clone your new fork of the repository in the terminal/CLI on your computer with the following command:
```bash
git clone https://github.com/<your-github-username>/git-github-practice
```

**3.** Navigate to the newly created git-github-practice project directory:
```bash
cd git-github-practice
```

**4.** Set upstream command:

```bash
git remote add upstream https://github.com/CryptoverseWeb3/git-github-practice.git
```

**5.** Create a new branch:
```bash
git checkout -b YourBranchName
```

**6.** Sync your fork or your local repository with the origin repository:
- In your forked repository, click on "Fetch upstream"
- Click "Fetch and merge"
### Alternatively, Git CLI way to Sync forked repository with origin repository:

```bash
git fetch upstream
```

```bash
git merge upstream/main
```

### [GitHub Docs](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-on-github) for Syncing

**7.** Make your changes to the source code.
  - Add you name in [Contributors.md](Contributors.md)
  - Example:
    ```markdown
    - [Kabir](https://github.com/kabir0x23)
    ```

**8.** Stage your changes and commit:

⚠️ **Make sure** not to commit `package.json` or `package-lock.json` file, until and unless you have installed the new packages.

⚠️ **Make sure** not to run the commands `git add .` or `git add *`. Instead, stage your changes for each file/folder

```bash
git add Contributors.md
```

```bash
git commit -m "<your_commit_message>"
```

**9.** Push your local commits to the remote repository:

```bash
git push origin YourBranchName
```

**10.** Create a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!

**11.** **Congratulations!** You've made your first contribution to [**git-github-practice**](https://github.com/cryptoverseWeb3/git-github-practice/graphs/contributors)! 🙌🏼

**_:trophy: After this, the maintainers will review the PR and will merge it if it helps move the git-github-practice project forward. Otherwise, it will be given constructive feedback and suggestions for the changes needed to add the PR to the codebase._**

---

- We help and encourage each other to contribute to open source little and often 😄.
- Feel free to check out other cool open-source repositories and communities:
    - [kabir0x23](https://github.com/kabir0x23)
    - [Cryptoverse Web3](https://github.com/CryptoverseWeb3)
    - [Thecyberworld](https://github.com/thecyberworld).



---