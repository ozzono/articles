# Configure btcnode

## Default installs

> sudo apt install -y gpg git hdparm ufw fail2ban nginx tor cargo clang cmake nodejs inotify-tools vim wget curl screen swapspace

## Configure iptables alternative

```shell
sudo update-alternatives --list iptables
sudo update-alternatives --set iptable /user/sbin/iptables-legacy
```

## login in as bitcoin as user

If the error `could not open session` appear when running `sudo su - bitcoin`
