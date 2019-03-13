# nodejs-server-scalling

```sh
# Start the servers
make run

# Stop the servers
make stop
```

## Install the performance loader tools for loader testing
[Install wrk](https://github.com/wg/wrk/wiki/Installing-wrk-on-Linux)

Run the loader command:
```sh
wrk -t12 -c400 -d30s http://127.0.0.1:3000
```