# Useful Commands

### Git & GitHub

#### Branches

- `git branch -d localBranchName` Delete the local branch
- `git push origin --delete remoteBranchName`: Delete the remote branch
- `git fetch --all --prune`: Removes all references to remote branches

### NPM

- `rm -rf node_modules package-lock.json && npm cache clean --force && npm install` Delete node_modules folder, clear cache and install packages

### Open VPN

- `sudo openvpn --config configFile.ovpn` Connect to OpenVPN with the config file
