---
title: 'VIM Keybindings in the Command Line With .inputrc Configuration'
description: 'How to get VIM keybindings in any terminal application (supporting GNU Readline)'
pubDate: 'Jan 15 2026'
---

I've been using VIM (or VIM mode in other editors) since undergrad. I would often have to context switch between the command line (usually defaulting to EMACS style keybindings) and my editors.

However, someone showed me that you can enable VIM keybindings in a [.inputrc config file](https://www.baeldung.com/linux/inputrc-file).

This `.inputrc` config file is read by the `readline` program. By enabling `vi` `editing-mode` and `vi-command` `keymap` - your terminal will behave like a VIM editor.

Moreover - readline based command line utilities (`psql`, `python`, etc.) also now use a VIM interface.

You get dropped into `insert` mode - so it feels pretty typical. But you can escape to `normal` mode - navigate back through your history like you're navigating through a file in VIM (via the `k` key). If you pick an old line - you can edit the line as you would any other line in VIM. If you're used to working in VIM - it feels very ergonomic to always use those keybindings.

Here is what that looks like in my `.inputrc` config file.
```
set editing-mode vi
set keymap vi-command
```

It is a simple enough change that I'll manually make it on most hosts I work on.

[Here](https://deut-erium.github.io/2024/01/28/inputrc.html) is a more in-depth post discussing more configuration options - though I have always found the simple one good for my use.