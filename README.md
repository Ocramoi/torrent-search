# torrent-search

Bash only script for searching torrents on 1337x, based on [Sayan G's](https://github.com/sayan01) [youtube search script](https://github.com/sayan01/scripts/blob/master/yt).

# Requirements
- [fzf](https://github.com/junegunn/fzf)
- sed, awk, grep, bash

# Installation
To install the script simply clone the git repository and add it to your PATH (or move `torrent-search` to your user's bin folder) as such:

`$ git clone https://github.com/Ocramoi/torrent-search $HOME/torrent-search`

Then:

`$ export PATH=$PATH:$HOME/torrent-search`

Or, if you have a `bin` folder (assuming `$HOME/bin`):

`$ git clone https://github.com/Ocramoi/torrent-search $HOME/torrent-search`

`$ ln -s $HOME/torrent-search/torrent-search $HOME/bin`

# Usage
To use the tool once it's on your PATH simply type `torrent-search <search query>` or just `torrent-search` and you'll then receive the search prompt. Example:

`$ torrent-search Night of the Living Dead`

or

`$ torrent-search` \<RET\>

`Search: Night of the Living Dead` \<RET\>

# TODO
- [x] Show file size
- [x] Show amount of seeders
