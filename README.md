# examples

This repository contains examples that I use for production.

## Ubuntu 14.04

Post-Install for a node-based web-server using nvm for node version management:

  1. [First updates, openssh-server and DHCP to Static IP](https://github.com/jpfluger/examples/blob/master/ubuntu-14.04/updates-ssh-static-ip.md)
  2. [Changing the hostname](https://github.com/jpfluger/examples/blob/master/ubuntu-14.04/changing-hostname.md)
  3. [nvm for node package managment](https://github.com/jpfluger/examples/blob/master/ubuntu-14.04/nvm-for-node-package-management.md)
  4. [Start/Stop the node server using nvm and sysvinit](https://github.com/jpfluger/examples/blob/master/ubuntu-14.04/sysvinit-and-nvm.md)
  5. [Nginx proxying multiple node sites](https://github.com/jpfluger/examples/blob/master/ubuntu-14.04/nginx-proxy.md)
  6. [Restart with monit](https://github.com/jpfluger/examples/blob/master/ubuntu-14.04/monit-restart.md)
  7. [NRPE client](https://github.com/jpfluger/examples/blob/master/ubuntu-14.04/nagios-npre-client.md) (for Ubuntu 14.04) to communicate with Nagios/Icinga2
  8. [Firewall with UFW](https://github.com/jpfluger/examples/blob/master/ubuntu-14.04/ufw.md)

Additional services:

  1. [Private NPM Registry with Sinopia](https://github.com/jpfluger/examples/blob/master/ubuntu-14.04/sinopia.md)
  2. [Icinga2 central server using nginx and postgresql](https://github.com/jpfluger/examples/blob/master/ubuntu-14.04/icinga2-server.md)  (monitors targeted devices and/or aggregates host node Nagios notifications (NRPE))
  3. Future... [Graphing Performance Data with Icinga2 and Graphite](https://github.com/jpfluger/examples/blob/master/ubuntu-14.04/icinga2-graphite.md)

## Windows

  1. [NSClient++](https://github.com/jpfluger/examples/blob/master/windows/nsclient-windows.md) (for Windows 8.1) to communicate with Nagios/Icinga2
     * It should run on all versions of MS Windows
     * It can run on Linux too but pre-compiled binaries are currently unavailable

---

## [MIT Licensed](LICENSE)
