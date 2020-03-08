# Bind9 with Webmin

Webmin runs on port 10000

'''

docker run -it -p 67:67 -p 68:68 -p 67:67/udp -p 68:68/udp -p 80:80  -e PASSWORD=YourRootPassword quay.io/spivegin/isc_dhcp_server

docker run -d -p 67:67 -p 68:68 -p 67:67/udp -p 68:68/udp -p 80:80  -e PASSWORD=YourRootPassword quay.io/spivegin/isc_dhcp_server
'''