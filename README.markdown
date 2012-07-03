# Sublime Text 2 plugin: Goto DrupalContrib API

A command to jump to documentation for the current word.

## Supports

 * Drupal 7 API

Submit a patch adding more and I'll include it.

## Using

Open the command palette (cmd-shift-p) and choose "Goto Documentation" while your cursor is on a word.

Make a keybind by adding the following to your `User/Default (OSX).sublime-keymap`:

	{ "keys": ["super+shift+a"], "command": "goto_drupalapi" }

## Installing

First, you need to have `git` installed and in your `$PATH`. Afterwards you may need to restart Sublime Text 2 before the plugin will work.

### OSX

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/
    $ git clone git://github.com/revagomes/Sublime-Text-2-Goto-DrupalContrib-API.git GotoDocumentation

### Linux (Ubuntu like distros)

    $ cd ~/.config/sublime-text-2/Packages/
    $ git clone git://github.com/revagomes/Sublime-Text-2-Goto-DrupalContrib-API.git GotoDocumentation

### Windows 7:

    Copy the directory to: "C:\Users\<username>\AppData\Roaming\Sublime Text 2\Packages"

### Windows XP:

    Copy the directory to: "C:\Documents and Settings\<username>\Application Data\Sublime Text 2\Packages"
