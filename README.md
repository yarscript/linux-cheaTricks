# linux-cheaTricks by yarscript
It could be useful

<hr>

### SSH connection
```powershell
ssh user@225.225.225.1 -i ~/.ssh/some_key.pem
```

### Change PHP/Python(?) Version Linux
```powershell
sudo update-alternatives --set php /usr/bin/php8.0
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.9 2
```

### Create Symlink 
```powershell
ln -s /opt/foo /usr/bin/bar
```

### Install Xdebug
```powershell
sudo apt install php-xdebug
sudo phpenmod -v 7.3 xdebug
```

### Redis cli login & changepass
```powershell
redis-cli -a redispass
config set requirepass ""
```

<hr>

### Remove package ubuntu
```powershell
sudo apt-get --purge remove octave3.2
```

### Installed packages list
```powershell
dpkg -l OR apt list
dpkg -l | grep apt # SEARCH "apt"
```

### Install package with version ubuntu
```powershell
sudo apt install apt-transport-https=1.4.10
```

### Download / Upload file terminal | ssh
```powershell
scp root@servername.com:/tmp/1.sql ~/Downloads/1.sql  # Download
scp ~/1.sql root@servername.com:/tmp                  # Upload
```

### Processes
```powershell
pstree                                                # Tree
htpp                                                  # Informative
```

### Draw tree in terminal
```powershell
tree -L 4 dir_name
```
