# systemd - System and Service Manager
systemd is a suite of basic building blocks for a Linux system. It provides a system and service manager that runs as PID 1 and starts the rest of the system.

systemd provides aggressive parallelization capabilities, uses socket and D-Bus activation for starting services, offers on-demand starting of daemons, keeps track of processes using Linux control groups, maintains mount and automount points, and implements an elaborate transactional dependency-based service control logic. systemd supports SysV and LSB init scripts and works as a replacement for sysvinit.

Other parts include a logging daemon, utilities to control basic system configuration like the hostname, date, locale, maintain a list of logged-in users and running containers and virtual machines, system accounts, runtime directories and settings, and daemons to manage simple network configuration, network time synchronization, log forwarding, and name resolution.

# Booting

*   [Automatic Boot Assessment](https://systemd.io/AUTOMATIC_BOOT_ASSESSMENT/)
*   [Boot Loader Interface](https://systemd.io/BOOT_LOADER_INTERFACE/)
*   [Mount Requirements](https://systemd.io/MOUNT_REQUIREMENTS/)
*   [TPM2 PCR Measurements Made by systemd](https://systemd.io/TPM2_PCR_MEASUREMENTS/)

# Manuals and Documentation for Users and Administrators

*   [API File Systems](https://systemd.io/API_FILE_SYSTEMS/)
*   [Booting Without /usr is Broken](https://systemd.io/SEPARATE_USR_IS_BROKEN/)
*   [Compatibility with SysV](https://systemd.io/INCOMPATIBILITIES/)
*   [Diagnosing Boot Problems](https://systemd.io/DEBUGGING/)
*   [Frequently Asked Questions](https://systemd.io/FAQ/)
*   [My Service Can’t Get Realtime!](https://systemd.io/MY_SERVICE_CANT_GET_REATLIME/)
*   [Socket Activation with Popular Daemons](https://systemd.io/DAEMON_SOCKET_ACTIVATION/)
*   [Tips And Tricks](https://systemd.io/TIPS_AND_TRICKS/)


## Documentation for Developers

*   [Autopkgtest - Defining tests for Debian packages](https://systemd.io/AUTOPKGTEST/)
*   [Backports](https://systemd.io/BACKPORTS/)
*   [Inhibitor Locks](https://systemd.io/INHIBITOR_LOCKS/)
*   [Journal Message Catalogs](https://systemd.io/CATALOG/)
*   [Minimal Builds](https://systemd.io/MINIMAL_BUILDS/)
*   [New Control Group Interfaces](https://systemd.io/CONTROL_GROUP_INTERFACE/)
*   [Presets](https://systemd.io/PRESET/)
*   [Testing systemd during Development in Virtualization](https://systemd.io/VIRTUALIZED_TESTING/)
*   [The Case for the /usr Merge](https://systemd.io/THE_CASE_FOR_THE_USR_MERGE/)
*   [Writing Desktop Environments](https://systemd.io/WRITING_DESKTOP_ENVIRONMENTS/)
*   [Writing Display Managers](https://systemd.io/WRITING_DISPLAY_MANAGERS/)
*   [Writing Network Configuration Managers](https://systemd.io/WRITING_NETWORK_CONFIGURATION_MANAGERS/)
*   [Writing Resolver Clients](https://systemd.io/WRITING_RESOLVER_CLIENTS/)
*   [Writing VM and Container Managers](https://systemd.io/WRITING_VM_AND_CONTAINER_MANAGERS/)
*   [Writing syslog Daemons Which Cooperate Nicely With systemd](https://systemd.io/SYSLOG/)
*   [systemd File Hierarchy Requirements](https://systemd.io/SYSTEMD_FILE_HIERARCHY_REQUIREMENTS/)
*   [systemd Optimizations](https://systemd.io/OPTIMIZATIONS/)
*   [systemd-boot UEFI Boot Manager](https://systemd.io/BOOT/)

# Project

*   [Brand](https://brand.systemd.io/)
*   [GitHub Project Page](https://github.com/systemd/systemd)
*   [Issues](https://github.com/systemd/systemd/issues)
*   [Mailing List](https://lists.freedesktop.org/mailman/listinfo/systemd-devel)
*   [Mastodon](https://mastodon.social/@pid_eins)
*   [Pull Requests](https://github.com/systemd/systemd/pulls)
*   [Releases](https://github.com/systemd/systemd/releases)
*   [mkosi Project - Build Bespoke OS Images](https://mkosi.systemd.io/)

## Publications

*   [Article in The H](http://www.h-online.com/open/features/Control-Centre-The-systemd-Linux-init-system-1565543.html)
*   [Article in The H, Part 2](http://www.h-online.com/open/features/Booting-up-Tools-and-tips-for-systemd-1570630.html)
*   [Bê-á-bá do systemd #1 (Brazilian Portuguese)](https://community.ibm.com/community/user/legacy)
*   [Bê-á-bá do systemd #2 (Brazilian Portuguese)](https://community.ibm.com/community/user/legacy)
*   [Bê-á-bá do systemd #3 (Brazilian Portuguese)](https://community.ibm.com/community/user/legacy)
*   [Bê-á-bá do systemd #4 (Brazilian Portuguese)](https://community.ibm.com/community/user/legacy)
*   [Bê-á-bá do systemd #5 (Brazilian Portuguese)](https://community.ibm.com/community/user/legacy)
*   [Bê-á-bá do systemd #6 (Brazilian Portuguese)](https://community.ibm.com/community/user/legacy)
*   [RHEL7 docs](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/system_administrators_guide/chap-managing_services_with_systemd)
*   [SUSE White Paper on systemd](https://www.suse.com/media/white-paper/systemd_in_suse_linux_enterprise_12_white_paper.pdf)
*   [Évolutions techniques de systemd (French)](https://linuxfr.org/news/evolutions-techniques-de-systemd)

## The various distributions

*   [Arch Linux bugtracker](https://gitlab.archlinux.org/archlinux/packaging/packages/systemd/-/issues)
*   [Arch Linux packages](https://www.archlinux.org/packages/core/x86_64/systemd/)
*   [Arch Linux wiki](https://wiki.archlinux.org/index.php/Systemd)
*   [Debian bugtracker](http://bugs.debian.org/cgi-bin/pkgreport.cgi?ordering=normal;archive=0;src=systemd)
*   [Debian packages](http://packages.debian.org/systemd)
*   [Debian wiki](http://wiki.debian.org/systemd)
*   [Fedora bugtracker](https://bugzilla.redhat.com/buglist.cgi?list_id=565273&classification=Fedora&query_format=advanced&bug_status=NEW&bug_status=ASSIGNED&bug_status=MODIFIED&bug_status=ON_DEV&bug_status=ON_QA&bug_status=VERIFIED&bug_status=RELEASE_PENDING&bug_status=POST&component=systemd&product=Fedora)
*   [Fedora packages](https://packages.fedoraproject.org/pkgs/systemd/systemd/)
*   [Fedora sources](https://src.fedoraproject.org/rpms/systemd)
*   [Gentoo bugtracker](https://bugs.gentoo.org/buglist.cgi?quicksearch=systemd)
*   [Gentoo packages](http://packages.gentoo.org/package/sys-apps/systemd)
*   [Gentoo wiki](http://wiki.gentoo.org/wiki/Systemd)
*   [Mageia bugtracker](https://bugs.mageia.org/buglist.cgi?field0-0-0=cf_rpmpkg&query_format=advanced&bug_status=NEW&bug_status=UNCONFIRMED&bug_status=ASSIGNED&bug_status=REOPENED&type0-0-0=substring&value0-0-0=systemd&component=RPM%20Packages&product=Mageia)
*   [Mageia packages](http://svnweb.mageia.org/packages/cauldron/systemd/current/)
*   [Ubuntu packages](https://launchpad.net/ubuntu/+source/systemd)
*   [Ubuntu wiki](https://wiki.ubuntu.com/systemd)
*   [openSUSE bugtracker](https://bugzilla.novell.com/buglist.cgi?short_desc=systemd&field0-0-0=product&type0-0-1=substring&field0-0-1=component&classification=openSUSE&value0-0-2=systemd&query_based_on=systemd&query_format=advanced&type0-0-3=substring&field0-0-3=status_whiteboard&value0-0-3=systemd&bug_status=UNCONFIRMED&bug_status=NEW&bug_status=ASSIGNED&bug_status=NEEDINFO&bug_status=REOPENED&short_desc_type=allwordssubstr&field0-0-2=short_desc&value0-0-1=systemd&type0-0-0=substring&value0-0-0=systemd&type0-0-2=substring&known_name=systemd)
*   [openSUSE instructions](http://en.opensuse.org/SDB:Systemd)
*   [openSUSE packages](https://build.opensuse.org/package/show/Base:System/systemd)

### Credits

*   [https://systemd.io/](https://systemd.io/)
