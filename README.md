# my-configs
A smattering of configuration files I use for common programs like bash, vim, etc. The contents of these files are subject to change according to my preferences.

Currently included are:
  - Miscellaneous
      + `issue`: default login screen for `/dev/tty*` devices.
      + `.inputrc`: enables history search with up/down arrows and word skipping with left/right arrows.
  - bash
      + `./.alias`: Contains alias files for various specific scenarios, like different Linux distros.
      + `.bash_aliases`: Contains the most common aliases I use across UNIX-like systems.
      + `.bash_profile`: Commands run whenever one logs in. (Also reads `.bashrc` automatically)
      + `.bash_prompt`: The prompt used (blue and green, but changes to a scary red for the root user)
      + `.bashrc`: Commands run at every interactive session.
 - OpenSSH
      + `config`: Shows randomart for all systems, contains option for disabling IPQoS for WSL (needed due to a known issue: https://github.com/microsoft/WSL/issues/8985).
 - Vim
      + `.vimrc`: Presets for vim (sets tabstops, enables line numbers, syntax highlighting, and colors)
 - WSL
      + `wsl.conf`: Enable systemd and set default login username.
