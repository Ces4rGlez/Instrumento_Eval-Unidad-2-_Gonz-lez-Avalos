# Instrumento de Evaluación | Unidad 2 | González Avalos César Fernando |   GDS0641
___
## Ejercicio integral de la unidad, usando ESP32 y otros sensores de IoT para lograr un funcionamiento completo.

### Ejercicio --> Termostato de calor con Buzzer y LED RGB
Componentes | DHT11 , buzzer , LED RGB , OLED

Descripción | Si la temperatura supera un límite, el LED RGB cambia a rojo y el buzzer emite una alerta, la pantalla OLED muestra la temperatura en tiempo real.

#### Código y Video Explicativo

| **Plataforma**    | **Link** |
|-----------------|-------------|
| Drive         | [https://drive.google.com/drive/folders/1jqqpngP7WORwfYxnFWY5K7z3tBnHWsSA?usp=drive_link](https://drive.google.com/drive/folders/1jqqpngP7WORwfYxnFWY5K7z3tBnHWsSA?usp=drive_link)     |

---

##  Ejercicios en clase con el uso de sensores, actuadores y ESP32

### Carpeta con los Videos y Códigos hechos en Python y Arduino:

| **Plataforma**                           | **Enlace**                                              |
|-------------------------------------------|---------------------------------------------------------|
| Drive | [https://drive.google.com/drive/folders/1tkMeL1jVSmXtmRuzuwRrCXK6cWnYtdYL?usp=sharing](https://drive.google.com/drive/folders/1tkMeL1jVSmXtmRuzuwRrCXK6cWnYtdYL?usp=sharing) |

### Descripción funcionamiento códigos -->
| **Código**                           | **Descripción**                                              |
|-------------------------------------------|---------------------------------------------------------|
| Buzzer.py | Este código permite controlar un buzzer conectado a un microcontrolador, activándolo y desactivándolo de manera repetida. Utiliza un ciclo continuo para alternar entre encender y apagar el buzzer a intervalos regulares, asegurando que se apague correctamente si el programa se interrumpe. En términos generales, su función es generar un sonido intermitente utilizando el buzzer. |
|Distancia.py| Este código utiliza un sensor de distancia para medir la distancia a un objeto y controlar LEDs en función de esas mediciones. Dependiendo de la distancia medida por el sensor, se enciende un LED diferente. Si la distancia es corta, se enciende un LED; si es media, se enciende otro, y si es larga, se enciende un tercero. |
|MatrizMax.py|Este código controla una matriz de LEDs para mostrar un mensaje desplazándose de derecha a izquierda. Utiliza un microcontrolador para enviar los datos a la matriz a través de una comunicación SPI. El mensaje "Feliz navidad" se mueve continuamente en la pantalla, y el brillo de la matriz se ajusta.|
|MotorAPasos.py| Este código controla un motor paso a paso, permitiendo que gire tanto en sentido horario como antihorario.|
|PotAndMatriz.py|Este código lee el valor de un potenciómetro y muestra el porcentaje de su valor en una matriz de LEDs. El porcentaje se desplaza de derecha a izquierda en la pantalla, actualizándose continuamente.|
|SeieLAndSens.py|Este código utiliza un sensor HC-SR04 para medir la distancia y muestra el valor de la distancia en una matriz de LEDs NeoPixel. |
|Jos.py|Este código usa un joystick y un botón para controlar un LED RGB en un ESP32. El joystick mueve el LED a diferentes colores según su dirección|
|Serv.py|Este código lee la temperatura de un sensor y mueve un servo motor dependiendo de la temperatura medida. Si la temperatura es alta, el servo se mueve a una posición, y si es baja, se mantiene en otra posición.|
|Bot.py|Este código controla un LED utilizando dos botones: uno para encenderlo y otro para apagarlo.|
---

## Avance en el proyecto navideño

#### Código y Video Explicativo

| **Plataforma**    | **Link** |
|-----------------|-------------|
| Drive         | [https://drive.google.com/drive/folders/1jNeVY24-PO4ZBcQgQBLnmxBUevEXWL3v?usp=drive_link](https://drive.google.com/drive/folders/1jNeVY24-PO4ZBcQgQBLnmxBUevEXWL3v?usp=drive_link)     | 

**Avances Logrados :**  Los avances del proyecto "Duende Navideño" incluyen el movimiento, la reproducción de sonido y el sistema de luces. El duende ya cuenta con luces LED que cambian de color y parpadean según el ambiente, un servo que le permite realizar movimientos festivos como agitar los brazos, y un módulo de sonido que reproduce melodías navideñas al detectar movimiento en el entorno. Sin embargo, aún falta por diseñar la figura del duende, comprar algunos componentes (pantalla OLED, tira de leds y una Matriz de leds) y desarrollar la parte de comunicación, que permitirá que el duende interactúe con otros dispositivos o se controle de forma remota, completando así la experiencia festiva y funcional del proyecto.

---

## Capturas de Pantalla del curso de Python en NetAcad

#### Capturas de Pantalla -->

| **Plataforma**    | **Link** |
|-----------------|-------------|
| Drive         | [https://drive.google.com/drive/folders/1w06sQ31uivaNNicYh7fzine36beOhunK?usp=sharing](https://drive.google.com/drive/folders/1w06sQ31uivaNNicYh7fzine36beOhunK?usp=sharing)     |  

#### Aplicación de lo aprendido en el curso de Python -->

Aprender Python es útil porque es un lenguaje fácil de entender y muy flexible, lo que permite aplicarlo en muchísimos campos, como desarrollo de aplicaciones, análisis de datos, inteligencia artificial, y automatización. Al ser uno de los lenguajes más populares, conocer Python abre muchas oportunidades, tanto en lo laboral como en lo académico, y ayuda a entender mejor cómo funcionan las tecnologías que usamos todos los días. 

Los conocimientos adquiridos en Python pueden ser útiles para crear un programa de control para el "Duende Navideño" en la placa ESP32, utilizando MicroPython. Este programa permitiría gestionar todos los elementos del duende, desde el sistema de luces hasta el módulo de sonido y el motor de movimiento, en función de las condiciones ambientales y los eventos programados. Con Python, podríamos implementar una lógica flexible y fácil de modificar que haga que el duende reaccione automáticamente a su entorno, creando una experiencia interactiva y dinámica para los usuario. Por ejemplo, podríamos emplear un bucle while para ejecutar continuamente las funciones de encendido de luces y reproducción de sonido, verificando en cada iteración si se cumplen ciertas condiciones ambientales, como la temperatura o el nivel de luz.

---

## Coevaluación 

#### Nombre de mi compañero --> Chavero Martínez Noé
#### Calificación --> 9/10
**Descripción -->** Mi compañero fue excelente al armar rápidamente los circuitos que haciamos en la ESP32 y siempre estuvo dispuesto a colaborar con los materiales necesarios, lo cual ayudó mucho al avance del proyecto. Además, cumplió con su parte de la evaluación sin problemas, lo que hizo que el trabajo en equipo fuera mucho más fluido. Destaco también su capacidad para escuchar y proponer ideas: cada vez que tuve problemas con el código, él siempre me daba sugerencias útiles para corregir los errores.

En cuanto a áreas de mejora, aunque montaba el circuito muy rápido, en algunas ocasiones conectaba mal ciertos cables o componentes, lo cual requería ajustes posteriores. También, algunas veces el punteado no era el adecuado, y al grabar los videos se ponía un poco nervioso, lo que afectaba el resultado final.

En general, trabajamos muy bien juntos y considero que es un muy buen compañero. Su disposición para colaborar y su habilidad para resolver problemas técnicos son aspectos que valoro mucho.
