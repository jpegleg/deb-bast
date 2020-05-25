# deb-bast
Ansible playbook to install common workstation tools.
Depending on the Debain install method used by you before running the playbook, many of these tools may 
already be installed. Tested/for Debian 10.X.

No GUI required
vim
ssh
gpg
gcc
tar
rsync
tcpdump
python3
netcat
curl
openssl
ufw (firewall enable and rule adds included in playbook)
fail2ban
ansible
git
tmux
docker-ce
docker-cli
containerd.io
snapd (and microk8s snap)

optional playbook for some GUI tools
postman snap
inkscape
gimp
wireshark

Works for GUI or no GUI builds, extra book included for GUI builds. 
Run the main book first then the GUI book afterwards for GUI builds.
