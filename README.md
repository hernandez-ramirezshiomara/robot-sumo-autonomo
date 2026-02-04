Robot Sumo Autónomo

Descripción
Robot sumo autónomo desarrollado como proyecto personal en bachillerato de mecatrónica.
El objetivo del robot es detectar al oponente, mantenerse dentro del dohyo y ejecutar
acciones de ataque y evasión de manera automática.

Funcionamiento general
El robot opera mediante una lógica de control basada en estados:
- Búsqueda del oponente
- Ataque directo al detectar presencia
- Corrección de trayectoria
- Retroceso al detectar el borde del área de combate

Sensores y actuadores
- Sensores infrarrojos / ultrasónicos para detección del oponente
- Sensores de línea para detección del borde
- Motores DC con tracción diferencial
- Puente H para control de motores

Control
El control del movimiento se realiza mediante programación en C++.
Se implementa lógica de control para el movimiento autónomo del robot,
incluyendo correcciones de trayectoria según la lectura de sensores.

Tecnologías utilizadas
- C++
- Microcontrolador (Arduino)
- Electrónica básica
- Control de motores DC

Resultados
El robot es capaz de operar de manera autónoma, detectar al oponente
y evitar salir del área de combate, aunque la fuerza mecánica es limitada.

Aprendizajes
- Programación estructurada en C++
- Integración de sensores y actuadores
- Lógica de control en sistemas autónomos
- Resolución de problemas en sistemas reales

Posibles mejoras
- Implementar control PID para mayor estabilidad
- Optimizar el diseño mecánico
- Migrar a ROS para simulación y control avanzado

Multimedia
[SUMO.zip](https://github.com/user-attachments/files/25059801/SUMO.zip)

