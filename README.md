## Run legacy Dovecot 1.2 on FreeBSD

Dovecot 1.2 has been deprecated in upstream and FreeBSD Ports, files in this repo will allow you to build and install Dovecot 1.2 with Sieve plugin.

## Install

Before your install, please make sure no other versions of Dovecot exist on the system.

1. Run `copyfiles.sh`
2. `cd /usr/ports/mail/dovecot1/`
3. `make config` and select `MANAGESIEVE` if you need it
4. `make install clean`
5. Done!
