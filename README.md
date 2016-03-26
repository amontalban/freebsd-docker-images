# FreeBSD

This repository is the source of automated Docker images builds to have some sort of "Official" FreeBSD images.

Since `ADD` does not support extracting a remote URL (bummer) I have to copy the base.txz from official FreeBSD mirrors i.e http://ftp.freebsd.org/pub/FreeBSD/releases/amd64/ to this git repository.

I used the scratch image as source as the only needed action is to extract the base.txz tarball to have a minimal installation.

Thanks for checking this out!