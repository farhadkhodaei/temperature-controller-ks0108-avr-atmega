# temperature-controller-ks0108-avr-atmega
A cooling system controller with a good UI. Note that the file "KS0108 GLCD - final controller - additional files.zip" should be extracted by WinRAR or WinZip with the option 'Extract Here' to have the remaining files and the codevision AVR project. The used microcontroller is ATmega16A and the circuit can be obtained by noting to the configuration of the project and the statements. In the hardware, two push buttons are also required, that are active low. The push buttons are connected to PINC.0 and PINC.1 (PINC.0 to increase and PINC.1 to decrease the desired temperature). The '+' or '-' icon is highlighted by pressing these buttons. Also the control signal is put out from PORTC.4 that is active high and turns the cooler relay on. The temperature is measured by an LM35 module and ADC3 pin of the microcontroller.





