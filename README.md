#Meowsocks
Mutable Encrypted and Obfuscated Web SOCKS

##What's this?
Mutable:The core of the protocol
Encrypted:Encrypt your connection
Obfuscated:Obfuscate your connection so that it looks just like WebSocket or HTTP
Web:Transport via HTTP or Websocket,to make it work on PaaSs

##Mutable
As is widely seen,most proxy servers can be identified 
easily by the firewall(even the popular Shadowsocks).

However,what if the protocol itself,instead of only keys,differs from server to server?

And,what if the protocol of the same server varies from then to now according to time?

This will make the server harder to be identified.
