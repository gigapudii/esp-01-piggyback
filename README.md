# ESP8266 USB programmer piggyback board
A small board that piggybacks on an ESP-01 module, and makes it easier for you to program the ESP8266 via a [USB-to-Serial board](https://i.imgur.com/NQs8db6.jpg).

![piggyboard](https://i.imgur.com/TKHBqHe.jpg)

## WHY
According to the datasheet of ESP8266, the GPIO-0 pin should be grounded for the microcontroller to be in programming mode. However, these cheap USB-to-Serial adaptors from China don't offer a way to make that connection.

If you want to use these adaptors, you would have to solder the connection yourself. This doesn't look very nice and it is not the only problem. After soldering the pins together, you wouldn't be able to use the ESP with the adaptor to run your software because the microcontroller will always be stuck in programming mode.

## HOW
My solution to this is this little board, that will sit between the ESP-01 and the USB-to-Serial board. Using the jumper, one can switch between programming and normal mode easily without soldering any pins together.

## Components
* [ESP-01 piggyback PCB](http://oshparklink)
* 3-pin male header
* Pin jumper

## Media
* [Demo video](https://youtu.be/fUgga0gxCAw)

