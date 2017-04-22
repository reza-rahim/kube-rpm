# kube-rpm

* the option policy can show the installed and the remote version (install candidate) of a package

apt-cache policy <package>

* download the deb package. the deb goes goes to /var/cache/apt/archives

sudo apt-get --download-only install packagename
