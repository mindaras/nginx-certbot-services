# NGINX with SSL Configuration Using Let's Encrypt

## Start

1. Replace `example.org` with your domain name in `data/nginx/app.conf`
2. Replace `example.org` with your domain name in `init-letsencrypt.sh`
3. Add your email address on `line 11` in `init-letsencrypt.sh`
4. Run `chmod +x init-letsencrypt.sh`
5. Run `sudo ./init-letsencrypt.sh`
6. Run `docker-compose up -d`
