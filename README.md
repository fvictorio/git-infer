# git-infer

Commit your changes with an auto-generated message.

## Installation

### Antigen

`antigen bundle fvictorio/git-infer`

### Manually

Clone this repository and add it to your `$PATH`.

## Examples

```
$ echo node_modules > .gitignore

$ git add .gitignore

$ git infer # this will create a commit
[master (root-commit) 2b34524] Add .gitignore
 1 file changed, 1 insertion(+)
 create mode 100644 .gitignore

$ echo build >> .gitignore

$ git add .gitignore

$ git infer
[master 0b7132a] Update .gitignore
 1 file changed, 1 insertion(+)
```

## Options

- `-a`: Include all tracked files.
- `-A`: Include all files, even the untracked.

## Disclaimer

The vast majority of times, you shouldn't use this.
