# Apt Repository Server
## Summary
deb packages, easy and fast deploy
## Connection
- Add to /etc/apt/sources.list
```bash
deb http://repos.elprofesor.io/elprofesor /
```
 - Add repository key
```bash
wget -qO - https://repos.elprofesor.io/key.gpg | sudo apt-key add -
```
- Update
```bash
apt update
```

## Package List

|  Name | Build|
|--------|---------|
| slack-desktop | &check; |  
| code | &check; |
| obsidian | &check; | 
| dpkg-sig | &check; | 
| spotify-client | &check; | 
| pyfriend | &check; | 
| monbox | &check; |
| monlocal| &cross;|
| www-general | &cross;|
