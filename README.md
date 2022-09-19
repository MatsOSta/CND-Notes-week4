# CND-Notes-week4

Generic system hardening
Must be done at system and application levels - and integrated 
preliminary planning
physical system security
operating


# Linux security controls
User and groups files
/etc/passwords
see slides for more info
google what does 777 mean
what does x on directory mean

setUID set GID
SetUI runs with same priviledge as user
setGID runs with same priviledge as group


OS-level security tools and techniques
OS installation: Software selection and Initail Setup
Patch Management
Network-level access controls
using host firewall systems
antivirus software
system validation
user Managment (and auditing)
password ageing
root Delegation
Logging (and log inspection)

Common OS Security Features
logon sec
Digital certi sec
file and folder sec
shared resource sec
security poli
remote access sec
wireless sec
distaer rec

Encrypt Data Communications
scp, ssh, sftp
Best practice Unnecessary software
Best practive Updates
Automatic updates?

baseline security change control

netstat -at
netstat -au
Fail2ban

Best practice Storage Security
disable USB bott?
Separate Disk Partitions
Disk quotas
applyappropriate security options when mounting noexec, nsuid, ro many other options

System logs tracking
some logs related to topics covered
Email Notification - kanary

SSMTP configuration
Outbound SMTP config needs to happen
where no easy mail solution available

Best Practice Backups
Offsite and Offline backups are essential for servers
backups must be verified and tested
rsync, is a popular choice for certain backup types
backup rules
3 locations
2 Media types
1 Offline copy 

Best practice Audits
Even the most secure sercer will eventually become culnerable
audits uncoer adjustments
tend to be automated

(learn reg expressions)
