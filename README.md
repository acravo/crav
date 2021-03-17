<!-- markdownlint-disable MD032 MD033-->
# **Josee9988's Github Project Template**

## **What is this template all about?** 🔥

* This template can be used as a base layer for any of your future repositories/projects.
* Make your project easy to maintain with **7 issue templates**.
* Make your _community healthier_ with all the guides like code of conduct, contributing, support, security...
* Learn more with the [official Github guide on creating repositories from a template](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template).
* To start using it; "**[click use this template](https://github.com/Josee9988/project-template/generate)**", create your new repository,
clone your new repository and execute the `EXECUTEME.sh` shell script to personalize the markdowns with your private details. Check how to execute it [here](https://asciinema.org/a/398761).
* All the markdown follows [MarkdownLint rules](https://github.com/DavidAnson/markdownlint).

---

## **How to use it as a template for my new repositories?** 🚀

1. To create a new repository from this template [generate your new repository from this template](https://github.com/Josee9988/project-template/generate)
for more information or guidance follow the [Github guide](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template).
2. Clone your repo and cd into it.
3. Execute the `EXECUTEME.sh` shell script to customize the files with your data.
  
    Use `bash EXECUTEME.sh` or `./EXECUTEME.sh`.

    ```bash
    bash EXECUTEME.sh # execute the setup script.
    ```

      Additionally watch *[this video](https://asciinema.org/a/398761)* to see **how to execute the script**.

4. **Review** every single file and **customize** it as you like.
5. Build your project. 🚀

⚠️ _Customize every file to fit your requirements_ ⚠️

---

## **What does it include?** 📚

1. An **`EXECUTEME.sh`** script that **MUST be executed right when you clone your repository**.
The script will replace Jose's username and email (the author) with yours.
It will remove all the _content_ from the CHANGELOG.md and write the basic structure for you to write your own.
The script will also remove all the _content_ from the README.md, and it will remove the `LICENSE` file to let you freely choose your own and will auto remove itself (the script).
1. A `.gitignore` ignoring Jetbrains/Intellij and VSCode IDE's folders and Linux files.
1. A CHANGELOG.md file that the `EXECUTEME.sh` script will remove to let you write your own.
1. A README.md file that its content will be erased when you run the `EXECUTEME.sh` script.
1. A fully customized `.github` folder with:
   1. A [funding](/.github/FUNDING.yml) section to display a sponsor button (should be manually modified). [Learn more with the Github guide](https://docs.github.com/en/github/administering-a-repository/displaying-a-sponsor-button-in-your-repository)
   1. A [issue_label_bot.yaml](/.github/issue_label_bot.yaml) file to use the popular Github bot. [Activate it or check its documentation](https://github.com/marketplace/issue-label-bot).
   1. A [CONTRIBUTING](/.github/CONTRIBUTING.md) explaining how to contribute to the project. [Learn more with the Github guide](https://docs.github.com/en/github/building-a-strong-community/setting-guidelines-for-repository-contributors).
   1. A [SUPPORT](/.github/SUPPORT.md) explaining how to support the project. [Learn more with the Github guide](https://docs.github.com/en/github/building-a-strong-community/adding-support-resources-to-your-project).
   1. A [SECURITY](/.github/SECURITY.md) with a guide on how to post a security issue. [Learn more with the Github guide](https://docs.github.com/es/github/managing-security-vulnerabilities/adding-a-security-policy-to-your-repository).
   1. A [CODE_OF_CONDUCT](/.github/CODE_OF_CONDUCT.md) with a basic code of conduct. [Learn more with the Github guide](https://docs.github.com/en/github/building-a-strong-community/adding-a-code-of-conduct-to-your-project).
   1. A [PULL_REQUEST_TEMPLATE](/.github/pull_request_template.md) with a template for your pull request that closes issues with keywords. [Learn more with the Github guide](https://docs.github.com/es/github/building-a-strong-community/creating-a-pull-request-template-for-your-repository).
   1. Multiple [issues templates](/.github/ISSUE_TEMPLATE). [Learn more with the Github guide](https://docs.github.com/en/github/building-a-strong-community/configuring-issue-templates-for-your-repository).
      1. A [config.yml](/.github/ISSUE_TEMPLATE/config.yml) with the config and information about the issue templates.
      1. A [Blank issue template](/.github/ISSUE_TEMPLATE) with the super basic stuff, all the issues should contain.
      1. A [Bug issue template](/.github/ISSUE_TEMPLATE/1-bug-report.md).
      1. A [Failing test issue template](/.github/ISSUE_TEMPLATE/2-failing-test.md).
      1. A [Documentation issue template](/.github/ISSUE_TEMPLATE/3-docs-bug.md).
      1. A [Feature request issue template](/.github/ISSUE_TEMPLATE/4-feature-request.md).
      1. A [Security report issue template](/.github/ISSUE_TEMPLATE/5-security-report.md).
      1. A [Question or support issue template](/.github/ISSUE_TEMPLATE/6-question-support.md).

---

### **Project tree** 🌲

```text
.
├── CHANGELOG.md
├── EXECUTEME.sh (will get removed)
├── .github
│   ├── CODE_OF_CONDUCT.md
│   ├── CONTRIBUTING.md
│   ├── FUNDING.yml
│   ├── issue_label_bot.yaml
│   ├── ISSUE_TEMPLATE
│   │   ├── 1-bug-report.md
│   │   ├── 2-failing-test.md
│   │   ├── 3-docs-bug.md
│   │   ├── 4-feature-request.md
│   │   ├── 5-security-report.md
│   │   ├── 6-question-support.md
│   │   └── config.yml
│   ├── ISSUE_TEMPLATE.md
│   ├── pull_request_template.md
│   ├── SECURITY.md
│   └── SUPPORT.md
├── .gitignore
├── LICENSE (will get removed)
└── README.md

2 directories, 20 files
```

---

## **Extra recommendations** 🕵️

* After **[generating your new repo with this template](https://github.com/Josee9988/project-template/generate)**, make sure to, right after you clone it, run the script `EXECUTEME.sh`.

* Then you will be presented with all the files modified with your project details and information. It is very important to **manually review every file** to check if it fits your requirements, and perform any necessary changes to customize the project as you want.

* If you are using **Windows** and you don't know how to execute the `EXECUTEME.sh` script:
  1. Install **[git for Windows](https://git-scm.com/download/win)**.
  2. Right-click on the git repository folder and click "*git bash here*".
  3. Then just perform *`bash EXECUTEME.sh`* **or** *`chmod u+x EXECUTEME.sh && ./EXECUTEME.sh`*.

---

## **Screenshots** 📷

A couple of screenshots to delight you before you use this template.

* All the issue templates.
<p align="center">
  <img width="70%" height="70%" src="https://i.imgur.com/BWOdDCb.png" alt="All the issue templates.">
</p>

* An issue template opened.
<p align="center">
  <img width="70%" height="70%" src="https://i.imgur.com/r5AiLWu.png" alt="Bug issue template opened.">
</p>

* Security policy
<p align="center">
  <img width="70%" height="70%" src="https://i.imgur.com/ArwDQTi.png" alt="Security issue.">
</p>

* Community profile at 100%
<p align="center">
  <img width="70%" height="70%" src="https://i.imgur.com/kRt3lPs.png" alt="Community profile.">
</p>

---

For the right maintenance of the CHANGELOG.md, we recommend this [VSCode extension](https://github.com/Josee9988/Changelog-and-Markdown-snippets)
and the read and understanding of the [keep a changelog guide](https://keepachangelog.com/en/1.0.0/).

If you liked it please, make sure to star this project. ❤️

Enjoy! 😃

> ⚠️Remember that this template should be reviewed and modified to fit your requirements.
> The script **EXECUTEME.sh** should be executed right when you clone your new repository.
> There will be files that will need manual revision⚠️

_Made with a lot of ❤️❤️ by **[@Josee9988](https://github.com/Josee9988)**_
