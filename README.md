# Dotfiles

### Description

A collection of bash profile setup files, including aliases, prompt and ssh config and others.

### Usage

Simply source the .imports file in your ~/.bash_profile to use.

### What Does It Do?

#### Aliases

Here's a non-exhaustive list of aliases this provides:

```bash
commit='git add --all && git commit -m $&'
p='git push'

l='ls -lta'
c='cd ~/Code'
```
#### Prompt

The .prompt file configures the prompt with the format:

```bash
$current_directory on $git_branch(*) <pull-required>
```

where '*' indicates whether the branch has uncommitted changes or not.
