# jsonserver

Sample server to return local json files

* Examples

````
  $ cat > /var/tmp/test.json
  {"this": "that"}

  $ python server.py

  $ curl http://localhost:5555/json/var/tmp/test.json
````
