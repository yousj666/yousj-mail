# 📮 yousj.cc Mail

My personal mail server is now live! Get your very own `@yousj.cc` email address.

Real email on my own infrastructure. No ads, no tracking — just fast, private IMAP/SMTP that works with any mail app: Gmail, Outlook, Apple Mail, Thunderbird, you name it.

## How to register

Send an email to **hello@yousj.cc** with the username you'd like, and I'll set one up for you.

## Server settings

- 📥 IMAP: `mail.yousj.cc`, port `993` (SSL/TLS)
- 📤 SMTP: `mail.yousj.cc`, port `2525` (STARTTLS)

Use your full email address as the username. Port 2525 is used instead of the usual 587 so it also works behind VPNs that block standard mail ports.

## Under the hood

- Postfix + Dovecot + OpenDKIM on a lightweight VPS
- SPF, DKIM and DMARC all enabled
