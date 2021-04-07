# VSCode

## Extensions

Install the extensions found in `VSCode/extensions` with the command:

```
code --install-extension <extension-id>
```

To update the extensions in this list, use this command:

```
code --list-extensions --show-versions > ~/.dotfiles/VSCode/extensions
```

## Settings

Configure VSCode settings. These files need to be symbolically linked to `~/Library/Application\ Support/Code/User/`.

```
ln -s /Users/<USER>/.dotfiles/VSCode/settings.json /Users/<USER>/Library/Application\ Support/Code/User/settings.json
ln -s /Users/<USER>/.dotfiles/VSCode/keybindings.json /Users/<USER>/Library/Application\ Support/Code/User/keybindings.json
ln -s /Users/<USER>/.dotfiles/VSCode/snippets/* /Users/<USER>/Library/Application\ Support/Code/User/snippets
```

## Font

You can download Fira Code font family here: https://github.com/tonsky/FiraCode/tree/master/distr/ttf

