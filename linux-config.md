# Update & Upgrade
### Ubuntu
```bash
sudo apt update -y && sudo apt upgrade -y && sudo apt autoremove -y && sudo apt clean -y && sudo apt autoclean -y
```

### Fedora
```bash
  sudo dnf update -y && sudo dnf upgrade -y && sudo dnf autoremove -y && sudo dnf clean all && sudo dnf autoremove
```

# Scripting

#!/bin/bash

### Change default terminal emulator

```bash
sudo update-alternatives --config x-terminal-emulator
```

### CHange default shell in the terminal

```bash
chsh -s `which fish`
```

### Partition a disk

With the Disks - Manage Drives and Media utility
