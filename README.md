# Apt Repository Server
## Summary
Apt repository server to hold custom .deb packages for easy and fast deploy on any linux with apt package manager. (Any DEBIAN based unix including KALI). 
## Connection
- Add elprofesor apt server to /etc/apt/sources.list.d/elprofesor.list
```bash
echo 'deb http://repos.elprofesor.io/elprofesor /' > /etc/apt/sources.list.d/elprofesor.list
```
 - Add apt server key
```bash
wget -qO - https://repos.elprofesor.io/key.gpg | sudo apt-key add -
```
- Update
```bash
apt update
```
- List available packages from apt server
```bash
cat /var/lib/apt/lists/repos.elprofesor.io_elprofesor_Packages
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
