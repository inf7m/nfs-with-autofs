# Description
Practice repo for working with nfs and autofs service

# Table of content

1. [autofs.service](#introduction-autofs.service)
2. [nfs.service](#introduction)
3. [Set-up policy](#set-up-policy)

## autofs.service <a name="introduction-autofs.service></a>

autofs - is a daemon which is automount points

autofs mechanism:

First, define the configuration at `/etc/auto.master`

3 fields need to specify
(1) Mount point (2) Location of map file (3) Optional field

