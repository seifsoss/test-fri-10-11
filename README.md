#!/bin/bash
echo " Hi, Happy Debuging :) ..."
sleep 1
sudo yum groupinstall -y "Development Tools"
sudo yum install -y ncurses-devel
sudo yum install -y qt3-devel
sudo yum install -y vim
sudo yum install -y kernel-devel
sudo yum install -y hmaccalc
sudo yum install -y zlib-devel
sudo yum install -y binutils-devel
sudo yum install -y elfutils-libelf-devel
sudo yum install -y asciidoc
sudo yum install -y audit-libs-devel
sudo yum install -y bash
sudo yum install -y bc
sudo yum install -y binutils
sudo yum install -y binutils-devel
sudo yum install -y bison
sudo yum install -y diffutils
sudo yum install -y elfutils
sudo yum install -y elfutils-devel
sudo yum install -y elfutils-libelf-devel
sudo yum install -y findutils
sudo yum install -y flex
sudo yum install -y gawk
sudo yum install -y gcc
sudo yum install -y gettext
sudo yum install -y gzip
sudo yum install -y hmaccalc
sudo yum install -y hostname
sudo yum install -y java-devel
sudo yum install -y m4
sudo yum install -y make
sudo yum install -y module-init-tools
sudo yum install -y ncurses-devel
sudo yum install -y net-tools
sudo yum install -y newt-devel
sudo yum install -y numactl-devel
sudo yum install -y openssl
sudo yum install -y patch
sudo yum install -y pciutils-devel
sudo yum install -y perl
sudo yum install -y perl-ExtUtils-Embed
sudo yum install -y pesign
sudo yum install -y python-devel
sudo yum install -y python-docutils
sudo yum install -y redhat-rpm-config
sudo yum install -y rpm-build
sudo yum install -y sh-utils
sudo yum install -y tar
sudo yum install -y xmlto
sudo yum install -y xz
sudo yum install -y zlib-devel
sudo yum install -y "kernel-devel-uname-r == $(uname -r)"
sudo yum install -y libtool
sudo yum install -y byacc
sudo yum install -y gcc
sudo yum install -y sysstat
