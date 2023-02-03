# finewall-mailer

A dockerized [Postfix](http://www.postfix.org/) mail transfer agent.

## Setup

Requires the following environment variables:

```
SMTP_FORCE_FROM=...
SMTP_SERVER=...
SMTP_PORT=587
SMTP_USERNAME=...
SMTP_PASSWORD=...
SERVER_HOSTNAME=mailer.localhost
```

Additionally, for enabling debugging logs, `DEBUG=yes` may be set.