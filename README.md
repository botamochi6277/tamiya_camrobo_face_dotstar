# TAMIYA CAMROBO FACE DOTSTAR

![FRONT](https://user-images.githubusercontent.com/14128408/89731623-6fd4a800-da83-11ea-9f16-9c0c96dd00fc.jpeg)

![BACK](https://user-images.githubusercontent.com/14128408/89731617-6b0ff400-da83-11ea-9e61-22950e78e3c5.jpeg)

An extension board for the face of [TAMIYA Cam-Program Robot](https://www.tamiya.com/english/products/70227/index.htm). 
This board has RGB LEDs and an audio amp.
This board is designed for Raspberry Pi.

- LED: SK9822, compatible chip of APA102. It is a RGB LED including a controller communicate with SPI. 
- Audio AMP: [AKIZUKI AMP Module](http://akizukidenshi.com/catalog/g/gK-08217/) using PAM8012. 
- Speaker: Small speaker you can buy from [AKIZUKI](http://akizukidenshi.com/catalog/g/gP-10128/). You need replace it because the speaker works in 3V (I failed to select.)

The board in v1.0 (photo version) have no wire between `IN-` and `GND`. I added wire for the connection. 