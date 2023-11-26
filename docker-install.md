B1: control panel -> programs -> programs and features -> turn windows....-> 
virtual machine platform, windows hypervisor platform,windows system for linux
B2:  wsl -l -o
B3:  wsl.exe --install openSUSE-Tumbleweed
B4:  wsl -d openSUSE-Tumbleweed : chay khi cai nhieu distro
B5: sudo zypper in docker docker-compose podman podman-compose
B6: sudo vim /etc/wsl.conf
```
[boot]
systemd=true
```
B7:sudo systemstl start docker