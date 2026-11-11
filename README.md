# dotvpn-mirrors

Public fallback mirrors for Dot VPN signed server lists.

Control publishes `serverlist.txt` via **Admin → Ops settings → Publish mirrors** (GitHub path in this repo).

Client / invite mirror URL:

```
https://raw.githubusercontent.com/payam-foundation/dotvpn-mirrors/main/serverlist.txt
```

S3 twin (optional):

```
https://payam-dotvpn.s3.eu-west-1.amazonaws.com/mirrors/serverlist.txt
```

Do not commit secrets. Only the signed list body belongs here.
