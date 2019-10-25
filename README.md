# starterRepo
Starting notes for setup at Tray

When installing nvm sometimes the PATH needed isnt always included in the .nvm file. 
Make sure to copy/ paste the following into your desired shell configuration file (bash / zsh): 

```
export NVM_DIR="$HOME/.nvm"
. "$(brew --prefix nvm)/nvm.sh"

PATH=$PATH:/usr/local/Cellar
```

Github

In order to avoid signing in and writing out your password every time you want to commit or make a change set up an SSH key.

Follow the instructions in this link once you have navigated to Settings -> SSH keys -> New key in your Github account:
https://help.github.com/en/enterprise/2.16/user/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

 
