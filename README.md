# NGINX with SSL Configuration Using Let's Encrypt

## Start

1. Replace `example.org` with your domain name in `data/nginx/app.conf`
2. Replace `example.org` with your domain name in `init-letsencrypt.sh` (if you’ve changed the directories of the shared Docker volumes, make sure you also adjust the `data_path` variable as well)
3. Add your email address on `line 11` in `init-letsencrypt.sh`
4. Run `chmod +x init-letsencrypt.sh`
5. Run `sudo ./init-letsencrypt.sh`
6. Run `docker-compose up -d`

Note: save edits to `docker-compose.yaml` without formatting (cmd + shift + p) to preserve commas in nginx bash script
