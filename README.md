# shell-it package

A simple Atom package to replace text in the editor by passing it through a shell command.  It is in the vein of `%!` in VIM.

![untitled screencast 15](https://cloud.githubusercontent.com/assets/811455/12214409/ddafdf94-b647-11e5-8a28-02c88d5a1446.gif)

### Usage

- select text
- execute `shell-it:open` (default keybinding is `shift-ctrl-alt-S`)
- type in a shell cmd (such as `sort`).
- hit enter
- The command will be executed in an OS shell

### Stdin and Stdout

- The left checkboxes specify stdin from the selected text and/or the clipboard.  If both are checked the clipboard and selection are concatenated for the input.

- The right checkboxes specify where stdout is sent.  If both are checked then the output goes to both the clipboard and the selection.

- The working directory is set to the project containing the current editor

### License
Copyright Mark-Hahn with the MIT license.
