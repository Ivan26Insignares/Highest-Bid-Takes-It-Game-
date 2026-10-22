# El Que Más Puja

Juego de subastas en el navegador. Hay 29 temas en 12 categorías, todos disponibles siempre. Cada jugador empieza con 20 monedas y debe terminar con 5 elementos.

- **Misma pantalla:** dos jugadores en un dispositivo.
- **En línea:** quien crea la sala comparte un código de 4 letras. Las jugadas viajan por un servidor MQTT público y gratuito (EMQX, con HiveMQ y Mosquitto de respaldo) usando [MQTT.js](https://github.com/mqttjs/MQTT.js) (MIT), incluido en `mqtt.min.js`.

Es un sitio estático: `index.html` se publica tal cual con GitHub Pages.
