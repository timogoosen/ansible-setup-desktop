### Usage:

To use:

```

venv $) ansible-playbook -i hosts site.yml


```

To run and debug:

```

venv $) ansible-playbook -i hosts site.yml -vvv

```

### Automating Stuff

* Do I really need to automate this?
* Document first
* Automate



### Tasks 




## Add to .bashrc

```
Add this to ~/.bashrc

export PS1="\[\033[1;36m\]me\[\033[01;37m\]@\[\033[01;34m\]me\[\033[01;30m\][\[\033[01;37m\]\w\[\033[01;30m\]]\[\033[01;32m\]\[\033[00m\]+ "

```



# Install tmux tpm 

```
 git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm

```


#Put this in tmux config

```
#

# List of plugins
set -g @plugin 'tmux-plugins/tpm'
set -g @plugin 'tmux-plugins/tmux-sensible'

# Other examples:
# set -g @plugin 'github_username/plugin_name'
# set -g @plugin 'git@github.com/user/plugin'
# set -g @plugin 'git@bitbucket.com/user/plugin'

# Initialize TMUX plugin manager (keep this line at the very bottom of tmux.conf)
run -b '~/.tmux/plugins/tpm/tpm'
```
