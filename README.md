# curl
This build does not include SSL certificates, which means you have to include "-k" option to basically allow self-signed certs for https. For example:

```bash
curl -k https://www.kapparock.com
```

To use certs, simply copy all the certs from  ``/etc/ssl`` of your host machine to ``/etc/ssl`` of the router.
