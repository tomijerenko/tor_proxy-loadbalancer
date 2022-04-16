# tor-proxy-loadbalancer
The tool is used as a proxy that load balances requests through randomly selected TOR circuits.

Run `make` to see options

## Run and Test
* `make docker-start`
* `curl --proxy localhost:8080 ip.me`


### Notes
You can restart tor-circuit containers within tor-loadbalancer container. This recreates the circuits with new IPs.
