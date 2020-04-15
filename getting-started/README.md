# Getting Started
For more information about MFRC522 please refer to the [library](https://github.com/miguelbalboa/rfid).

## Pin Layout
For all other Arduinos other than ESP8266 (NodeMCU), refer to the library. For NodeMCU ([Fritzing file](Fritzing/RFID-and-NodeMCU.fzz) also available):

	SDA  -> SS_PIN  -> D2
	SCK  -> D5
	MOSI -> D7
	MISO -> D6
	IRQ  -> -------
	GND  -> GND
	RST  -> RST_PIN -> D3

## Dump Info
The first sketch you should study is the ['DumpInfo'](Sketches/DumpInfo.ino) sketch. This program reads an card and 'dumps' all the information that is stored on it.
This includes the following:

 * UID (Unique Identifier)
 * SAK (Select Acknowledge)
 * Type
 * Data Blocks

B/c of the large output required to output the data blocks, a baud rate 115200 is required.
