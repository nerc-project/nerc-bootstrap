FROM rockylinux/rockylinux:9

RUN dnf install -y \
  dnsmasq \
  && dnf clean all -y

COPY dnsmasq.conf /etc/dnsmasq.conf

CMD [ \
  "/sbin/dnsmasq", \
  "-k", \
  "--conf-file=/etc/dnsmasq.conf", \
  "--log-queries", \
  "--log-facility=-", \
  "--dhcp-authoritative" \
]
