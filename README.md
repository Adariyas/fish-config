## Cachyos Fish Config

- ohmyfish
- fish
- fastfetch

## Common use
grubup="sudo grub-mkconfig -o /boot/grub/grub.cfg"
fixpacman="sudo rm /var/lib/pacman/db.lck"
tarnow='tar -acf '
untar='tar -zxvf '
wget='wget -c '
psmem='ps auxf | sort -nr -k 4'
psmem10='ps auxf | sort -nr -k 4 | head -10'
alias ..='cd ..'
alias ...='cd ../..'
alias ....='cd ../../..'
alias .....='cd ../../../..'
alias ......='cd ../../../../..'
dir='dir --color=auto'
vdir='vdir --color=auto'
grep='grep --color=auto'
fgrep='fgrep --color=auto'
egrep='egrep --color=auto'
hw='hwinfo --short'                                   # Hardware Info
big="expac -H M '%m\t%n' | sort -h | nl"              # Sort installed packages according to size in MB
gitpkg='pacman -Q | grep -i "\-git" | wc -l'          # List amount of -git packages
update='sudo pacman -Syu'
