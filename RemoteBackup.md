# Remote Backup #

## Installation ##

First, you need to enable root account on your Mac:

```
$ sudo passwd root
Changing password for root.
New password: ********
Retype new password: ********
```

Login as root:

```
$ su -
Password: ********
```

And generate the keys for passwordless ssh connection:

```
$ ssh-keygen -t rsa
```

Accept the defaults. The private and public keys should reside in ~/.ssh. Do not enter a passphrase, just hit enter twice.



To be continued...