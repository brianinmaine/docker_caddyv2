# docker_caddyv2
All these services run in docker containers with caddy as a reverse proxy so you only need 80 and 443 open on your router/firewall. Check out the Caddyfile, where all the work is being done to proxy.
When adding a new service, I create a new directory, paste in a new docker-compose.yaml and modify it. When I know that works I add a new entry to Caddyfile and have a new domain name with https!
