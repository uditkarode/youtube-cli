# youtube-cli
youtube-cli is a command line based music player with a song cache at ~/.songs which uses ytcli as a helper.
make sure you have youtube-dl and mpv installed, you can find installation guides for your distro on Google.

USAGE:  
1> clone the repository  
  `git clone https://github.com/uditkarode/youtube-cli.git /tmp`  
  
2> move ytcli and ytm to /usr/bin  
  `cp /tmp/youtube-cli/{youtube-cli,ytcli} /usr/bin`  
  
3> make ytcli and ytm executable using chmod  
  `sudo chmod a+x /usr/bin/youtube-cli /usr/bin/ytcli`
  
4> create the directory $HOME/.songs  
  `mkdir -v ~/.songs`
  
5> youtube-cli --play or -p song name  
  `youtube-cli -p pink floyd wish you were here`
