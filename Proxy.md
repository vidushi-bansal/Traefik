# Proxy 
A proxy server acts as a gateway between you and the internet. It’s an intermediary server separating end users from the websites they browse. Proxy servers provide varying levels of functionality, security, and privacy depending on your use case, needs, or company policy.

If you’re using a proxy server, internet traffic flows through the proxy server on its way to the address you requested. The request then comes back through that same proxy server (there are exceptions to this rule), and then the proxy server forwards the data received from the website to you.

## How Does a Proxy Server Operate?
Every computer on the internet needs to have a unique Internet Protocol (IP) Address. Think of this IP address as your computer’s street address. Just as the post office knows to deliver your mail to your street address, the internet knows how to send the correct data to the correct computer by the IP address.

A proxy server is basically a computer on the internet with its own IP address that your computer knows. When you send a web request, your request goes to the proxy server first. The proxy server then makes your web request on your behalf, collects the response from the web server, and forwards you the web page data so you can see the page in your browser.

When the proxy server forwards your web requests, it can make changes to the data you send and still get you the information that you expect to see. A proxy server can change your IP address, so the web server doesn’t know exactly where you are in the world. It can encrypt your data, so your data is unreadable in transit. And lastly, a proxy server can block access to certain web pages, based on IP address.

## Why Should You Use a Proxy Server?
Bandwidth savings and improved speeds: Organizations can also get better overall network performance with a good proxy server. Proxy servers can cache (save a copy of the website locally)
Privacy benefits: Individuals and organizations alike use proxy servers to browse the internet more privately. Some proxy servers will change the IP address and other identifying information the web request contains. This means the destination server doesn’t know who actually made the original request, which helps keeps your personal information and browsing habits more private.
Improved security: Proxy servers provide security benefits on top of the privacy benefits. You can configure your proxy server to encrypt your web requests to keep prying eyes from reading your transactions. 

## Types of Proxy Servers
### Transparent Proxy
A transparent proxy, also known as an inline proxy, intercepting proxy or forced proxy, is a server that intercepts the connection between an end-user or device and the internet. For example, a user on a corporate network may be surfing the Internet. The user requests to view a news article on cnn.com, and views the same content as they would on their local connection at home.
Uses for Transparent Proxy on Client Side
Content Filtering: You can use a transparent proxy to filter out unwanted content, defined via proxy settings. For example, when a specific website is requested, the proxy can refrain from forwarding the request to the web server. 
Gateway Proxies: You can use a gateway proxy to modify or block network traffic based on rules. For example, a firewall is a transparent proxy, which allows traffic to pass between an internal network and the Internet, but blocks traffic if it violates the firewall’s rule table.
Transparent Caching: If multiple people are accessing the same content from the same location—for example, many students viewing the same news site via their university network—it is more efficient to initially cache the content, and serve it from cache to subsequent users. A transparent proxy can do this for an organization, facility or neighborhood.
Traffic Monitoring: If you operate a network, you can set up a transparent proxy to monitor user traffic and behavior.
Authentication: Public wifi spots and cellular Internet operators sometimes use transparent proxies to force users to authenticate themselves on the network, and agree to terms of service. Only after a user authenticates and agrees, are they allowed to surf.


### Anonymous Proxy
An anonymous proxy will identify itself as a proxy, but it won’t pass your IP address to the website – this helps prevent identity theft and keep your browsing habits private. They can also prevent a website from serving you targeted marketing content based on your location.

### Distorting proxy
A distorting proxy server passes along a false IP address for you while identifying itself as a proxy. This serves similar purposes as the anonymous proxy, but by passing a false IP address, you can appear to be from a different location to get around content restrictions.

### High Anonymity proxy 
High Anonymity proxy servers periodically change the IP address they present to the web server, making it very difficult to keep track of what traffic belongs to who. High anonymity proxies, like the TOR Network, is the most private and secure way to read the internet.

