# No longer required

Modern Watchgurad allow downloading of a OpenVPN configuration file from  https://your gateway here/sslvpn_logon.shtml that works out of the box.

At least it does for me on Ubuntu 24.04 LTS under KDE, which means I no longer have hardware to test this against.

# ike

Also known as the Shrewsoft VPN Manager.

The Shrew Soft VPN Client for Linux and BSD is an IPsec Client for FreeBSD, NetBSD and many Linux based operating systems. This version is distributed under an OSI approved open source license and is hosted in a public subversion repository. It supports most of the features available in the Windows VPN Client version with the exception of those which are not cross platform compatible.

Website: https://www.shrew.net/home

# Install

`snap install --edge ike-qt-lts` or use something like the Ubuntu Software store

# Usgae

Before use, start the service
`sudo snap start ike-qt`

To open the graphical interface 
`/snap/bin/ike-qt-lts.qikea`

Example : https://github.com/tomchiverton/ike/wiki#basic-start-up-script

# Still in beta, some features may not work.
