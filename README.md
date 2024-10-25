# New deployment playbook 010-tls
- Red hat trust update
- ubuntu trust update
```
verbose=0
fresh=0
default=0
CERTSCONF=/etc/ca-certificates.conf
CERTSDIR=/usr/share/ca-certificates
LOCALCERTSDIR=/usr/local/share/ca-certificates
CERTBUNDLE=ca-certificates.crt
ETCCERTSDIR=/etc/ssl/certs
HOOKSDIR=/etc/ca-certificates/update.d
```
- debian trust update
