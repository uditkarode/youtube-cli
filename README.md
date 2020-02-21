# youtube-cli
youtube-cli is a command line based music player with a song cache at ~/.songs which uses ytcli as a helper.
make sure you have youtube-dl and mpv installed, you can find installation guides for your distro on Google.

USAGE:  
  ```bash
  git clone https://github.com/uditkarode/youtube-cli.git /tmp/youtube-cli
  cp /tmp/youtube-cli/{youtube-cli,ytcli} /usr/bin
  sudo chmod a+x /usr/bin/youtube-cli /usr/bin/ytcli
  youtube-cli -p pink floyd wish you were here
  ```
    
  To make it a little handier:  
  `mv /usr/bin/youtube-cli /usr/bin/ytm`
    
  If you're on macOS 10.15+
  ```bash
  git clone https://github.com/uditkarode/youtube-cli.git /tmp/youtube-cli
  cp /tmp/youtube-cli/{youtube-cli,ytcli} /usr/localbin
  sudo chmod a+x /usr/local/bin/youtube-cli /usr/localbin/ytcli
  youtube-cli -p pink floyd wish you were here
  ```
