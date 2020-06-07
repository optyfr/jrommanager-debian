# jrommanager-debian
Debian repository for JRomManager

0. First, you must be root (with `su` command) or run `sudo bash`
1. add public key: `wget -qO - https://raw.github.com/optyfr/jrommanager-debian/master/public.key | sudo apt-key add -`
2. add to apt sources:
    * for Jessie: `echo "deb https://raw.githubusercontent.com/optyfr/jrommanager-debian/master/debian jessie contrib" >/etc/apt/sources.list.d/jrommanager.list`
    * for Stretch: `echo "deb https://raw.githubusercontent.com/optyfr/jrommanager-debian/master/debian stretch contrib" >/etc/apt/sources.list.d/jrommanager.list`
    * for Buster: `echo "deb https://raw.githubusercontent.com/optyfr/jrommanager-debian/master/debian buster contrib" >/etc/apt/sources.list.d/jrommanager.list`
3. update lists: `apt update`
4. install: `apt install jrommanager`
