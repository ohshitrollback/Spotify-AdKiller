# Spotify-AdKiller (for LINUX)

Your Party with Spotify - but without Ads!

We all love Spotify, but sometimes people (like me) want to throw a party without interrupting Ads before having bought premium. This is for testing purposes ONLY! Spotify is a fantastic service and worth every penny. This script is **NOT** meant to circumvent buying premium! Please do consider switching to premium to support Spotify - especially if you're going to use it on the move.

### Installation of the script

Move the script `adkiller.sh` to your PATH containing the Spotify-Binary (e.g. $HOME/bin on openSUSE and Ubuntu) and make it executable with `chmod +x spotify-adkiller.sh`. Then use the wrapper script `spotify-wrapper.sh` to start the AdKiller automatically when Spotify gets started. On openSUSE I simply placed the following line into the Spotify-Launcher on my Desktop: `Exec=/bin/bash /$HOME/bin/spotify-wrapper.sh %U`. You don't have to worry about terminating it when Spotify exits because that happens automatically.
