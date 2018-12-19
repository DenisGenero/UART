# UART
Driver and app

En este proyecto se encuentra tanto el driver de comunicación serie, que incluye funcionalidades para trabajar con UART por USB, RS-232 y RS485, asi como dos aplicaciones ejemplo que muestran como se utiliza el driver.
Para hacer funcionar las aplicaciones se necesitan 2 computadoras y 2 EDU-CIAA, una programada con la aplicación UARTMaster (la que envia datos) y la otra con la aplicació UARTSlave (la que recibe datos).
En la primera aplicación se interactua con el usuario mediante consola (UART por USB), y mediante un menu se puede optar por enviar datos por RS-232 o RS-485. Las datos que se envían son interpretados por la otra EDU-CIAA, y se manifiesta encendiendo o apagando sus leds.
