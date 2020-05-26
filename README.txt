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

In separate playbook for docker, kubernetes, and snapd (need to have docker repo add from generic playbook first):
docker-ce
docker-cli
containerd.io
snapd (and microk8s snap)

Optional playbook for some GUI tools
postman snap
inkscape
gimp
wireshark

Works for GUI or no GUI builds, extra book included for GUI builds and for running microk8s with docker. 
Run the main book first then the GUI book afterwards for GUI builds.
