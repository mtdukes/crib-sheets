##Starting a simple web server
Use an example from learn_python/webapp/simple_http.py
```python
from http.server import HTTPServer, CGIHTTPRequestHandler

port = 8080
httpd = HTTPServer(('',port), GCGIHTTPRequestHandler)
print("Starting simple_httpd on port: " + str(httpd.server_port))
httpd.serve_forever()
```
Set executable bit
```bash
chmod _x PYTHON_SCRIPT.py
```
Add to top of your python script
```python
#! /usr/local/bin/python3
```
Navigate to http://localhost:8080