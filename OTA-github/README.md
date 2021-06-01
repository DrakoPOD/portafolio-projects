# Actualización OTA a un repositorio privado de GitHub
Una actualización OTA (Over the Air - Por el aire) es cuando se le carga un firmware a un microcontrolador mediante conexión Wi-Fi en vez de la usual comunicación serial.

Por defecto, las librerías de OTA del ESP8266 y el ESP32, no adminten firmware cifrados o con "login", debe estar en formato RAW.
## Usos
Podría darse la situación de que tienes un dispositivo IoT, está ubicado en un lugar distante o difícil de acceder, lo cual dificulta su actualización, una actualización sería la mejor alternativa. 

Y es aquí donde está el problema, podría darse el caso que un dispositivo que maneja información sensible o no quieres que tu programa esté al dominio público.

Puedes tener un repositorio privado en GitHub, que también funciona como host gratuito para tus actualizaciones.