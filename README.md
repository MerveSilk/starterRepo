# starterRepo
Starting notes for setup at Tray

When installing nvm sometimes the PATH needed isnt always included in the .nvm file. 
Make sure to copy/ paste the following into your desired shell configuration file (bash / zsh): 

```
export NVM_DIR="$HOME/.nvm"
. "$(brew --prefix nvm)/nvm.sh"

PATH=$PATH:/usr/local/Cellar
``` 
