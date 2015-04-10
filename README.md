# BARE BONES GIT

Let the gitwich making begin.

## GIT SHIT

- `git init`: initializes repo. only when starting project.
- `git status`: shows status of repo
- `git add <path to filename>`: adds file to staging from working dir
- `git commit -m "commit message"`: commits changes in staging to git history
- `git reset [<path to filename>]`: removes changes from staging
- `git diff [--staged] [<path to filename>]`: compares working dir to history (staging if flagged)
- `git log`: show log
- `git config --global [thing.thing] ["stuff"]`: shows what's in .gitconfig; if " ", then changes it
- `git remote [-v]`: shows remote (remote touchable copies of repo)
- `git push <remote name> <branch>`: pushes commits to heaven
- `git clone <git repo address>`: clones remote repo
- `git pull <remote name> <branch>`: pull changes from a remote

## OTHER USEFUL SHIT

- `subl <path to filename>`: opens file in sublime (requires doing something like [this](https://www.sublimetext.com/docs/2/osx_command_line.html))
