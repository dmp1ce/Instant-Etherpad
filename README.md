# Instant Etherpad

Create an Etherpad instance with a few commands and share it with the world! Even if you are behind a NAT, Etherpad can be viewed by sharing the Tor hidden service .onion address.

# Requirements

- Docker
- Docker Compose
- Tor Browser (to access Etherpad)

# Usage

```
# docker-compose up -d mysql
# docker-compose up -d
# docker-compose logs explorer
CTRL-C
```

Use the .onion address from the explorer log to reach the Etherpad instance through Tor.  You'll also need to add the port `:9001` so the URL will look like: `zm7ed35ae2e4bxng.onion:9001`.
