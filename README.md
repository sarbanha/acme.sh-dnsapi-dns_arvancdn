# Arvan Cloud DNSAPI

This code is pushed to ACME.SH repository as and additional dnsapi module for Let's Encrypt SSL Certificate management.

# Usage
Make you sure have `acme.sh` [installed](https://github.com/acmesh-official/acme.sh).

Create API key on Arvan Cloud and export the following environment variable:

```
export ARVAN_API_KEY="SAMPLE-2e2d-51ef-9c8c-bf113b59be0d"
```

Run `acme.sh` to issue your SSL Certificate:
```
acme.sh --issue -d yourdomain.tld --dns dns_arvandcdn
```

**Note:** You cain find `dns_arvancdn.sh` inside `[acme.sh installation directory]/dnsapi`.


