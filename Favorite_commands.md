## Update packages
```
sudo pacman -Syu  
yay -Syu
```

## Packages cleanup
```
sudo pacman -Sc  
yay -Sc  
yay -Yc
```

## Check cache files & logs
`sudo du -sh ~/.cache /var/cache /var/log/journal`

## Logs cleanup
`sudo journalctl --vacuum-size=82M`

## Remove orphan packages
```
sudo pacman -Qtdq  
sudo pacman -R $(pacman -Qtdq)
```

## Remove cache files older than 28 days
`sudo find ~/.cache -type f -atime +30 -delete`

## List available block devices
`lsblk -f`

## Mount an external drive 
`sudo mount /dev/sda1 /mnt`  
Replace sda1 and /mnt with actual source and destination targets.  
You might have to create a destination folder if /mnt is already in use. 

## Time a command
`time <my_command>`

## Delete a specific entry from fish shell history
`history delete <entry>`

