## 👨‍💻 Prerequisite Skills to Contribute

Basics:
- [Git](https://git-scm.com/)
- [Markdown](https://www.markdownguide.org/basic-syntax/)

---

## 💥 How to Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/cryptoverseWeb3/git-github-practice/pulls)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/cryptoverseWeb3/)

- Take a look at the existing [Issues](https://github.com/cryptoverseWeb3/git-github-practice/issues) or [create a new issue](https://github.com/cryptoverseWeb3/git-github-practice/issues/new/choose)!
- [Fork the Repo](https://github.com/cryptoverseWeb3/git-github-practice/fork). Then, create a branch for any issue that you are working on. Finally, commit your work.
- Create a **[Pull Request](https://github.com/cryptoverseWeb3/git-github-practice/compare)** (_PR_), which will be promptly reviewed and given suggestions for improvements by the community.
- Add screenshots or screen captures to your Pull Request to help us understand the effects of the changes proposed in your PR.

---

## ⭐ HOW TO MAKE A PULL REQUEST:

**1.** Start by making a Fork of the [**git-github-practice**](https://github.com/cryptoverseWeb3/git-github-practice) repository. Click on the <a href="https://github.com/CryptoverseWeb3/git-github-practice/fork"><img src="https://i.imgur.com/G4z1kEe.png" height="21" width="21"></a>Fork symbol at the top right corner.

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
git remote add upstream https://github.com/cryptoverseWeb3/git-github-practice.git
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

## Style Guide for Git Commit Messages :memo:

**How you can add more value to your contribution logs:**

- Use the present tense. (Example: "Add feature" instead of "Added feature")
- Use the imperative mood. (Example: "Move item to...", instead of "Moves item to...")
- Limit the first line (also called the Subject Line) to _50 characters or fewer_.
- Capitalize the Subject Line.
- Separate subject from body with a blank line.
- Do not end the subject line with a period.
- Wrap the body at _72 characters_.
- Use the body to explain the _what_, _why_, _vs_, and _how_.
- Reference [Issues](https://github.com/cryptoverseWeb3/git-github-practice/issues) and [Pull Requests](https://github.com/cryptoverseWeb3/git-github-practice/pulls) liberally after the first line.

---

## 💥 Issues

In order to discuss changes, you are welcome to [open an issue](https://github.com/cryptoverseWeb3/git-github-practice/issues/new/choose) about what you would like to contribute. Enhancements are always encouraged and appreciated.

## All the best! 🥇

[![built with love](https://forthebadge.com/images/badges/built-with-love.svg)](https://community.cryptoverseWeb3.com)