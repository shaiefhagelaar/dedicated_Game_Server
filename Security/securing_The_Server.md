# Securing The Server

The server runs on:

Command(-s) to use to check the info:

This will output the following info:

Command
    lsb_release -a

- Distributor ID
- Description
- Release
- Codename

If your not familiar with the attributes try to do your research.

Kernel Specifications:

Command
    uname -a


## To do list

Here's a useful link to securing your Debian 'Game' server:

    https://www.debian.org/doc/manuals/securing-debian-manual/index.en.html

Overview of setting up security:

1. Introduction

    1.1. Authors
    1.2. Where to get the manual (and available formats)
    1.3. Organizational notes/feedback
    1.4. Prior knowledge
    1.5. Things that need to be written (FIXME/TODO)
    1.6. Credits and thanks!

2. Before you begin

    2.1. What do you want this system for?
    2.2. Be aware of general security problems
    2.3. How does Debian handle security?

3. Before and during the installation

    3.1. Choose a BIOS password
    3.2. Partitioning the system

    3.2.1. Choose an intelligent partition scheme
    3.2.2. Selecting the appropriate file systems

    3.3. Do not plug to the Internet until ready
    3.4. Set a root password
    3.5. Run the minimum number of services required

    3.5.1. Disabling daemon services
    3.5.2. Disabling inetd or its services

    3.6. Install the minimum amount of software required

    3.6.1. Removing Perl

    3.7. Read the Debian security mailing lists

4. After installation

    4.1. Subscribe to the Debian Security Announce mailing list
    4.2. Execute a security update

    4.2.1. Security update of libraries
    4.2.2. Security update of the kernel

    4.3. Change the BIOS (again)
    4.4. Set a LILO or GRUB password
    4.5. Disable root prompt on the initramfs
    4.6. Remove root prompt on the kernel
    4.7. Restricting console login access
    4.8. Restricting system reboots through the console
    4.9. Restricting the use of the Magic SysRq key
    4.10. Mounting partitions the right way

    4.10.1. Setting /tmp noexec
    4.10.2. Setting /usr read-only

    4.11. Providing secure user access

    4.11.1. User authentication: PAM
    4.11.2. Password security in PAM
    4.11.3. User access control in PAM
    4.11.4. User limits in PAM
    4.11.5. Control of su in PAM
    4.11.6. Temporary directories in PAM
    4.11.7. Configuration for undefined PAM applications
    4.11.8. Limiting resource usage: the limits.conf file
    4.11.9. User login actions: edit /etc/login.defs
    4.11.10. User login actions: edit /etc/pam.d/login
    4.11.11. Restricting ftp: editing /etc/ftpusers
    4.11.12. Using su
    4.11.13. Using sudo
    4.11.14. Disallow remote administrative access
    4.11.15. Restricting users's access
    4.11.16. User auditing
    4.11.17. Reviewing user profiles
    4.11.18. Setting users umasks
    4.11.19. Limiting what users can see/access
    4.11.20. Generating user passwords
    4.11.21. Checking user passwords
    4.11.22. Logging off idle users

    4.12. Using tcpwrappers
    4.13. The importance of logs and alerts

    4.13.1. Using and customizing logcheck
    4.13.2. Configuring where alerts are sent
    4.13.3. Using a loghost
    4.13.4. Log file permissions

    4.14. Adding kernel patches
    4.15. Protecting against buffer overflows

    4.15.1. Kernel patch protection for buffer overflows
    4.15.2. Testing programs for overflows

    4.16. Secure file transfers
    4.17. File system limits and control

    4.17.1. Using quotas
    4.17.2. The ext2 filesystem specific attributes (chattr/lsattr)
    4.17.3. Checking file system integrity
    4.17.4. Setting up setuid check

    4.18. Securing network access

        4.18.1. Configuring kernel network features
        4.18.2. Configuring syncookies
        4.18.3. Securing the network on boot-time
        4.18.4. Configuring firewall features
        4.18.5. Disabling weak-end hosts issues
        4.18.6. Protecting against ARP attacks

    4.19. Taking a snapshot of the system
    4.20. Other recommendations

        4.20.1. Do not use software depending on svgalib

5. Securing services running on your system

    5.1. Securing ssh

        5.1.1. Chrooting ssh
        5.1.2. Ssh clients
        5.1.3. Disallowing file transfers
        5.1.4. Restricing access to file transfer only

    5.2. Securing Squid
    5.3. Securing FTP
    5.4. Securing access to the X Window System

        5.4.1. Check your display manager

    5.5. Securing printing access (the lpd and lprng issue)
    5.6. Securing the mail service

        5.6.1. Configuring a Nullmailer
        5.6.2. Providing secure access to mailboxes
        5.6.3. Receiving mail securely

    5.7. Securing BIND

        5.7.1. Bind configuration to avoid misuse
        5.7.2. Changing BIND's user
        5.7.3. Chrooting the name server

    5.8. Securing Apache

        5.8.1. Disabling users from publishing web contents
        5.8.2. Logfiles permissions
        5.8.3. Published web files

    5.9. Securing finger
    5.10. General chroot and suid paranoia

        5.10.1. Making chrooted environments automatically

    5.11. General cleartext password paranoia
    5.12. Disabling NIS
    5.13. Securing RPC services

        5.13.1. Disabling RPC services completely
        5.13.2. Limiting access to RPC services

    5.14. Adding firewall capabilities

        5.14.1. Firewalling the local system
        5.14.2. Using a firewall to protect other systems
        5.14.3. Setting up a firewall

6. Automatic hardening of Debian systems

    6.1. Harden
    6.2. Bastille Linux

7. Debian Security Infrastructure

    7.1. The Debian Security Team
    7.2. Debian Security Advisories

        7.2.1. Vulnerability cross references
        7.2.2. CVE compatibility

    7.3. Security Tracker
    7.4. Debian Security Build Infrastructure

        7.4.1. Developer's guide to security updates

    7.5. Package signing in Debian

        7.5.1. The current scheme for package signature checks
        7.5.2. Secure apt
        7.5.3. Per distribution release check
        7.5.4. Release check of non Debian sources
        7.5.5. Alternative per-package signing scheme

8. Security tools in Debian

    8.1. Remote vulnerability assessment tools
    8.2. Network scanner tools
    8.3. Internal audits
    8.4. Auditing source code
    8.5. Virtual Private Networks

        8.5.1. Point to Point tunneling

    8.6. Public Key Infrastructure (PKI)
    8.7. SSL Infrastructure
    8.8. Antivirus tools
    8.9. GPG agent

9. Developer's Best Practices for OS Security

    9.1. Best practices for security review and design
    9.2. Creating users and groups for software daemons

10. Before the compromise

    10.1. Keep your system secure

        10.1.1. Tracking security vulnerabilities
        10.1.2. Continuously update the system
        10.1.3. Avoid using the unstable branch
        10.1.4. Security support for the testing branch
        10.1.5. Automatic updates in a Debian GNU/Linux system

    10.2. Do periodic integrity checks
    10.3. Set up Intrusion Detection

        10.3.1. Network based intrusion detection
        10.3.2. Host based intrusion detection

    10.4. Avoiding root-kits

        10.4.1. Loadable Kernel Modules (LKM)
        10.4.2. Detecting root-kits

    10.5. Genius/Paranoia Ideas - what you could do

        10.5.1. Building a honeypot

11. After the compromise (incident response)

    11.1. General behavior
    11.2. Backing up the system
    11.3. Contact your local CERT
    11.4. Forensic analysis
    11.5. Analysis of malware

12. Frequently asked Questions (FAQ)

    12.1. Security in the Debian operating system

        12.1.1. Is Debian more secure than X?
        12.1.2. My system is vulnerable! (Are you sure?)

    12.2. Specific software

        12.2.1. proftpd is vulnerable to a Denial of Service attack.
        12.2.2. After installing portsentry, there are a lot of ports open.

    12.3. Questions regarding the Debian security team

A. Changelog/History
B. Appendix

    B.1. The hardening process step by step
    B.2. Configuration checklist
    B.3. Setting up a stand-alone IDS
    B.4. Setting up a bridge firewall

        B.4.1. A bridge providing NAT and firewall capabilities
        B.4.2. A bridge providing firewall capabilities
        B.4.3. Basic IPtables rules

    B.5. Sample script to change the default Bind installation.
    B.6. Security update protected by a firewall
    B.7. Chroot environment for SSH

        B.7.1. Chrooting the ssh users
        B.7.2. Chrooting the ssh server
        B.7.3. Chroot environment for Apache
        B.7.4. See also
