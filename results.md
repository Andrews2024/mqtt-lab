## Send message
* 1000 ms delay: Messages get received one at a time
* 100 ms delay: In MQTT explorer, it looks like it receives messages in delayed bunches of 3 or 40 or so
* 10 ms delay: Messages get received in bunches of 30 or so
* 1 ms delay: Messages get received in bunches of 40 or so
## Send long message
* 1000 ms delay: Messages get received one at a time
* 100 ms delay: In MQTT explorer, it looks like it receives messages in delayed bunches of 3
* 10 ms delay: Messages get received in bunches of 30 or so
* 1 ms delay: Messages get received in bunches of 40 or so

## 11 ESP32s: 100 ms per message
* Messages received quickly in bunches of 3 for each board
* No issues with ESPs disconnecting