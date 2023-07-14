# Package Requirements
`dnf install nfs autofs -y` (RHEL command)
nfs 
autofs 

## Server file config `/etc/exports`
Export directory with `/etc/exports`
Explain fields:

(1) Dir (2) Client list (3) Options - behaviors on NFS exports

## Server file config `/etc/auto.master`
(1) Mount point (2) auto-mount - or map configuration 

sample: 
/automount  /etc/auto.share

## Server file config `/etc/auto.shared`
(1) Mountpoint - in hierachy  (2)Access privileges,options along with (3)Client-ip:/dirOnClient
sample:
/private  -rw,soft,intr 192.168.1.100:/private
/public   -ro,soft,sync 192.168.1.100:/public

