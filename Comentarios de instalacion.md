En este documento almacenare todo comentario respecto a la habilitación de los ESP32 Huzzah para los diferentes proyectos. Tanto ideas como paginas web interesantes seran agregados.

Para iniciar, se recomienda leer la pagina oficial de adafruit respecto al equipo, esta es:
https://learn.adafruit.com/adafruit-huzzah32-esp32-feather

Comentarios importantes respecto al hardware:

The ESP32 runs on 3.3V power and logic, and unless otherwise specified, GPIO pins are not 5V safe!
Note that the I2C pins do not have pullup resistors already! 
33 - This is GPIO #33 and also an analog input A9. It can also be used to connect a 32 KHz crystal.
32 - This is GPIO #32 and also an analog input A7. It can also be used to connect a 32 KHz crystal.

Lo importante parte aca:
https://learn.adafruit.com/adafruit-huzzah32-esp32-feather/using-with-arduino-ide
Que corresponde a como habilitar el Arduino IDE para poder programar el ESP32 HUZZAH. Lo principal es que te recomiendan que uses el tutorial de la gente de Espressif, que puedes encontrar en https://github.com/espressif/arduino-esp32#using-through-arduino-ide.




