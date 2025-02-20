FROM ghcr.io/nerc-project/nerc-bootstrap/base:rl9

RUN install -d -o root -g dnsmasq /var/lib/dnsmasq/dhcp-hostsdir

COPY base.conf /etc/dnsmasq.d/
