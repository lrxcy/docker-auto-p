# docker-auto-p

## Installation

1. move the `./etc/cron.daily/docker-updater` script to `/etc/cron.daily/docker-updater`
2. move the `./etc/default/docker-updater` config file to `/etc/default/docker-updater`
3. update the setup in `/etc/default/docker-updater` -- at least set `ENABLED=1`
4. create a list of Docker Compose config files in `/etc/docker-compose-auto-update.conf` - one path to a `docker-compose.yml` per line.

Docker-Tools Import environment variables

Afterwards, configure `/etc/default/docker-updater` and at least set `ENABLED=1`.
This way, you'll always stay up-to-date with bug fixes and new features :)
