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

### Remove package ubuntu
```powershell
sudo apt-get --purge remove octave3.2
```
