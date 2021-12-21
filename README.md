# p4wnsolo-global-keylogger
Hardware keylogger design &amp; Python script to exfiltrate globally 

## Concept

* Use Raspberry Pi Zero and a GSM add-on/HAT to build a keylogger into a physical Keyboard
* USB dongle such as the iUniker USB dongle provides hardware HID functionality in the Raspberry Pi
    * This means RPi can receive keypresses from a Keyboard - then pass the keypresses on to the next device (the "target" device)
* [GSM USB add-on](https://www.amazon.com/SIM800C-Wireless-Quad-Band-Communication-Transmission/dp/B087Z6F953/) or [Waveshare GSM HAT](https://www.amazon.com/Raspberry-Bluetooth-SIM800C-Supports-Compatible/dp/B07PRMY2ZP/) gives us the ability to connect to cell networks in most countries in the world
