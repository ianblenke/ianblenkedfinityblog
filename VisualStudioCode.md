# Visual Studio Code

This markdown text file describes the Visual Studio Code experience with motoko.

If you are on a Mac and are using [Homebrew](https://brew.sh), start by installing Visual Studio Code:

    brew cask install visual-studio-code

Then you can fire up Visual Studio Code simply by running:

    code

If you're an old school VI greybeard like myself, you may want to install the VIM plugin:

https://github.com/VSCodeVim/Vim

# Install the VsCodeVim plugin:

- Open Visual Studio Code
- Go to Extensions (Look in the menu under Code -> Preferences)
- Type vim in the search box
- The first plugin named Vim is the one you want
- Click on the install button

# Enable key-repeating:

Run the following command:

    defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
    defaults delete -g ApplePressAndHoldEnabled
