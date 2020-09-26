# SALTO ProAccess Space NGINX Reverse Proxy
NGINX Reverse Proxy configuration for SALTO ProAccess Space, with fully functioning PPD and Card Reader/Writer thanks to an additional WebSocket proxy. This assumes that you install SALTO ProAccess Space using the default ports (8100-8102).

You will need to generate your own SSL Certificates for your desired hostname, and then copy them to your NGINX SSL Store. I've left the default path in the config file for ease of use.

Replace "[YOUR-HOSTNAME]" with your desired FQDN/Hostname, and replace "[YOUR-CONTROLLER-IP]" with the IP of your SALTO ProAccess Space Controller.
