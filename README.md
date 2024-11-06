# Unidad2PersonajeNavide-o
Evidencias de la Unidad, videos de las actividades realizadas, capturas de los examenes del curso de python y el avance del proyecto

## Ejercicio Practico Integral
https://drive.google.com/file/d/1jXwqmK4ITC5yddx58-1aJiMXpOgx_DAA/view?usp=sharing

11. Alarma de Seguridad para Zona Restringida
Componentes: HC-SR04, buzzer, LED RGB, OLED
Descripcion: Si alguien cruza la zona restringida, el buzzer emite una alarma, 
el LED RGB parpadea en rojo, y la distancia del intruso se muestra en la OLED

## Ejercicios en Clase
https://drive.google.com/drive/folders/10wt11mgyVxfgfTNA8foS2NPJdw6Lk_1y?usp=sharing

## Avance del proyecto navideño



## Capturas de Evaluaciones de Curso de Python
https://drive.google.com/drive/folders/1alyp6rHc-4xUoBU-qg4_MdE_AOLxC6DZ?usp=sharing


En este proyecto, utilizando conceptos aprendidos en el curso de Python, se implementan funciones y clases que controlan las acciones del personaje, el alcalde de El Extraño Mundo de Jack, en un robot basado en ESP32. Se utilizan clases para organizar el código de manera modular, como BrazoRobot, MotorDePasos, y RobotPrincipal, que permiten controlar los movimientos del brazo, la cabeza y la simulación de parpadeo y guiños, al igual que en Python donde se emplean clases y funciones para estructurar la lógica. A través de condicionales y bucles, el robot realiza acciones como bailar, moviendo sus brazos y cabeza, y reproduciendo una melodía con un buzzer, lo que refleja el uso de estructuras de control en Python. El manejo de eventos se implementa al capturar la presión de un botón, lo que inicia la secuencia de movimientos y sonidos, similar al uso de entradas de usuario en Python. Además, se emplea el concepto de temporización con delay(), equivalente a time.sleep() en Python, para controlar la velocidad de las animaciones y asegurar la sincronización de los movimientos y sonidos, creando una experiencia interactiva y dinámica.

## Coevaluacion
Lo que hizo bien:
Estructura del código: El uso de clases y funciones para modularizar el proyecto es adecuado, lo que hace que el código sea más organizado y fácil de entender. La implementación de las funciones de movimiento y animación (bailar, parpadear, guiñar) es clara y eficiente.
Manejo de entradas: El uso del botón para activar las secuencias es correcto y eficiente, lo que permite una interacción clara con el usuario.
Sincronización de acciones: Las animaciones y sonidos están bien sincronizados, lo que ayuda a crear una experiencia dinámica y fluida.

Áreas de mejora:
Comentarios en el código: Se recomienda añadir más comentarios explicativos en el código para facilitar la comprensión, especialmente para aquellos que no están familiarizados con el proyecto. Explicar el propósito de cada función y el rol de las variables importantes ayudaría a mejorar la legibilidad.
Optimización de temporización: El uso de delay() para las animaciones y sonidos puede causar que otras partes del código se bloqueen. Una mejora sería utilizar funciones como millis() para gestionar las temporizaciones de manera no bloqueante.
Revisión del control de hardware: Aunque el código controla correctamente los servos y el motor de pasos, sería ideal verificar que el hardware utilizado (servos, LEDs, etc.) tenga suficiente alimentación para evitar fallos o comportamientos inesperados.

Aspectos técnicos y de calidad a resaltar:
Uso correcto de la programación orientada a objetos: La implementación de clases para gestionar los diferentes componentes del robot (brazos, cabeza, ojos) refleja un buen manejo de la programación orientada a objetos.
Funcionalidad robusta: El proyecto funciona correctamente, y todas las animaciones se realizan como se espera.

