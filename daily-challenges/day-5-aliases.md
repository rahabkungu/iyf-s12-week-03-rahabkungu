# Day 5: Terminal aliases for common commands

## Useful Git and Navigation aliases
Add these aliases to your `~/.bashrc` or `~/.bash_profile` to speed up your workflow:

1. **Quick status & diff:**
- `alias gs="git status"`
- `alias ga="git add"`
- `alias gc="git commit -m"`
- `alias gp="git push origin main"`

2. **Directory Navigation:**
- `alias ..="cd.."`
- `alias ...="cd../.."`

3. **How to activate them:**
```bash
source ~/.bashrc
```