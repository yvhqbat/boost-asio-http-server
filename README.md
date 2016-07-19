# boost-asio-http-server

HTTP Server
This example illustrates the use of asio in a simple single-threaded server implementation of HTTP 1.0. 
It demonstrates how to perform a clean shutdown by cancelling all outstanding asynchronous operations.

use:
./http_server 8090 ../doc_root

http://127.0.0.1:8090/index.html
