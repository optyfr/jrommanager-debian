# jrommanager-debian
Debian repository for JRomManager

1. add public key `wget -qO - https://raw.github.com/optyfr/jrommanager-debian/master/public.key | sudo apt-key add -`
2. add to apt sources:
  * for jessie: `echo "deb https://raw.githubusercontent.com/optyfr/jrommanager-debian/master/debian jessie contrib" >/etc/apt/sources.list.d/jrommanager.list`
  * for stretch: `echo "deb https://raw.githubusercontent.com/optyfr/jrommanager-debian/master/debian stretch contrib" >/etc/apt/sources.list.d/jrommanager.list`
  * for buster: `echo "deb https://raw.githubusercontent.com/optyfr/jrommanager-debian/master/debian buster contrib" >/etc/apt/sources.list.d/jrommanager.list`
3. `apt update`
4. `apt install jrommanager`
