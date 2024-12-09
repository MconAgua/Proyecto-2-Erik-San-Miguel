# Proyecto Aventura Pirata

## Descripción

El proyecto **Aventura Pirata** es un juego interactivo en el que el jugador controla a un pirata en busca de un cofre en un tablero de 10x10 celdas. El jugador mueve al pirata de acuerdo con el resultado de un dado lanzado, con el objetivo de llegar al cofre lo más rápido posible. El número de tiradas es contabilizado y se guarda en el almacenamiento local como el récord de tiradas.

## Características

- **Interacción**: El jugador puede introducir su nombre y comenzar el juego.
- **Tablero**: El tablero es una cuadrícula de 10x10 celdas, con un pirata y un cofre.
- **Movimiento**: El pirata se mueve en el tablero en función del número obtenido en el dado.
- **Registro de tiradas**: El número de tiradas es contabilizado y guardado en el almacenamiento local.
- **Diseño Temático**: El juego tiene una temática pirata con colores y diseños acordes.

## Requisitos

- Navegador web moderno (Chrome, Firefox, Edge, Safari).
- La aplicación usa **localStorage** para almacenar y recuperar el récord de tiradas.

## Tecnologías utilizadas

- **HTML**: Estructura del contenido del juego.
- **CSS**: Estilo visual, diseño responsivo y personalización de la interfaz.
- **JavaScript**: Lógica del juego, gestión de los movimientos y manejo de eventos.
- **Imágenes**: PNGs con el pirata, cofre y dado, con un fondo transparente.

## Instalación

1. Clona o descarga el proyecto.
2. Abre el archivo `index.html` en tu navegador.
3. Juega directamente en tu navegador, sin necesidad de un servidor.

## Cómo jugar

1. **Introduce tu nombre** en el campo de texto.
2. Haz clic en **"Jugar"** para empezar el juego.
3. **Tira el dado** haciendo clic en el botón de tirar, lo que generará un número aleatorio.
4. Mueve al pirata en el tablero según el número obtenido en el dado.
5. **Llegar al cofre** y verás el mensaje de victoria con el número de tiradas.

## Casos de Uso

- **Iniciar el Juego**: El jugador ingresa su nombre, el sistema valida el nombre y habilita las opciones de juego.
- **Lanzar el Dado**: El jugador hace clic en el botón de lanzar el dado, y el sistema mueve al pirata en el tablero.
- **Mover al Pirata**: El jugador puede mover al pirata según el número obtenido en el dado, y el sistema actualiza la visualización.
- **Llegar al Cofre**: El jugador gana al llegar al cofre, y el juego registra el número de tiradas.

## Estructura del Proyecto

