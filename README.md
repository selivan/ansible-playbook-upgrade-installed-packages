When upgrading packages on multiple hosts with `-m a-t -a "state=latest pkg=..."` it's easy to install unnecessary packages on wrong hosts group. This playbook upgrades packages only if they are present on the host. Works for Debian-like distributives(Ubuntu etc).

If you find this useful, please star it on GitHub.
