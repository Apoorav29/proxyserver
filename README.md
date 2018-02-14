													Computer Networks - Assignment 2

This assignment required us to build a proxy server prototype which implements the functionalities of caching. The basic prototype deals with 
simple GET requests for contents of the files present in server directory. The aim of the proxy server is to reduce the client request response
time by storing the recently accessed files in the cache of proxy server with the limited amount of allowed files in the cache. The client could 
send the request via curl requests or using browser with appropriate proxy settings.  In addition, the proxy server can handle multiple client requests
can be handled at once using threading. 

Getting Started:
				1.) python server.py   					(server's directory.)
				2.) python proxyserver.py   			(proxyserver's directory)
				3.) curl -x http://localhost:12345 http://localhost:20000/2.binary    (client request.)
				4.) curl -x http://localhost:12345 http://localhost:20000/2.binary & curl -x http://localhost:12345 http://localhost:20000/1.txt

