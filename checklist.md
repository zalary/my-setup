## Configure OS preferences, shortcuts, etc
- [x] Update to the latest OSX patch
- [x] Set new system password
- [x] Turn on hard drive encryption
- [x] Trackpad
	- [x] Turn on 1 click touch
	- [x] Enable three finger touch to drag (System Prefs > Accessibility > Trackpad > Shortcuts)
- [x] Spotlight: change to `alt A` for Spotlight search
- [x] Global: `cmd shift +` for Window > Zoom
- [x] Dock
	- [x] Move to left side
	- [x] Check automatically show and hide
- [x] Finder
	- [x] Setup sidebar
	- [x] Setup [default arrangement view](https://howchoo.com/g/mzuxyjqyzmy/how-to-set-the-view-options-for-all-finder-windows-in-os-x)
		- Arrange by: Name
		- Sort by: Name
		- Check Show item Info
		- Click `Use as Defaults`
	- [x] Turn on [view hidden files](https://gist.github.com/jglovier/f87661ad2d10fa747ad6fcbbf7224305)
- [x] Energy Saver: Turn off slightly dim display on battery power
- [x] Security
	- [x] Turn on FileVault disk encryption
	- [x] Set to require password immediately
	- [x] Turn on Firewall (?)

## Applications
- [x] General
	- [x] Go to App Store > Purchased and download all necessary
		- [x] ByWord
		- [x] Xcode
			- [x] Also install [Command Line Tools](https://developer.apple.com/downloads/)
		- ~~Sketch~~ (not from App store anymore, download from site)
		- [x] Slack
		- [x] 1Password
		- [x] TextExpander
		- [x] DaisyDisk
		- [x] etc
- [x] [Dropbox](https://www.dropbox.com/install)
- [x] [Chrome](http://www.google.com/chrome/)
	- [x] Set to confirm on `Cmd Q` for Quit
	- [x] Log in and sync bookmarks and extensions
	- [ ] Install [user style for GitHub.com](https://gist.github.com/jglovier/2dff3507d9ee007f6ce4)
- [x] [Atom](http://atom.io)
- [x] [GitHub Desktop](https://desktop.github.com/)
- [x] [Sketch](http://www.sketchapp.com/)
- [x] [Fantastical 2](https://flexibits.com/fantastical)
	- [x] Check Appearance > Use color icon
- [x] [Adobe Creative Cloud](http://www.adobe.com/creativecloud.html)
	- [x] Photoshop
	- [x] Illustrator
	- [x] Acrobat
- [x] [Bartender 2](https://www.macbartender.com/)
- [x] Apple Mail (or [Nylas](https://nylas.com/))
	- [x] Configure email accounts
- [x] [Cloak](https://www.getcloak.com/)

## CLI
- [x] Xcode > install command line tools
- [x] Install [iTerm2](https://www.iterm2.com/)
	- [x] Install [Galaxy theme](https://github.com/jglovier/galaxy-theme-iterm)
	- [x] Load `.bash_profile`
	- [x] Load `.gitconfig` contents into global `~/.gitconfig`
	- [ ] Load `.zshrc`
- [ ] zsh
- [ ] Install Ruby
	- [x] Install rbenv via Homebrew: `brew install rbenv`.
	- [x] Download a version of Ruby via rbenv (e.g., `rbenv install 2.2.3`). See <https://gorails.com/setup/osx/10.11-el-capitan>.
	- [ ] Make it the global version of Ruby: `rbenv global 2.2.3`.
- [ ] Install misc dependencies
	- [x] Install Node via Homebrew: `brew install node`
	- [ ] Install Sass, Jekyll, and Rouge: `gem install sass jekyll rouge`.

## Atom
- [ ] Enable `atom` Terminal commands: from Atom.app, open the Atom menu and select *Install Shell Commands*
- [x] Disable the `wrap-guide` package
- [ ] Install [favorite packages](https://atom.io/users/jglovier/stars):
	- [x] [Fizzy syntax theme](https://atom.io/themes/fizzy) syntax package
	- [ ] [Wrap in tag](https://atom.io/packages/atom-wrap-in-tag)
	- [ ] [Selector to tag](https://atom.io/packages/selector-to-tag)
	- [ ] [Linter](https://atom.io/packages/linter) and [`.scss` linter](https://atom.io/packages/linter-scss-lint)

## GitHub
- [x] [Generate new SSH key](https://help.github.com/articles/generating-an-ssh-key/)
- [x] [Generate an access token](https://help.github.com/articles/creating-an-access-token-for-command-line-use/) for Terminal to auth your GitHub account when 2FA is enabled.
- [x] Download the [Strap](https://github.com/mikemcquaid/strap) setup script for GitHub's foundational development setup.
- [ ] Clone the `github/github` repository and run `script/osx-setup`.

## Code
- [x] Setup ~/github
- [x] Setup ~/code/github-*

## Backup
- [x] Configure TimeMachine and perform initial backup
  - [x] Turn off, and set Cal reminder to perform manually each week
