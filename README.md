# git-coveo
git scripts, hooks and utilities

# installation

```bash
git clone https://github.com/coveo/git-coveo.git $HOME/Developer/git-coveo

ln -s $HOME/Developer/git-coveo/hooks $HOME/.githooks

git config --global core.hooksPath $HOME/.githooks

git config --global jira.url https://myjira.atlassian.net/browse
```
