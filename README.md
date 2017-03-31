# USB Encoding PASS

Consiste en un dispositivo USB que contiene claves de acceso para uso cotidiano.


## Caracterisiticas

La Implementacion ésta creada por un attiny85, donde se almacenaran las claves, un par led rojo/verde que indicará si el dispositivo está bloqueado o desbloqueado. El dispositivo cuenta con un encoder de 2 direcciones y un boton, que tendrá diferentes funciones.
Si está bloqueado, el enconder se usará para desbloquearlo utilizandolo como una caja fuerte, girando hacia la izquierda y derecha una determinada cantidad de veces y presionando el boton.
Si está desbloqueado se podra usar para navegar por las diferentes contraseñas, se ira mostrando (escribiendo como un teclado) en la pantalla el nombre de la clave. cuando se presione el boton se escribirá el nombre de usuario, una tabulacion y por ultimo escribirá la contraseña. No escribirá el ENTER. Si se deja presionado durante 1 segundo el boton, el dispositivo se bloquea y el led rojo se enciende.
