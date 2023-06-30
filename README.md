# app-chat-gui
This is a simple GUI-based chatting application.

(make sure you've installed python 3 and cloned this repository to your computer)

## How to use
1. Change the Host IP address to your local IP (IPv4)
2. Change the Port based on the Server Port number
3. Open terminal
4. Run `server.py`
5. Run `client.py`. Note that only one device should run the server, while the rest of the users should run `client.py` using the same port number as the server
6. Set the username and the profile picture

## Notice
If you're using personal hotspot for connection, the server might be offline. These are the potential reasons: 
1. Firewall or Network Restrictions: There might be firewall settings or network restrictions in place that prevent your client application from establishing a connection to the server.
2. NAT or Router Configuration: If you are both on the same local network (e.g., connected to the same Wi-Fi), the server might be behind a router or using Network Address Translation (NAT).
