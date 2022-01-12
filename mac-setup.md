# Mac Setup

## Apps to Install

- [ ] 1Password (sync with phone or old device)
- [ ] Slack
- [ ] Toggl
- [ ] Xcode and TestFlight
- [ ] Sketch / Figma
- [ ] VS Code
   - [ ] Sync settings by logging into Github
   - [ ] [Install `code .` command via shell command](https://stackoverflow.com/questions/29955500/code-not-working-in-command-line-for-visual-studio-code-on-osx-mac)
- [ ] Browsers
   - [ ] Safari (Default)
   - [ ] Chrome / Brave
   - [ ] Edge
   - [ ] Firefox

### Optional Apps

- [ ] Craft
- [ ] Space Gremlin (paid)

## Development

### General

- [ ] [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
   - [ ] [Set your global username and email](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
- [ ] Create zshrc using command
```Bash
touch ~/.zshrc
```

- [ ] [Install NVM](https://github.com/nvm-sh/nvm)
   - [ ] [If you need to install a node version lower than v15](https://github.com/nvm-sh/nvm/issues/2350#issuecomment-734132550)
- [ ] [Generate SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
- [ ] [Connect SSH key to Github](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

### Apps

- [ ] [Install Firebase CLI](https://firebase.google.com/docs/cli#mac-linux-auto-script)
   - [ ] Login with `firebase login`
- [ ] [Install Java](https://www.java.com/en/download/) (Required for Firestore emulators)

### Web

- [ ] Install MAMP Pro
   - [ ] Keys in 1Password or recover via email
   - [ ] Set server ports to 80, 81, etc (use button) in "Ports & Users"
   - [ ] Turn off cache module in "PHP"
   - [ ] Install Sequel Ace in "MySQL"
   - [ ] Enable network access to SQL in "MySQL" in order to use Sequel Ace
- [ ] [Install Composer](https://getcomposer.org/download/) make sure you global install with the `mv` command on that page

   If composer isn't working in an older project your can roll back via `composer self-update --1` . Might get permissions error use `sudo` if so. Can jump back to 2 by using `--2`.

- [ ] [Install Drush globally via Composer](https://docs.drush.org/en/8.x/install-alternative/)

   Add the following to `.zshrc`

```Bash
alias mysql=/Applications/MAMP/Library/bin/mysql
export PATH="/Applications/MAMP/Library/bin:$PATH"
```

- [ ] [Set up PHP path to go to MAMP](https://stackoverflow.com/questions/4145667/how-to-override-the-path-of-php-to-use-the-mamp-path/10653443#10653443)
- [ ] [Install WP-CLI](https://wp-cli.org/#installing)

# Other

Stuff you might want, but don't need for the initial setup.

- [ ] [Install Brew](https://brew.sh/)
   - [ ] [Need to add path for brew](https://apple.stackexchange.com/a/347134) (check the comment if the answer doesn't work.)
- [ ] [Install Github CLI](https://github.com/cli/cli#installation)
   - [ ] Run `gh auth login`
   - [ ] Add to $PATH, I installed via brew so `export PATH="/opt/homebrew/bin/gh:$PATH"`
- [ ] [Install Postman](https://www.postman.com/)

### Extras

- [ ] [Add FiraCode font](https://github.com/tonsky/FiraCode)
   - [ ] [Install for VS code](https://github.com/tonsky/FiraCode/wiki)
- [ ] [OhMyZSH](https://ohmyz.sh/)
- [ ] [Fig](https://fig.io/)
- [ ] [Remote Desktop for testing Windows on site](https://install.appcenter.ms/orgs/rdmacios-k2vy/apps/microsoft-remote-desktop-for-mac/distribution_groups/all-users-of-microsoft-remote-desktop-for-mac)
