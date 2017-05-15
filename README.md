### Bash Completion For autopkg

This is a script to provide custom completion for `autopkg` when
running the `bash` shell.

It completes the commands and the long options for each command. For
the options the completion cuts in once you type `--`. It will also
complete on recipe and repo names for commands that require those.

If you have installed bash completion using `brew` then drop the file
into `/usr/local/etc/bash_completion.d/` and open a new Terminal window.

Feedback and bug reports would be greatly appreciated.
