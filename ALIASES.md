# ALIASES

## Shell
- `c` - `clear`
- `v` - `nvim`
- `ip` - `dig +short myip.opendns.com @resolver1.opendns.com`
- `localip` - `ipconfig getifaddr en1 || ipconfig getifaddr en0`
- `tml` - `tmux list-sessions`
- `tma` - `tmux -2 attach -t $1`
- `tmk` - `tmux kill-session -t $1`

## Eza
- `ls` - `eza --icons=auto --hyperlink --group-directories-first`
- `la` - `eza --icons=auto --hyperlink --group-directories-first -la`

## Kitty
- `ks` - `ksession basic`
- `ksd` - `ksession docker`
- `ksg` - `ksession git`

## Git
- `g` - `git`
- `gb` - `git branch`
- `gba` - `git branch --all --verbose`
- `gbc` - `git checkout -b`
- `gbd` - `git branch --delete`
- `gbD` - `git branch --delete --force`
- `gbl` - `git branch --verbose`
- `gc` - `git commit --verbose`
- `gca` - `git commit --verbose --all`
- `gcm` - `git commit --message`
- `gcam` - `git commit --all --message`
- `gco` - `git checkout`
- `gcF` - `git commit --verbose --amend`
- `gf` - `git fetch`
- `gfa` - `git fetch --all`
- `gg` - `git grep`
- `gia` - `git add`
- `giA` - `git add --patch`
- `giu` - `git add --update`
- `gl` - `git log --topo-order --pretty=format:"%C(bold)Commit:%C(reset) %C(green)%H%C(red)%d%n%C(bold)Author:%C(reset) %C(cyan)%an <%ae>%n%C(bold)Date:%C(reset)   %C(blue)%ai (%ar)%C(reset)%n%+B"`
- `glg` - `git log --topo-order --graph --pretty=format:"%C(green)%h%C(reset) %s%C(red)%d%C(reset)%n"`
- `gm` - `git merge`
- `gmC` - `git merge --no-commit`
- `gmF` - `git merge --no-ff`
- `gma` - `git merge --abort`
- `gp` - `git push`
- `gpf` - `git push --force-with-lease`
- `gpF` - `git push --force`
- `gpc` - `git push --set-upstream origin "$(git-branch-current 2> /dev/null)"`
- `gpp` - `git pull origin "$(git-branch-current 2> /dev/null)" && git push origin "$(git-branch-current 2> /dev/null)"`
- `gr` - `git rebase`
- `gra` - `git rebase --abort`
- `grc` - `git rebase --continue`
- `gri` - `git rebase --interactive`
- `grs` - `git rebase --skip`
- `gs` - `git stash`
- `gsa` - `git stash apply`
- `gsx` - `git stash drop`
- `gsl` - `git stash list`
- `gsp` - `git stash pop`
- `gsr` - `git-stash-recover`
- `gss` - `git stash save --include-untracked`
- `gt` - `git tag`
- `gtl` - `git tag --list`
- `gws` - `git status --ignore-submodules=none --short`
- `gwS` - `git status --ignore-submodules=none`
- `gwd` - `git diff --no-ext-diff`
- `gwD` - `git diff --no-ext-diff --word-diff`

## Docker
- `dk`: `docker`
- `dka`: `docker attach`
- `dkb`: `docker build`
- `dke`: `docker exec`
- `dkE`: `docker exec -it`
- `dkps`: `docker ps`
- `dkr`: `docker run`
- `dkR`: `docker run -it --rm`
- `dkRM`: `docker system prune --volumes`
- `dkrm`: `docker rm`
- `dkrmi`: `docker rmi`
- `dkC`: `docker container`
- `dki`: `docker images`
- `dkI`: `docker image`
- `dkV`: `docker volume`
- `dkVls`: `docker volume ls`
- `dkVrm`: `docker volume rm`
- `dkc`: `docker compose`
- `dkcb`: `docker compose build`
- `dkcB`: `docker compose build --no-cache`
- `dkcd`: `docker compose down`
- `dkce`: `docker compose exec`
- `dkck`: `docker compose kill`
- `dkcl`: `docker compose logs`
- `dkcps`: `docker compose ps`
- `dkcr`: `docker compose run`
- `dkcR`: `docker compose run --rm`
- `dkcu`: `docker compose up`
- `dkcU`: `docker compose up -d`
- `dkcx`: `docker compose stop`
