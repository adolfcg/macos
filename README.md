# macOS Initial Setup

## Install Command Line Tools for Xcode ##

Usually you can install the Command Line Tools for Xcode with the command: 

```sh
xcode-select --install
```

> Or download and install it from the original source [ [here](https://developer.apple.com/download/more/?=command%20line%20tools) ]

After installation you can check or install a new version available with the commands below.

```sh
softwareupdate --list
softwareupdate --all --install --force
```

## Install Homebrew ##

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"  
```

The below line will help you to turn off any analytics comming from Google.

```sh
brew analytics off
```

Finally you can check the health of your current installation with:

```sh
brew doctor
```
