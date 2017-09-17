# cuchi

``cuchi`` is a forked of [localtunnel](https://github.com/progrium/localtunnel). Read file `README.original.md` or visit the original project to get more information.

## Install cuchi

Binary releases have not been set up yet, so you'll need Go to get started:
    $ go install github.com/michlabs/cuchi

## Usage

`cuchi` binary runs in both server and client mode
```
# server mode
$ cuchi -s your_server.com:1203 your_server.com:80

# client mode
$ cuchi your_server.com:1203 localhost:8080 your_subdomain
```
Then the request to `your_subdomain.your_server.com` will be tunnelled to the `localhost:8080`

## License

BSD