# Control-de-actuadores-mediante-lenguaje-de-señas

Este proyecto implementa un sistema de control de actuadores basado en el reconocimiento de gestos y lenguaje de señas utilizando visión artificial. Desarrollado para facilitar la interacción entre personas y dispositivos, el sistema convierte los gestos manuales en comandos de control, permitiendo el manejo de dispositivos de manera más accesible y natural.


Tecnologías utilizadas

OpenCV : Captura de vídeo en tiempo real y procesamiento de imágenes.
MediaPipe : Detección de poses de las manos y extracción de puntos clave para reconocimiento de gestos.
ESP32 : Comunicación serial para el control de actuadores.
NumPy : Procesamiento de datos y cálculos necesarios para la detección de gestos.

Funcionalidades

El sistema detecta gestos de la mano y los interpreta para realizar diversas acciones en actuadores como:

Control de la velocidad de un motor mediante PWM.
Encendido y apagado de una barra de LED.
Control direccional de un servomotor (movimiento hacia la derecha e izquierda).
