# Mac notification git hooks

Git hooks that trigger Notification Center notifications

## Installation

Install [terminal-notifier](https://github.com/alloy/terminal-notifier)
```
brew install terminal-notifier
```

Checkout the repo
```
git clone git@github.com:richardpeng/git-templates.git ~/.git-templates
```

Use this repo as git's global template directory
```
git config --global init.templatedir '~/.git-templates'
```

Re-initialize each repository to install the hooks
```
git init
```
