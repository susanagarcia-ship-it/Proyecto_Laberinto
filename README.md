#  DUNGEON EXPLORER – Professional Edition
Juego estilo *maze–survival* desarrollado en **Python con Tkinter**, que combina generación de laberintos, enemigos con IA, trampas, cofres y distintos modos de juego.

Este proyecto fue creado con fines educativos e incluye tres modos de juego, un sistema dinámico de niveles, pathfinding inteligente (BFS), detección de colisiones y una interfaz completamente gráfica.

---

##  Características Principales

###  **1. Laberinto generado proceduralmente**
Se utiliza un algoritmo DFS para generar un laberinto aleatorio cada vez que inicia un nivel.  
Ninguna partida es igual a otra.

###  **2. Tres modos de juego**
- **Modo Aventura**  
  Avanza por el laberinto y llega al tesoro esquivando trampas.

- **Modo Jefe**  
  Un enemigo grande te persigue usando pathfinding.  
  ¡Escapa mientras buscas la salida!

- **Modo Carrera**  
  Compites contra un rival fantasma — el primero en llegar al cofre gana.

###  **3. Pathfinding Inteligente (BFS)**
Los enemigos pueden:
- Seguir al jugador (modo jefe)
- Calcular la ruta perfecta hacia el objetivo (modo carrera)

### **4. Interfaz gráfica**
- Colores temáticos
- Barra de vida animada
- Redibujado a 30 FPS
- Botón para volver al menú
- Pantalla de victoria/derrota

###  **5. Sistema de objetos**
Dentro del laberinto se generan:
- **Trampas** (daño)
- **Cofres** (curación)

###  **6. Sistema de niveles**
Cada nivel aumenta:
- Tamaño del laberinto  
- Cantidad de trampas  
- Cantidad de cofres  
- Dificultad del jefe o rival  

---

## Tecnologías Utilizadas

| Tecnología | Uso |
|-----------|-----|
| **Python 3** | Lenguaje principal |
| **Tkinter** | Interfaz gráfica |
| **threading** | Sonidos y procesos paralelos |
| **collections.deque** | BFS rápido y eficiente |
| **math & random** | Generación procedural |
| **winsound (Windows)** | Efectos de sonido |

---

##  Estructura del Proyecto# Proyecto_Laberinto
