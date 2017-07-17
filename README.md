# brew-bundle
Base brew bundle to build Gain dev machines from.

#### Installing Homebrew
The following will setup homebrew on your machine:
```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Steps
#### Run Brewfile:

```shell
brew bundle --file=Brewfile
```

#### Configure nvm
```shell
mkdir ~/.nvm
```
Add the following to your ~/.bash_profile:
```shell
export NVM_DIR="$HOME/.nvm"
. "/usr/local/opt/nvm/nvm.sh"
```
