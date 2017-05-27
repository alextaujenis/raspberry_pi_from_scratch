# How to build a new Raspberry Pi from scratch
[Click here](README.md) to go to the beginning of this guide.

## Configuration
The newly built Raspberry Pi with the latest version of `Raspbian Jessie (lite)` (Linux Operating System) needs to be configured before setting it up as a server. There are a few things that should happen for you to take control of the Raspberry Pi:

1. Copy SSH keys from your local machine to the Raspberry Pi
1. Disable password-based SSH connections
1. Install Fail2ban to prevent brute-force SSH hacking attempts
1. Remove the default Raspberry Pi user