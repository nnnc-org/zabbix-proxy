# Zabbix Proxy Compose

This is a docker-compose file to run a Zabbix Proxy with a sqlite3 database.

## Configuration

Configuration is very easy. Just copy the `.env.example` file to `.env`, and change the values to your needs.

For the wireguard configuration, just download / generate a wireguard config from your server and save it as `wireguard.conf` in the same directory as the `docker-compose.yml` file.