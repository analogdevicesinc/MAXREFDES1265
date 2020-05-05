# MAXREFDES1265
Numeric keypad interface using the MAX7360 and a MAX3265PICO with a spare I2C interface.

<b>Description</b>: 
MAX7360 is a key switch controller with an I2C interface. When integrated with a microcontroller it can be used to control a numeric keypad.
 
<b>Operation</b>: 
This code was developed in a such a way that initially all the pertinent registers of the MAX7360 gets initialized. Then, based upon the key press, the data gets displayed on a Serial terminal.

<b>Getting Started</b>: 
Click the "Clone or Download" button and click "Download ZIP" above (from the main GITHUB repo page). After the download finishes, unzip the file to a directory of your choosing. Program the FTHR board with the MAX7360_rev2.MAX32625PICO.bin file found in the Firmware directory. The complete procedure is mentioned in the design documents found on the MAXREFDES1265's page on Maxim's website.

<b>Firmware Source</b>:
Although the firmware binary can be found in this repository, the firmware source is available for download at this mbed repository: https://os.mbed.com/teams/MaximIntegrated/code/MAXREFDES1265/.
