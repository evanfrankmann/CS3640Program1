# CS3640Program1

Developed a simple web server capable of handling one GET request at a time. Specifically, the web server will:
- Create a connection socket when contacted by an http client.
- Accept and parse the HTTP request from that connection.
- Get the requested file from the server's file system.
- Create an http response message consisting of the requested file preceded by header lines.
- Send the response back to the client.

Developed a simple web proxy which understands http GET requests and is able to cache web pages. Specifically, the web proxy will:
- Establish a connection socket when contacted by a client.
- Accept and parse the HTTP GET request from the client.
- Check the local cache for the requested web page.
- If not found in cache, forward the request to the target web server.
- Retrieve the requested web page from the target web server, if not in cache.
- Cache the retrieved web page for future requests.
- Create an HTTP response message containing the requested web page preceded by header lines.
- Send the response back to the client.
