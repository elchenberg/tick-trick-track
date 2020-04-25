FROM alpine:3.11.6
RUN apk add --no-cache rsyslog rsyslog-tls
COPY rsyslog.conf /etc/rsyslog.conf
CMD ["rsyslogd", "-n"]
