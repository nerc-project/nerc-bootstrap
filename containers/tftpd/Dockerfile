FROM ghcr.io/nerc-project/nerc-bootstrap/base:rl9

EXPOSE 69/udp

RUN install -d -o root -g dnsmasq /var/lib/tftpboot

COPY tftp.conf /etc/dnsmasq.d/tftp.conf
