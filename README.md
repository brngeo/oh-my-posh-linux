
# oh-my-posh-linux

Oh My Posh is a cross-platform prompt theme engine for shells like Bash, Zsh, PowerShell, and Fish, supported on Linux via amd64, arm, and arm64 architectures.

## Installation

**Download and install**

```bash
sudo wget https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/posh-linux-amd64 -O /usr/local/bin/oh-my-posh
```

**Fonts**
```bash
oh-my-posh font install meslo
```
**Terminal Settings** \
Preferences > Appearance > Custom Font > meslo

**Refresh font cache** \
to refresh the font cache because sometimes it doesn't work when \
trying to install a font directly.
```bash
sudo fc-cache -f -v
```

**Make and Copy** \
make a new folder "oh-my-posh-linux-themes" 
```bash
cd /
cd /home/user/
mkdrir "oh-my-posh-linux-themes"
```
copy the brayan.omp.json file 
```bash
cp brayan.omp.json /home/user/oh-my-posh-linux-theme/
```

***.bashrc*** \
locate the .bashrc in your home directory and open and edit it, \
insert this in the last line.
```bash
eval "$(oh-my-posh init bash --config ~/oh-my-posh-linux-terminal/brayan.omp.json)"
```
Close all terminal and restart the terminal.


Good Job! \
your terminal is now good looking.

## Author
- [@brayan](https://facebook.com/brn.geo04)
