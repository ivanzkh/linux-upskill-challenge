## Day 4 – Installing Software and Exploring the File System

### Objective

* Install software using APT.
* Explore the Linux directory hierarchy.
* Inspect configuration and log files.
* Use Midnight Commander for navigation.

---

### Package Installation with APT

Installed Midnight Commander (mc) from Ubuntu repositories.

Command used:

```
sudo apt install mc
```

### Using Midnight Commander

Started Midnight Commander:

```
mc
```

Purpose:

* Visual file manager.
* Dual-pane navigation.
* Fast inspection of directories and files.


### Directory Exploration

Explored standard Linux directories using `mc` and `ls`.

Key directories reviewed:

* `/root`
  Root user home directory. Restricted access.
* `/home`
  User home directories.
* `/sbin`
  System administration binaries.
* `/etc`
  System and application configuration files.
* `/var/log`
  System and service logs.

Command used:

```
ls /etc
```

---

### Configuration and Log Files Viewed

Viewed files using `less` and `mc`:

* `/etc/passwd`
  User account definitions.
* `/etc/ssh/sshd_config`
  SSH server configuration.
* `/var/log/auth.log`
  Authentication and SSH login events.
  

### Filesystem Documentation

Reviewed Linux filesystem hierarchy:

```
man hier
```

