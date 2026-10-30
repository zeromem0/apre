# apre

The page that shows what an instrument reads off a wire, big, on a PC or a phone:
the result of its inspector (RS232, TTL, RS485, LIN, CAN, PWM, I2C clock, levels),
the text it reads, the frames it takes apart (LIN, Modbus RTU), and the waveform.

**Open it:** https://zeromem0.github.io/apre/

- On a PC: Chrome or Edge (Web Serial). On Android: Chrome, with a USB-C OTG cable (WebUSB).
- Plug the instrument in, press **Connect** and choose it.
- The instrument speaks *apre protocol 1*: JSON lines over USB serial, described in the page's
  source. The firmware that speaks it (for the FNIRSI DST-210) is not published.

One HTML file, nothing to install, nothing sent anywhere: the page talks only to the
instrument on the USB cable.

MIT licence.
