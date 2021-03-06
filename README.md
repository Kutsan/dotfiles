# `kutsan's dotfiles` [![luacheck](https://github.com/kutsan/dotfiles/actions/workflows/luacheck.yml/badge.svg)](https://github.com/kutsan/dotfiles/actions/workflows/luacheck.yml)

![screenshot](https://raw.githubusercontent.com/kutsan/dotfiles/master/.github/screenshot.png)

> running **neovim** inside **kitty** terminal emulator with **fira** font on

## Overview

- [`zsh`](https://github.com/zsh-users/zsh) - Highly customizable interactive login shell and command interpreter for shell scripting
  - [`pure`](https://github.com/kutsan/pure) - Minimal and fast Zsh prompt with asynchronous git fetch
  - [`autopair`](https://github.com/hlissner/zsh-autopair) - Auto-close and delete matching delimiters
  - [`system-clipboard`](https://github.com/kutsan/zsh-system-clipboard) - Synchronize ZLE clipboard buffer with system clipboard
  - [`fast-syntax-highlighting`](https://github.com/zdharma/fast-syntax-highlighting) - Fish-like syntax highlighting support for interactive terminal
  - [`autosuggestions`](https://github.com/zsh-users/zsh-autosuggestions) - Fish-like auto-suggestions for interactive terminal based on command history
- [`neovim`](https://github.com/neovim/neovim) - The fork of ubiquitous text editor focused on extensibility and usability
  - [`material`](https://github.com/kaicataldo/material.vim) - Color scheme
  - [`colorizer`](https://github.com/norcalli/nvim-colorizer.lua) - High-performance color highlighter
  - [`compe`](https://github.com/hrsh7th/nvim-compe/) - Auto completion support
  - [`editorconfig`](https://github.com/editorconfig/editorconfig-vim) - EditorConfig support
  - [`formatter`](https://github.com/mhartington/formatter.nvim) - Format runner
  - [`fugitive`](https://github.com/tpope/vim-fugitive) - Git client
  - [`fzf`](https://github.com/junegunn/fzf.vim) - Fuzzy finder fzf as plugin
  - [`indentline`](https://github.com/Yggdroot/indentLine) - Display the indention levels with thin vertical lines
  - [`lspconfig`](https://github.com/neovim/nvim-lspconfig) - Quickstart configurations for the neovim LSP client
    - [`diagnostic-language-server`](https://github.com/iamcco/diagnostic-languageserver) - General purpose language server that integrate with linters
    - [`typescript-language-server`](https://github.com/theia-ide/typescript-language-server) - TypeScript & JavaScript Language Server
    - [`css-language-server`](https://github.com/vscode-langservers/vscode-css-languageserver-bin) - CSS Language Server
    - [`html-language-server`](https://github.com/vscode-langservers/vscode-html-languageserver-bin) - HTML Language Server
    - [`json-language-server`](https://github.com/vscode-langservers/vscode-json-languageserver) - JSON Language Server
    - [`lua-language-server`](https://github.com/sumneko/lua-language-server) - Lua Language Server
  - [`nvim-tree`](https://github.com/kyazdani42/nvim-tree.lua) - File explorer
  - [`nvim-web-devicons`](https://github.com/kyazdani42/nvim-web-devicons) - Nerd Font icon API support
  - [`pears`](https://github.com/steelsojka/pears.nvim) - Auto pair plugin
  - [`polyglot`](https://github.com/sheerun/vim-polyglot) - Big collection of language packs as scripts are loaded only on demand
  - [`sandwich`](https://github.com/machakann/vim-sandwich) - The set of operator and text object plugins to search, select, edit sandwiched text objects
  - [`signify`](https://github.com/mhinz/vim-signify) - Show Git diff in the sign column
  - [`undotree`](https://github.com/mbbill/undotree) - Visualize undo tree
- [`git`](https://git-scm.com) - Version control system for tracking changes in files and coordinating the work
- [`nodejs`](https://nodejs.org) - JavaScript runtime environment for developing a diverse variety of applications
  - [`npm`](https://www.npmjs.com) - Node Package Manager mainly for the JavaScript programming language
    - [`fx`](https://github.com/antonmedv/fx) - TUI JSON viewer
    - [`bitwarden`](https://github.com/bitwarden/cli) - Password manager
    - [`eslint_d`](https://github.com/mantoni/eslint_d.js) - Run ESLint as a daemon
- [`python`](https://www.python.org) - High-level programming language for general-purpose programming
  - [`pip`](https://pypi.org) - Python package manager to install and manage packages written in Python
    - [`stig`](https://github.com/rndusr/stig) - TUI and CLI interface for transmission-daemon
    - [`grip`](https://github.com/joeyespo/grip) - Preview Markdown files in local server
    - [`trash-cli`](https://github.com/andreafrancia/trash-cli) - Move files and folders to the trash
- [`lua@5.1`](https://www.lua.org) - Lightweight, embeddable scripting language
  - [`luarocks`](https://luarocks.org) - Package manager for Lua modules
    - [`luacheck`](https://github.com/mpeterv/luacheck) - Linting and static analysis of Lua code
- [`rust`](https://www.rust-lang.org) - Multi-paradigm programming language designed for performance and safety
  - [`cargo`](https://crates.io) - Package manager for Rust crates
    - [`stylua`](https://github.com/johnnymorganz/stylua) - Lua formatter
- [`coreutils`](https://www.gnu.org/software/coreutils/coreutils.html) - GNU core utilities for basic file, shell and text manipulation
- [`findutils`](https://www.gnu.org/software/findutils) - GNU basic directory searching utilities that provides find, locate and xargs
- [`less`](http://www.greenwoodsoftware.com/less) - Standard file pager for Unix-like systems
- [`curl`](https://github.com/curl/curl) - Tool for transferring data using various protocols
- [`grep`](https://www.gnu.org/software/grep) - Search plain-text data sets for lines that match a regular expression
- [`tar`](https://www.gnu.org/software/tar) - File archiver
- [`gzip`](https://www.gnu.org/software/gzip) - Data compression utility
- [`sed`](https://www.gnu.org/software/sed) - Non-interactive command-line text editor
- [`gnupg`](https://www.gnupg.org) - Hybrid-encryption software suit, free implementation of the OpenPGP standard
- [`nmap`](https://github.com/nmap/nmap) - Network security scanner and mapper for exploration and security auditing
- [`openssl`](https://github.com/openssl/openssl) - Toolkit for the Transport Layer Security (TLS) and Secure Sockets Layer (SSL) protocols
- [`openssh`](https://www.openssh.com) - Connectivity tool for remote login with the SSH protocol
- [`rsync`](https://rsync.samba.org) - Utility that provides fast incremental file transfer
- [`fzf`](https://github.com/junegunn/fzf) - General-purpose fuzzy finder that can be used among other Unix tools
- [`htop`](https://github.com/hishamhm/htop) - Interactive text-based system monitor, process viewer and process manager
- [`ffmpeg`](https://github.com/FFmpeg/FFmpeg) - Cross-platform solution to handle, record, convert and stream audio and video
- [`lf`](https://github.com/gokcehan/lf) - Terminal file manager with vim-like key bindings
  - [`exiftool`](http://www.sno.phy.queensu.ca/~phil/exiftool) - Read, write and edit meta information in a wide variety of media files
- [`transmission`](https://github.com/transmission/transmission) - BitTorrent client and daemon with web UI for remote controlling
- [`bind`](https://source.isc.org/cgi-bin/gitweb.cgi) - Domain Name System tools
- [`gcal`](https://www.gnu.org/software/gcal) - Calculate and print calendars
- [`mpv`](https://github.com/mpv-player/mpv) - Minimalist video player based on MPlayer
- [`wireguard`](https://github.com/WireGuard/wireguard-go) - Virtual Private Network protocol to create secure point-to-point connections
- [`ledger`](https://github.com/ledger/ledger) - Double-entry accounting system with a command-line reporting interface
- [`oath-toolkit`](https://www.nongnu.org/oath-toolkit) - Provides components for building one-time password authentication systems
- [`gptfdisk`](https://www.rodsbooks.com/gdisk) - Interactive GUID partition table (GPT) manipulator

## License

GPL-3.0
