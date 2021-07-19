# dotfiles - Home directory configuration files for macOS

These are the configuration files I use for macOS systems. They may work on
Linux as well, but there is enough BSD in macOS that things are slightly
different.

## History
From about 2012 to 2021 I used [Dropbox](https://www.dropbox.com) to sync these
files. I find myself using Dropbox less and less, and I'm taking the
opportunity of setting up a new laptop to migrate to GitHub for these files.

macOS Big Sur (11.4) deprecated `bash`, and recommends `zsh`. After some
research and asking around, I'm trying `fish` instead. I like it, but there is
a learning curve, and some tools I use assume a POSIX shell.

My new laptop is the 2020 MacBook Pro (13-inch, M1), so I am also converting
from `amd64` / Intel to `arm64` / Apple Silicon.

I still have my older laptop, so I may import my `bash` files as well, and try
to switch between `amd64` and `arm64`.

Thanks to [jgmize](https://github.com/jgmize/dotfiles) and
[jsatt](https://github.com/jsatt/dotfiles) for suggesting this method of
keeping track of these files.
