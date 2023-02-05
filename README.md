# Simple NodeJS WebServer

Simple NodeJS WebServer running from a single file

## Usage

Simply run it with:

```console
$ node server.js
```

Or

```console
$ ./server.js
```

And it will use hardcoded port and hostname. To define something else, simply define these environment variables:

```bash
# Define environment variables
NODE_WEB_DEBUG=true
NODE_WEB_HOST="your-hostname"
NODE_WEB_ROOT="."
NODE_WEB_PORT=7000

# Start the server
node server.js
```

## Author

* [@Jiab77](https://github.com/Jiab77)
