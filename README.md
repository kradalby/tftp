# tftp

Most of the content from my TFTP server. For quick deployment.

## Install

    :::
    git clone https://github.com/kradalby/tftp.git /srv/tftp
    apt-get install tftpd-hba
    chown -R tftp:tftp /srv/tftp
    chmod -R +r /srv/tftp

If you need write access, add --create to /etc/default/tftpd-hpa
