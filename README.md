# Inspiration
- https://github.com/mathiasbynens/dotfiles
- https://github.com/driesvints/dotfiles
- https://driesvints.com/blog/getting-started-with-dotfiles/

## Fresh install flow for macOS

Prepare the machine with initial bits

1. Update macOS to the latest version with the App Store
2. Install Xcode from the App Store, open it and accept the license agreement
3. Install macOS Command Line Tools by running `xcode-select --install`
4. Install homebrew (https://brew.sh/)

Transfer SSH keys
1. Copy your public and private SSH keys to `~/.ssh` and make sure they're set to `600`

Pull down the dotfiles repo
`cd; curl -#L https://github.com/mathiasbynens/dotfiles/tarball/master | tar -xzv --strip-components 1 --exclude={README.md,bootstrap.sh}`
This command can be run again at any time to update files


1. Open terminal `
5. Clone this repo to `~/.dotfiles`

6. 

8. Restart the computer


### Maintaining Dotfiles
- When installing a new app, tool or font, try to install it with Homebrew and add it to your Brewfile
- When configuring a new app make sure to run mackup backup to save your preferences
- When changing an macOS setting, try setting it through the .macos file

Following these tips will help keep files up to date and enable your Mac to be restored the way more easily.