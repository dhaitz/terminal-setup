# terminal-setup
-   Mac Terminal: [iterm2](https://iterm2.com/ "https://iterm2.com/") + [catppucin](https://github.com/catppuccin/iterm "https://github.com/catppuccin/iterm") color theme
    -   Also useful for Mac: [Rectangle](https://rectangleapp.com/ "https://rectangleapp.com/") for window management, [Alt-Tab](https://alt-tab-macos.netlify.app/ "https://alt-tab-macos.netlify.app/") for switching windows & [Maccy](https://github.com/p0deje/Maccy) for clipboard history
-   Shell: zsh
    -   zsh configuration: [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh/ "https://github.com/ohmyzsh/ohmyzsh/") + [powerlevel10k](https://github.com/romkatv/powerlevel10k "https://github.com/romkatv/powerlevel10k") prompt + plugins ([zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions "https://github.com/zsh-users/zsh-autosuggestions"), [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting "https://github.com/zsh-users/zsh-syntax-highlighting"), [fzf-zsh-plugin](https://github.com/unixorn/fzf-zsh-plugin "https://github.com/unixorn/fzf-zsh-plugin"))
    -   Newer but less common ones are e.g. nushell, fish, [xonsh](https://github.com/xonsh/xonsh "https://github.com/xonsh/xonsh"). IMHO xonsh looks interesting as it allows both Python and shell commands

 ## Modern shell commands
Modern alternatives to classic tools. Often have nice formatting & colored highlighting, often written in Rust -> fast, some are git compatible (consider .gitignore).

-   File System
    -   [eza](https://github.com/eza-community/eza "https://github.com/eza-community/eza")/[lsd](https://github.com/lsd-rs/lsd "https://github.com/lsd-rs/lsd") (ls)
    -   [dust](https://github.com/bootandy/dust "https://github.com/bootandy/dust") (du)
    -   [broot](https://github.com/Canop/broot "https://github.com/canop/broot")[br] (tree)
    -   [fd](https://github.com/sharkdp/fd "https://github.com/sharkdp/fd") (find)
    -   [ripgrep](https://github.com/BurntSushi/ripgrep "https://github.com/burntsushi/ripgrep")[rg] (grep)
-   Text
    -   [bat](https://github.com/sharkdp/bat "https://github.com/sharkdp/bat") (cat)
    -   [delta](https://github.com/dandavison/delta "https://github.com/dandavison/delta") (diff)
    -   [sd](https://github.com/chmln/sd "https://github.com/chmln/sd") (sed)
-   System
    -   [bottom](https://github.com/ClementTsang/bottom "https://github.com/clementtsang/bottom")[btm], [glances](https://github.com/nicolargo/glances "https://github.com/nicolargo/glances"), [btop](https://github.com/aristocratos/btop "https://github.com/aristocratos/btop") (htop)
    -   [procs](https://github.com/dalance/procs "https://github.com/dalance/procs") (ps)
    -   [duf](https://github.com/muesli/duf "https://github.com/muesli/duf") (df)
-   Other
    -   [fzf](https://github.com/junegunn/fzf "https://github.com/junegunn/fzf") - fuzzy finder, useful to search in piped input, shell history, file contents, ...
    -   [fuck](https://github.com/nvbn/thefuck "https://github.com/nvbn/thefuck") - corrects typo in previous command

See also ~[modern-unix](https://github.com/ibraheemdev/modern-unix)~ [maintained-modern-unix](https://github.com/johnalanwoods/maintained-modern-unix). 
