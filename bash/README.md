# Bash

## Updating Terminal Profile

Whenever the Terminal profile changes, update the `.terminal` file located in this repo.

Open Terminal > Preferences, select the profile, click the "...", and select "Export...". Move the file to this repo.

## Setting Terminal Profile

You can simply import a `.terminal` profile in Terminal > Preferences.

Alternatively, or perhaps automatically, you can set the default profile running the following in a new terminal window.

```
open ~/.dotfiles/bash/steven.terminal
```

And then in that new window, paste the following two commands in.

```
defaults write com.apple.terminal "Default Window Settings" "steven"
defaults write com.apple.terminal "Startup Window Settings" "steven"
```
