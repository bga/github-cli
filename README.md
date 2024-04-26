# Github command line interface

Interact with Github servers via *curl* requests to their [REST API v1](https://docs.github.com/en/rest).

Use `./github` to show available actions.  
Use `./github <action>` to show required parameters.  
Use `./github <action> <argument> ...` to run actions.

## Available actions include to
- [x] create/fork/delete/list/query user/organization **repositories**
- [ ] add/remove/list repository **collaborators**
- [ ] create/list organization **teams**
- [ ] add/remove/list organization **team members**
- [ ] add/remove organization **team repositories**
- [ ] fetch **raw** file content

## Setup
- Github server URL
    - Required in the form `github.com`
    - Via environment variable or file in this directory
- Github API token
    - Create at `https://YOUR.GOGS.SERVER/settings/tokens`
    - Via environment variable or file in this directory

(See `config` section in `./github`)

---

*The REST API does not yet allow some actions (like organization team deletion).  
Similarly, this cli does not cover all avilable actions &mdash; pull requests are welcome!*
