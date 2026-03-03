# Sergio Ramos - Snake Rubic

En el proyecto hemos llevado la experiencia del Cubo de Rubik a un nuevo nivel al fusionarlo con el clásico juego **Snake**. Este juego ha sido reinterpretado en un entorno bidimensional donde **cada segmento del snake es un Cubo de Rubik ordenado o a la espera de ser ordenado**. La esencia del juego radica en la resolución constante de estos cubos mientras el snake se mueve por el espacio, devorando **frutas** que son representadas por cubos desordenados adicionales en una posición random del espacio de juego.

## ✨ Representación de snake y las frutas

- **Cabeza del Snake:** La cabeza del snake es un Cubo de Rubik inicialmente ordenado. Este cubo actúa como la entidad principal que guía el movimiento del snake.
- **Cola del Snake:** Cada vez que el snake consume una fruta, un nuevo Cubo de Rubik desordenado se une a la cola del snake. Esta cola representa la historia de las frutas consumidas.
- **Frutas**: Las frutas son cubos de Rubik desordenados dispersos en el espacio tridimensional. Al ser consumidas, se adjuntan a la cola del snake, y su resolución es parte del desafío continuo.

## 📱 **Dinámica del juego**

- **Movimiento del Snake:** El snake se desplaza por el espacio tridimensional siguiendo un patrón predefinido. A medida que avanza, la cabeza del snake resuelve su propio estado, manteniéndose siempre ordenada.
- **Consumo de Frutas:** Cuando la cabeza del snake entra en contacto con una fruta, esta se adjunta a la cola. La resolución de la fruta se inicia, y el juego continúa mientras el snake busca la siguiente fruta.


## 🏗️ Estructura del Proyecto

```
SnakeRubik/
├── Project_108_Snake_Ubuntu/
│   ├── CSolver/src/
│   │   ├── rubik-cube-solver.hpp              #Solver Rubik
│   │   ├── rubik_cube_3basic_solver.cpp       #Solver 3 basic
│   │   └── ....
│   ├── main.cpp
│   ├── rubikCube.h      
│   ├── shapes.h      
│   ├── snake.h 
│   ├── temp_script.py
│   └── .....
├── Project_108_Windows_Snake/
│   ├── CSolver/
│   │   ├── rubik-cube-solver.hpp            
│   │   ├── rubik_cube_3basic_solver.cpp    
│   │   └── ....
│   ├── CMakeList.txt  
│   ├── main.cpp       
│   ├── rubikCube.h      
│   ├── shapes.h      
│   ├── snake.h         
│   └── ....  
├── Project_Ubuntu_Solver/
└── Project_Windows_Solver/Project_108s/      

```

## 🚀 Primeros Pasos

### Requisitos Previos

- openGl
- glad

## 📧 Contacto

- **Email:** slrv.ramosv@gmail.com
- **LinkedIn:** [javiercastillodev](https://www.linkedin.com/in/sergio-leandro-ramos-villena-45b0bb270/)
- **Teléfono:** +51 3932416666

---

**Hecho con ❤️ por Sergio Ramos y Luigi Cabrera | 2023**
