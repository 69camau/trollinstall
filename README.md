# trollinstall
Install IPAs with TrollStore via SSH

# Dependencies
The Mac needs SSHPass installed and the iDevice needs to have OpenSSH installed
Both devices need to be on the same WiFi network for SSH to work

# Usage
trollinstall Desktop/App.ipa 192.168.1.000 root alpine 2222 (port is optional, default port is 2222)

# Why is this useful?
Its useful for developers to quickly test their apps without the need to rename the ipa to .tipa then AirDrop and install it. This can also be incorporated into the developers build command for Makefile so it automatically installs their app
