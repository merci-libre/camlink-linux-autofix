# camlink-linux-autofix
Shell Script that automates the process of fixing non-physical Camlink issues on most Linux Systems.

## Dependencies
`ffmpeg, v4l2loopback-utils, v4l2loopback-dkms (optional)`
## About
Essentially creates a loopback device through v4l2 and duplicates input from your camlink to it. This was inspired by other people's fixes for the camlink, I only wanted to automate it because it was a hassle to input many commands to do just one thing.  
##Running the script
1. `git clone https://github.com/merci-libre/camlink-linux-autofix/ `
2. `cd camlink-linux-autofix && chmod +x camlink`
3. `./camlink`
