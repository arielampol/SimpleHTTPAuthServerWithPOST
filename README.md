# SimpleHTTPAuthServerWithPOST
Simple HTTP Server with Authentication that accepts POST Requests

Based on https://github.com/tianhuil/SimpleHTTPAuthServer with POST handling added from https://gist.github.com/mdonkers/63e115cc0c79b4f6b8b3a6b797e485c7

Usage is pretty much the same:
```
python SimpleHTTPAuthServerWithPOST.py [-h] [--dir DIR] [--https] port key
```

Example:
```
python SimpleHTTPAuthServerWithPOST.py --dir /opt/data/http 8004 user:verysecurepassword
```

Logging, of GET requests and dumps of POST requests, is done to stdout.
