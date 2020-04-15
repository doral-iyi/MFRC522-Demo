# Getting Started
For more information about MFRC522 please refer to the [library](https://github.com/miguelbalboa/rfid).

## Pin Layout
For all other Arduinos other than ESP8266 (NodeMCU), refer to the library. For NodeMCU ( [Fritzing file](Fritzing/RFID & NodeMCU.fzz) also available):

	SDA  -> SS_PIN  -> D2
	SCK  -> D5
	MOSI -> D7
	MISO -> D6
	IRQ  -> -------
	GND  -> GND
	RST  -> RST_PIN -> D3
