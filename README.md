# pam_smbpass
PAM entries to have SSH-login or console-login update smbpass-db with credentials.

This also synchronizes a changed password.

## FreeBSD
This is so far for FreeBSD only.

## Samba
Only samba43 seems to come with pam_smbpass to compile. samba44 does not, and I have not found any way to compile pam_smbpass with it.

## Warning
Always backup you PAM-files!

## Source
I used this a long long time ago, then lost how (and never saved my PAM-files) but then found this [forum-thread](https://forums.freebsd.org/threads/49581/).
