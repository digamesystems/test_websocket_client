# test_websocket_client
Attempts to make a connection to a websocket server. Listens for data and displays on the serial monitor / plotter.

Uses the WebSockets library by Markus Sattler
https://github.com/Links2004/arduinoWebSockets

(It's available through the Arduino Library Manager)

Edit the network credentials in network.h to match your setup. 

Note: To do anything, the device you are connecting to must be acting as a WebSocket server, ready to accept connections. Current version uses port 81. 


