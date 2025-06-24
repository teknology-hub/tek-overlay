# tek-overlay

This is a Gentoo package overlay for teknology-hub software. To use it, add the following to your `/etc/portage/repos.conf`:
```ini
[tek-overlay]
location = /var/db/repos/tek-overlay
sync-type = git
sync-uri = https://github.com/teknology-hub/tek-overlay.git
```
