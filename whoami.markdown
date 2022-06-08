---
layout: page
title: Who Am I
permalink: /whoami/
---

# Intro

I'm Chris Annable, a nerd.

Professionally, I work as a solutions architect for central IT at a higher ed institution in Ontario, Canada.

# Hobby Projects

I tend to bounce between hobby projects. I'll have a flurry of activity on a project, then shelf it for a random period of time. This is not an exhaustive list of stuff (these are the most fully-baked things); if you want that go [here](https://github.com/cannable/).

| Project                                                            | Description                                                                                                                                                                                                            |
| ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [docker-unifi](https://github.com/cannable/docker-unifi)           | The Unifi Network Controller app in a very simple container. Some day, I'll fix the logging.                                                                                                                           |
| [docker-metasploit](https://github.com/cannable/docker-metasploit) | Nightly MSF builds in a Kali container. I build this when I need it and, since they're nightlies, constantly building it would be a waste of bandwidth. If you want to use it, you'll be happier building it yourself. |
| [docker-backup](https://github.com/cannable/docker-backup)         | Alpine with tar. This exists as a simple implementation of Docker's recommended backup strategy. I threw this at cron.                                                                                                 |
| [docker-sftp](https://github.com/cannable/docker-sftp)             | Proof of concept for on-the-fly chrooted SFTP servers in a container.                                                                                                                                                  |
| [ssh-cm](https://github.com/cannable/ssh-cm)                       | A simple SSH wrapper with a SQLite connection DB. I did this was a refresher on SQLite and actually use it a fair bit.                                                                                                 |
| [tclmpc](https://github.com/cannable/tclmpc)                       | Fully featured Tcl module for talking to MPD over a TCP socket.                                                                                                                                                        |
| [tclmpc-cli](https://github.com/cannable/tclmpc-cli)               | A CLI tool to serve as a demo/showcase for tclmpc. Sorta mimics mpc in some extremely broad ways (it's pretty different).                                                                                              |

# Experience/Interests

I tried to keep this short, but I tend to get drawn to complicated things... I like learning new stuff.

* Automation
    * Ansible
    * PagerDuty Rundeck
    * DevOps, and topics around process automation and large system design are super cool
    * HashiStack - Consul, Vault, Terraform, Nomad
* Containers
    * I make container images (see above) with a mixture of Docker and buildah
    * I tinker with container technologies all the time, and run some on my home network 24/7
* Server virtualization
    * VMware Stack - ESXi, vSphere/vCenter (embedded PSC, ELM, cert management), vSphere Replication, Site Recovery
    * VxRail/vSAN
    * Citrix XenServer
    * XCP, XCP-NG (Vates, you are awesome)
    * QEMU/KVM - libvirt and not, system and user, 
    * QEMU/Xen - a bit, prefer working with XAPI
    * Nutanix running ESXi, Hyper-V, and Acropolis
* Enterprise storage - iSCSI SAN planning/deployment/management/monitoring/tuning. Specifically:
    * Dell Compellent ("SC Series") - SC8000, SC7020, SC3020, SC2080.
    * Dell EqualLogic ("PS Series") FW 6.x+ - PS6600 series, PS6200 series, PS6010 series (hybrid and not), PS4100 series
* Operating Systems
    * I dig operating systems a lot. I like learning how they work under the hood.
    * Linux of many kinds, servers, desktops, on real iron, VMs, and Pis
         * Traditional distros - ex. Red Hat/DNF/Yum-based, Debian/Apt-based
         * Arch
         * Specialty distros - ex. VMware Photon, CoreOS, ThinStation
    * BSD - Mostly FreeBSD and NetBSD, but a bit of DragonflyBSD and OpenBSD
    * Solaris on Sparc (neat)
    * Windows client and server (for a while I was an endpoint admin, so did a lot of driver/deployment/sysprep kinds of stuff, and then there was VDI)
* VDI
    * Citrix XenDesktop (5.x, 7.x), XenApp (6.x and 7.x+), with PVS, UPM, NetScaler Access Gateway, Web Interface, StoreFront
    * VMware View 5.x, ThinApp 5.x
* Load Balancing/Reverse Proxies
    * KEMP LoadMaster (physical and virtual)
    * NetScaler MPX
    * Apache with mod_proxy, mod_jk
    * A bit of random things like nginx and WebLogic OHS+mod_sql
* Networking
    * I've never been a network admin by trade, but really got into it in college and maintain an active interest in networking topics, ex. I've massively over-complicated my home network with subnetting (6 and 4) and VLANs, simply because I could.
    * I really like learning how network protocols work, and some places like TLS are intersections between networking and server/systems that I find nifty.
    * Ubiquiti EdgeMAX, routing, vlan-aware switching, firewalling, dual stack IPv4/6 networking (ULA and PD are cool)
    * Ubiquiti Unifi AC-LRs with the Unifi Network Controller app (see container above)
* Programming
    * Similar to networking, I've never done this as a full-time gig, but was something I kept doing after high school and I maintain an active interest in it. Most of the stuff I do is scripting, some trivial, some complicated. It's an itch I scratch every once and a while.
    * Tcl/Tk - CLI, GUI, socket-based networking
    * Powershell
    * VBS/VBA/VB (I don't really miss this, though I did write an HTTP server in VB6 once)
    * ANSI C (in college mostly)
    * AWK (I keep meaning to dig into it more)
* Software - This is where I decided to put oddball things
    * Vim, Neovim, vi, nvi
    * git
    * tmux (boy do I love tmux)
    * OpenvSwitch (with VMs and containers)
    * Sparx Enterprise Architect
    * Oracle DB - entitlement management and hosting environment design (VM guest, host, and storage config/tuning)
    * MySQL
    * XWiki
    * Atlassian products
* Seriously random
    * HiFi audio
    * Multimedia streaming protocols and codec design
    * Factorio - seriously dangerous sometimes
