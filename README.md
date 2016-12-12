# pam_smbpass
Pam entries to have SSH-login or console-login update smbpass-db with credentials.

This also synchronizes a changed password.

## FreeBSD
This is so far for FreeBSD only.

## Samba
Only samba43 seems to come with pam_smbpass to compile. samba44 does not, and I have not found any way to compile pam_smbpass with it.
