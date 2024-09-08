# Buscaminas Automatizado

Este proyecto implementa un solucionador automático para el juego de Buscaminas utilizando procesamiento de imágenes y análisis de riesgo.

## Requisitos

Para ejecutar este proyecto, necesitarás Python 3.7 o superior y las siguientes bibliotecas:

- opencv-python
- numpy
- easyocr
- pyautogui

Puedes instalar estas dependencias utilizando pip:

pip install opencv-python numpy easyocr pyautogui

## Instalación

1. Clona este repositorio:
   
   `git clone https://github.com/aikerary/mineSweeperSolverAI.git`

2. Instala las dependencias:
   
   pip install -r requirements.txt

# 

## Estructura del Código

El código principal está contenido en buscaminas_solver.py y consta de las siguientes partes principales:

1. screenshot_gameboard(): Captura la región de la pantalla donde se encuentra el juego.

2. process_board_cells(): Procesa cada celda del tablero para determinar su estado.

3. process_game_board(): Coordina el proceso de captura y análisis del tablero completo.

4. get_best_cell(): Implementa la lógica para determinar la mejor celda para jugar.

5. solve_mine_sweeper(): Función principal que ejecuta el bucle de juego.

## Personalización

Puedes ajustar las siguientes variables en el código para adaptarlo a tu configuración:

- SCREEN_WIDTH, SCREEN_HEIGHT: Dimensiones de tu pantalla.
- GAME_REGION: Coordenadas de la región donde se encuentra el juego de Buscaminas.
- BOARD_SIZE: Tamaño del tablero de Buscaminas (por defecto 9x9).

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue para discutir cambios mayores antes de hacer un pull request.

## Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo LICENSE para más detalles.
