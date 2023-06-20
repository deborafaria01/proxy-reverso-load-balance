# > Reverse Proxy

A reverse proxy is a server that sits in front of one or more web servers, intercepting requests from clients. Reverse proxies are
typically implemented to help increase security, performance, and reliability.

This is different from a forward proxy, where the proxy sits in front of the clients. With a reverse proxy, when clients send requests to
the origin server of a website, those requests are intercepted at the network edge by the reverse proxy server. The reverse proxy server
will then send requests to and receive responses from the origin server.

The difference between a forward and reverse proxy is subtle but important. A simplified way to sum it up would be to say that a forward
proxy sits in front of a client and ensures that no origin server ever communicates directly with that specific client. On the other
hand, a reverse proxy sits in front of an origin server and ensures that no client ever communicates directly with that origin server.

<h1 align="center"><img src = "https://github.com/deborafaria01/proxy-reverso-load-balance/blob/main/reverse_proxy.png"></h1>

#

# > Load Balance

Load balancing refers to efficiently distributing incoming network traffic across a group of backend servers, also known as a server farm or server pool.

Modern high‑traffic websites must serve hundreds of thousands, if not millions, of concurrent requests from users or clients and return the correct text, images, video, or application data, all in a fast and reliable manner. To cost‑effectively scale to meet these high volumes, modern computing best practice generally requires adding more servers.

A load balancer acts as the “traffic cop” sitting in front of your servers and routing client requests across all servers capable of fulfilling those requests in a manner that maximizes speed and capacity utilization and ensures that no one server is overworked, which could degrade performance. If a single server goes down, the load balancer redirects traffic to the remaining online servers. When a new server is added to the server group, the load balancer automatically starts to send requests to it.

In this manner, a load balancer performs the following functions:

* Distributes client requests or network load efficiently across multiple servers
* Ensures high availability and reliability by sending requests only to servers that are online
* Provides the flexibility to add or subtract servers as demand dictates

<h1 align="center"><img src = "https://github.com/deborafaria01/proxy-reverso-load-balance/blob/main/load_balance.png"></h1>





  
