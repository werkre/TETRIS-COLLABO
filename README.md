IDEAS TETRIS PROYECTO URSS
0.  MECANISMOS DE LÓGICA
    0.1. Reaccionar a las teclas pulsadas por el usuarios -> Desplazamiento de las piezas.
    0.2. Giros de las piezas -> Cambio de forma.
    0.3. Control de eventos.
        0.3.1. Teclas pulsadas.
        0.3.1. Movimiento de las piezas.
        0.3.2. Reconocer cuando una pieza ha "tocado fondo"
               0.3.2.1. Refrescar display.
               0.3.2.2. Otorgar puntos (Si procede)
               0.3.2.3. Generar señal para insertar nueva pieza.
        0.3.3. Reconocimiento de las condiciones para obtener puntos -> Filas llena.
        0.3.4. Incremento de la puntuación.
        0.3.5. Mostrar siguiente pieza.
        0.3.6. Temporizador -> Regula el avance.
1.  Generación aleatoria de piezas de distinta forma que se posicionan sobre un mapa coordenado.
2.  Para lograrlo hace falta el uso de varios hilos a nivel de núcleo, en un esquema "Unos a Unos".
3.  También hace falta el uso de funciones auxiliares.
    3.1. La gestión de la aleatoriedad.
    3.2  QUIZÁS La inserción de piezas.
4. OBJETOS A USAR.
   4.1. Display -> Posible matriz de 1s y 0s.
   4.2. Piezas -> Matrices auxiliares de 3 x 3. Distinción entre casillas útiles y las que no en función de la orientación de la pieza actual.
5. HILOS
   5.1. Hilo que gestiona el display -> Necesidad de caracter atómico. Refrescos instáneos pero dependientes de un temporizador.
   5.2. Hilo del main -> Concretar esto último.
6. PROXIMAMENTE DIAGRAMA DE FLUJOS
