# havoc
sudo gpg --no-default-keyring --keyring /usr/share/keyrings/deadsnakes-archive-keyring.gpg --keyserver keyserver.ubuntu.com --recv-keys 6A755776
echo "deb [signed-by=/usr/share/keyrings/deadsnakes-archive-keyring.gpg] http://ppa.launchpad.net/deadsnakes/ppa/ubuntu focal main" | sudo tee /etc/apt/sources.list.d/deadsnakes.list
sudo apt update
sudo apt install python3.10
