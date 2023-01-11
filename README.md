# [Husky](https://typicode.github.io/husky/#/)

## Install

```
npx husky-init && npm install
```

## Create a Git Hook

```
 npx husky add .husky/pre-commit
```

## pre-commit Hook

```
 npx husky add .husky/pre-commit
```

## Useful Hooks

```
"applypatch-msg": "echo \"[Husky] applypatch-msg\"",
"pre-applypatch": "echo \"[Husky] pre-applypatch\"",
"post-applypatch": "echo \"[Husky] post-applypatch\"",
"pre-commit": "echo \"[Husky] pre-commit\"",
"pre-merge-commit": "echo \"[Husky] pre-merge-commit\"",
"prepare-commit-msg": "echo \"[Husky] prepare-commit-msg\"",
"commit-msg": "echo \"[Husky] commit-msg\"",
"post-commit": "echo \"[Husky] post-commit\"",
"pre-rebase": "echo \"[Husky] pre-rebase\"",
"post-checkout": "echo \"[Husky] post-checkout\"",
"post-merge": "echo \"[Husky] post-merge\"",
"pre-push": "echo \"[Husky] pre-push\"",
"pre-receive": "echo \"[Husky] pre-receive\"",
"update": "echo \"[Husky] update\"",
"post-receive": "echo \"[Husky] post-receive\"",
"post-update": "echo \"[Husky] post-update\"",
"reference-transaction": "echo \"[Husky] reference-transaction\"",
"push-to-checkout": "echo \"[Husky] push-to-checkout\"",
"pre-auto-gc": "echo \"[Husky] pre-auto-gc\"",
"post-rewrite": "echo \"[Husky] post-rewrite\"",
"sendemail-validate": "echo \"[Husky] sendemail-validate\"",
"fsmonitor-watchman": "echo \"[Husky] fsmonitor-watchman\"",
"p4-changelist": "echo \"[Husky] p4-changelist\"",
"p4-prepare-changelist": "echo \"[Husky] p4-prepare-changelist\"",
"p4-post-changelist": "echo \"[Husky] p4-post-changelist\"",
"p4-pre-submit": "echo \"[Husky] p4-pre-submit\"",
"post-index-change": "echo \"[Husky] post-index-change\""
```

## Helpful Link

https://www.freecodecamp.org/news/how-to-add-commit-hooks-to-git-with-husky-to-automate-code-tasks/

Clean Code:
https://myas92.medium.com/clean-code-tips-in-javascript-typescript-aabcc4bcb96c
