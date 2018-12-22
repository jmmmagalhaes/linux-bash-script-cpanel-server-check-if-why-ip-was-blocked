# linux-bash-script-cpanel-server-check-if-why-ip-was-blocked
Linux bash script that will grep user defined log files and iptables/CSF if contains user defined phrase (for example IP address)
Aim was to check if and why was some IP blocked on CentOS cPanel server.

Set execute permission: chmod +x isipblocked
Run script: ./isipblocked 1.2.3.4

Edit script to adjust log file paths. It contains path to log files on Centos server, some log paths are only used by Cpanel hosting control panel.
