# DaviXx59.github.io
hiii
# Created with YamlCreate.ps1 v2.2.9 $debug=AUSU.CRLF.5-1-19041-3031.Win32NT
Run sudo apt install quilt qemu-user-static debootstrap libarchive-tools arch-test
  sudo apt install quilt qemu-user-static debootstrap libarchive-tools arch-test
  shell: /usr/bin/bash -e {0}

WARNING: apt does not have a stable CLI interface. Use with caution in scripts.

Reading package lists...
Building dependency tree...
Reading state information...
The following additional packages will be installed:
  diffstat gettext
Suggested packages:
  squid-deb-proxy-client debian-archive-keyring autopoint gettext-doc
  libasprintf-dev libgettextpo-dev default-mta | mail-transport-agent graphviz
  procmail
The following NEW packages will be installed:
  arch-test debootstrap diffstat gettext libarchive-tools qemu-user-static
  quilt
0 upgraded, 7 newly installed, 0 to remove and 35 not upgraded.
Need to get 18.[2](https://github.com/trilobio/rpi-image/actions/runs/14866753447/job/41745351000#step:3:2) MB of archives.
After this operation, 173 MB of additional disk space will be used.
Get:1 http://ports.ubuntu.com/ubuntu-ports noble/universe arm64 arch-test all 0.21-1 [12.7 kB]
Get:2 http://ports.ubuntu.com/ubuntu-ports noble/main arm64 diffstat arm64 1.66-1build1 [28.1 kB]
Get:[3](https://github.com/trilobio/rpi-image/actions/runs/14866753447/job/41745351000#step:3:3) http://ports.ubuntu.com/ubuntu-ports noble/main arm6[4](https://github.com/trilobio/rpi-image/actions/runs/14866753447/job/41745351000#step:3:5) gettext arm64 0.21-14ubuntu2 [84[5](https://github.com/trilobio/rpi-image/actions/runs/14866753447/job/41745351000#step:3:6) kB]
Ign:4 http://ports.ubuntu.com/ubuntu-ports noble-updates/universe arm64 libarchive-tools arm[6](https://github.com/trilobio/rpi-image/actions/runs/14866753447/job/41745351000#step:3:7)4 3.[7](https://github.com/trilobio/rpi-image/actions/runs/14866753447/job/41745351000#step:3:8).2-2ubuntu0.3
Get:5 http://ports.ubuntu.com/ubuntu-ports noble-updates/universe arm64 qemu-user-static arm64 1:[8](https://github.com/trilobio/rpi-image/actions/runs/14866753447/job/41745351000#step:3:9).2.2+ds-0ubuntu1.6 [16.8 MB]
Get:6 http://ports.ubuntu.com/ubuntu-ports noble/universe arm64 quilt all 0.67+really0.67-4 [436 kB]
Get:7 http://ports.ubuntu.com/ubuntu-ports noble/main arm64 debootstrap all 1.0.134ubuntu1 [48.0 kB]
Err:4 http://ports.ubuntu.com/ubuntu-ports noble-updates/universe arm64 libarchive-tools arm64 3.7.2-2ubuntu0.3
  404  Not Found [IP: [9](https://github.com/trilobio/rpi-image/actions/runs/14866753447/job/41745351000#step:3:10)1.189.91.104 80]
Fetched 18.2 MB in 1s (25.4 MB/s)
E: Failed to fetch http://ports.ubuntu.com/ubuntu-ports/pool/universe/liba/libarchive/libarchive-tools_3.7.2-2ubuntu0.3_arm64.deb  404  Not Found [IP: 91.189.91.[10](https://github.com/trilobio/rpi-image/actions/runs/14866753447/job/41745351000#step:3:11)4 80]
E: Unable to fetch some archives, maybe run apt-get update or try with --fix-missing?
Error: Process completed with exit code 100.
