### DUDAS 1ª ITERACIÓN

### 

##### POWER CONVERTER 24V-->12V

* F1?
* D
* ~~Revisar huellas condensadores~~
* Valor L1
* ~~Huella L1~~





##### ~~CONNECTOR 23-PIN AMPSEAL~~

~~Pin 23:~~

~~a) SPI\_CSI\_EXT~~

~~b) SHIELD\_GND~~





##### ~~POWER CONVERTER 12V--> 5V~~

* ~~Huellas condensadores~~
* ~~Huella L1~~
* ~~Huella L2~~





##### ~~MICRO~~

* ~~Huellas condensadores desacoplo alimentación~~
* ~~Pág. 20 Datasheet --> Power supply scheme~~
* ~~NRST --> Qué hace?~~
* ~~Resistencias en I2C?~~
* ~~Falta algo?~~
* ~~BOOT0????~~





##### ~~OSCILADOR~~

* ~~Función~~
* ~~Modelo????~~
* ~~¿Qué significa Crystal?~~





##### CAN TRANSCIEVER

* ¿Qué es lo de "EXTRA"?
* No es el modelo del WO, revisar modelo





##### IMU

* Salidas?





##### ~~USB~~

* ~~USB\_BVUS --> ¿Protección? ¿De donde viene?~~



\-----------------------------------------------------

### FEEDBACK 1ª ITERACIÓN

* ~~Del stm vi que te faltaba el circuito para boot0.~~
* ~~Para i2c te hacen falta pull-ups de 4.7k en sda y scl~~
* Limitación 3V3 ADC
* ~~Del usb te falta la parte de la alimentación, vusb que viene del ordenador que conectas.~~
* ~~Diodo en serie USB~~



\-----------------------------------------------------

### DUDAS 2ª ITERACIÓN

##### 

##### POWER CONVERTER 24V-->12V

* F1 huella y valor
* D1
* Valor L1





##### MICRO

* VBAT
* Circuito alimentación
* Heartbeat necesario?
* Olvido algo?
* OSCILADOR --> "Cristal: C19/C20 de 25 pF, y el WO dice 12–18 pF." (by Mr. Claude)





##### IMU

* Revisar





##### ADC

* Divisor resistivo es correcto?



##### USB

* No se resalta la misma red en D+ y D- con el micro, ¿cómo arreglarlo?











