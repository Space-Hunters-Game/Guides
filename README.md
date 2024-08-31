# Space Hunters: The Reborn

## 📃Commit Messages

* __[WIP]__ - Work in progress
* __[FTR]__ - New feature
* __[SCR]__ - Security issue fix
* __[CLP]__ - Changes that do not alter functionality, but improve code style and readability.
* __[CRO]__ - Content Rate Optimization
* __[TST]__ - Add test suite for slider component
* __[!!!]__ - Deprecated. Can only be used with [FTR]
* __[FIX]__ for bug fixes: mostly used in stable version but also valid if you are fixing a recent bug in development version;
* __[RFR]__ for refactoring: when a feature is heavily rewritten;
* __[ADD]__ for adding new modules;
* __[REM]__ for removing resources: removing dead code, removing views, removing modules, …;
* __[REV]__ for reverting commits: if a commit causes issues or is not wanted reverting, it is done using this tag;
* __[MOV]__ for moving files: use git move and do not change content of moved file, otherwise Git may loose track and history of the file; also used when moving code from one file to another;
* __[REL]__ for release commits: new major or minor stable versions;
* __[IMP]__ for improvements: most of the changes done in the development version are incremental improvements not related to another tag;
* __[MERGE]__ for merge commits: used in forward port of bug fixes but also as main commit for feature involving several separated commits;
* __[I18N]__ for changes in translation files;
* __[DOCS]__ Update documentation such as the README or other markdown files with new project information

> [!WARNING]  
> PRs with the name and description [if possible, otherwise name of the assigned task].

### Examples

* __[FIX]__ Throw HttpStatusExceptions in BackendController
* __[FTR]__ Add option to hide BE search box in list mod
* __[!!!] [FTR]__ Remove login with Facebook
* __[SCR]__ SQL Injection vulnerability in prepared statements
* __[CRO]__ Increase font-size for phone CTA's
* __[RFR]__ Edit scripts gulp task
* __[WIP]__ Change header colors
* __[CLP]__ Fix indentation for styles.js
* __[TST]__ Add unit test for modal component
* __[DOCS]__ Update README with new project information

### Example with Branch Prefix 
Issue #456 is about user authentication. The branch name would be `feature/456-user-authentication`.

* **Commit messages would look like this**:
  ```text
  [WIP] Work in progress on #456
  [FIX] Throw HttpStatusExceptions in BackendController
  ```

## 🚀Best Practices for Code Review


A study of a Cisco Systems programming team revealed that a review of 200–400 LOC over 60 to 90 minutes should yield 70–90% defect discovery.
So, if a pull request has big diffs, it can be problematic.
In addition, large pull requests will take more time and will probably block other developers who may be depending on the code.

### Conflict resolution
Eventually, the pull request author and the reviewer will disagree. That is perfectly fine and actually a sign of good team dynamics. However, what is not fine is having endless discussions about it or one developer overriding the other because of reasons like personal opinions, seniority, access rights, etc.

It’s better to prevent these situations from happening and have a conflict resolution strategy.
One particular method that works well is to always require at least two code reviewers.
In those cases, it’s simply the majority vote that counts.

## 📖Documentation

- [A successful Git branching model](https://nvie.com/posts/a-successful-git-branching-model/)
- [Git feature branch workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)
- [Git Flow: A Successful Git branching model](https://gist.github.com/HeratPatel/271b5d2304de2e2cd1823b9b62bf43e0)
- [Best Practices for Code Review](https://leoneperdigao.medium.com/pull-request-best-practices-fa20f7daeb3c)
- [Git Cheatsheet [PDF📕]](https://github.com/ruhulmus/Git-Flow-Architecture/blob/main/git_cheatsheet.pdf)
