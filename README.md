Make sure `echo $XDG_CONFIG_HOME` points to `~/.config`. If it doesnt, add `export XDG_CONFIG_HOME="$HOME/.config"` to your .bashrc file.
These configs require modern versions of tmux. It's reccomended to build from the tmux/tmux repo. There are instructions on how to do so in their README.
if these requirements are met, then do:
```bash
git clone https://github.com/D-H0f/tmux_config ~/.config/tmux
rm -rf ~/.config/tmux/.git
```
If there are any problems downloading the packages with this repository, they are downloaded from github at [tmux-plugins](https://github.com/tmux-plugins/).
