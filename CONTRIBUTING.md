# Contributing Guidelines

Some basic conventions for contributing to this project.

### General

Please make sure that there aren't existing pull requests attempting to address the issue mentioned. Likewise, please check for issues related to update, as someone else may be working on the issue in a branch or fork.

* Non-trivial changes should be discussed in an issue first
* Develop in a topic branch, not master
* Squash your commits

### Commit Message Format

Each commit message should include a **type**, a **scope** and a **subject**:

```
 <type>: <subject>
```

Lines should not exceed 100 characters. This allows the message to be easier to read on github as well as in various git tools and produces a nice, neat commit log ie:

```
 #271 ADD: add style config and refactor to match
 #270 FIX: only override publicPath when served by webpack
 #269 ADD: replace eslint-config-airbnb
 #268 FIX: allow user to configure webpack stats output
```

#### Type

Must be one of the following:

* **ADD**: Add a new feature
* **FIX**: A bug fix
* **DOCS**: Documentation only changes
* **STYLE**: Changes that do not affect the meaning of the code (white-space, formatting, missing
  semi-colons, etc)
* **REFACTOR**: A code change that neither fixes a bug or adds a feature
* **TEST**: Adding missing tests
* **CHORE**: Changes to the build process or auxiliary tools and libraries such as documentation
  generation

#### Subject

The subject contains succinct description of the change:

* use the imperative, present tense: "change" not "changed" nor "changes"
* don't capitalize first letter
* no dot (.) at the end
