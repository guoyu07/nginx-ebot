nginx vHost-config: eBot
==========

This is only the vHost config for eBot with HTTPS.

nginx is being used as a reverse-Proxy and listening on Port 12365.

It forwards the requests to 127.0.0.1:12360

Usage
-------
change the following information in eBot.conf:

 - vHost Servername
 -   SSL certificate location
