## EJERCICIO 3 
### ¿Que se vio?
Podemos notar que cuando ponemos el valor en 100 este podemos observar como el Led se apaga y enciende mas rapido pero por otro ladocuando lo ponemos en 500, la velocidad disminuye y el parpadeo del Led es mas lento

## EJERCICIO 5
### Documentacion
- La biblioteca Arduino-Pico es ideal para programar el microcontrolador RP2040, como el Raspberry Pi Pico, con Arduino. 
- El Raspberry Pi Pico es un microcontrolador económico y potente, perfecto para proyectos electrónicos como robots y dispositivos conectados, gracias a su procesador ARM Cortex-M0+ y 2 MB de memoria flash. 
- La página principal de Arduino ofrece productos, herramientas, tutoriales y una comunidad para aprender y compartir ideas.

## EJERCICIO 6
### ¿Cómo se ejecuta este programa?
El codigo hace que se guarde en cada variable un numero cada 1 segundo para que luego se muestre en la pantalla (en el Monitor Serie) 

### Pudiste ver este mensaje: Serial.print("Task1States::WAIT_TIMEOUT\n");. ¿Por qué crees que ocurre esto?
No se puede ver el mensaje en el momento justo por el hecho de que cuando abre el Monitor serie este ya anda contando

### ¿Cuántas veces se ejecuta el código en el case Task1States::INIT?
Una sola vez que es cuando se inicia/ejecuta el codigo, inicializando el Task1 en INIT
Init = Iniciar
