# Traefik setup 

## Actions

### docker-compose.yml

- change the host domain (i.e. monitor.yourdomain.com) with yours

### acme.json

- change permissions: `chmod 600 /var/acme.json`

### traefik.yml

- change the credentials using a htpasswd generator (e.g. https://www.web2generators.com/apache-tools/htpasswd-generator) 

## Notes

- Letsencrypt takes a couple of minutes to provide the certificate. Therefore allow 5 minute before accessing your domain.
- Did it work? offer me a coffee: buymeacoffee.com/theunfollower

