# tech-stack
A small document describing the tech I use regularly and (sometimes) why

## Terminal

I use [wezterm](https://wezterm.org/index.html). Having tried many terminals, including iTerm2, kitty, Ghostty, etc. I find wezterm, for me, to provide the 
best combination of *fast* and *feature-complete* terminal emulators.

## Text editing

I use [neovim](https://neovim.io/) (btw), specifically, I have a configuration based on [astrovim](https://astronvim.com/).

## Version control

Almost all of what I do is hosted on GitHub, however I have recently adopted [`jj`](https://github.com/jj-vcs/jj) as my version control tool of choice (using the `git` backend). I find `jj` to be both a simpler and more powerful interface for version control.  Likewise, it integrates well with `git` and `GitHub`, so that I can continue to collaborate easily with those using `git` while I am treated to the upgraded VC experience provided by `jj`.

## Command line tools

Obviously, I make use of the regular *nix command line tools.  Here, I provide details on those that I've chosen to replace with some alternative:

* [ripgrep](https://github.com/BurntSushi/ripgrep) : like grep but better & faster.
* [bat](https://github.com/sharkdp/bat) : like cat, but nicer
* [tmux](https://github.com/tmux/tmux/wiki) : if you work on a remote server, you probably already know what `tmux` is, but if you don't I highly recommend using it.

## Software development

I prefer to write my applications in [`rust`](https://www.rust-lang.org/) whenever possible. No programming language is perfect, of course. However, I have so far found `rust` to be tremendously closer to the ideal than any other language I have previously used (which is quite a few). When using `rust` I adopt the `rust` ecosystem, and so use `cargo` as my build tool of choice.  Below, I provide some more details of what I use when developing software both with and without `rust`.

### Build tools

For `rust` I use `cargo`.

For `c++` I use [`meson`](https://mesonbuild.com/) when I can and [`cmake`](https://cmake.org/) when I must.

For `python` I use [`uv`](https://docs.astral.sh/uv/), for both environment managing and distribution.
