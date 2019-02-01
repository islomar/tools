# Tools

## Git hooks
The current configured Git hooks are:
* **pre-push**:  it will run all the tests before pushing

**How to install them for a specific repo:**
1. `chmod +x configure_git_hooks.sh`
2. `.\configure_git_hooks.sh <repo-name>`, where `<repo-name>` is the repo where you want to configure the Git hooks

**How to install the hooks for all the repos**
1. Create a folder for your centralized repos and copy all the hooks there: `cp -pr ./hooks /[path_to_my_centralized_hooks]` 
2. `git config --global core.hooksPath /[path_to_my_centralized_hooks]/hooks`

## Dotfiles
* `.alias`