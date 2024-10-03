# Gramatica para el Robot
## Creditos
- Autor: Alejandro Arango
- Modificado por: Silvia Takahashi
- Modificado por: Juan Pablo Morales.
- Agregadas producciones para manejar globos
- Modificado por Silvia Takahashi
- Modificado por Juan Jose Diaz y Simon Calderon para interpretar nuevas instrucciones y funciones.
- Documentado por Juan Jose Diaz

## Descripción General
El proyecto Robot es una aplicación que simula un robot en un mundo virtual. El robot puede moverse, recoger y colocar objetos, y realizar diversas acciones basadas en comandos definidos por el usuario. La aplicación incluye un intérprete de comandos y una interfaz gráfica para visualizar el estado del robot y su entorno.

## Estructura del Proyecto
El proyecto está organizado en tres paquetes principales:

- uniandes.lym.robot.control: Contiene las clases relacionadas con el control y la interpretación de comandos.
- uniandes.lym.robot.kernel: Incluye las clases que representan la lógica y el estado del mundo del robot.
- uniandes.lym.robot.view: Contiene las clases responsables de la interfaz gráfica y la visualización.

### Clases principales
#### Robot (uniandes.lym.robot.control.Robot)
Esta clase es el núcleo del intérprete de comandos del robot. Está generada a partir del archivo Robot.jj utilizando JavaCC. Algunas de sus responsabilidades incluyen:

- Interpretación de comandos: Procesa las instrucciones ingresadas por el usuario y ejecuta las acciones correspondientes en el mundo del robot.
- Control del mundo: Interactúa con el RobotWorldDec para cambiar el estado del mundo según los comandos ejecutados.
- Manejo de variables y macros: Soporta la definición y uso de variables y macros para crear programas más complejos.
#### RobotWorld y RobotWorldDec (uniandes.lym.robot.kernel)
- RobotWorld: Representa el mundo en el que el robot opera. Mantiene el estado del robot, incluyendo su posición, orientación y los objetos en el mundo.
- RobotWorldDec: Extiende RobotWorld y proporciona implementaciones específicas para las acciones del robot. Es la clase que Robot utiliza para manipular el mundo.
#### Console (uniandes.lym.robot.view.Console)
Proporciona la interfaz de usuario para interactuar con el robot. Algunas de sus funciones son:

- Entrada de comandos: Permite al usuario ingresar comandos para controlar el robot.
- Visualización: Muestra el estado actual del mundo y del robot utilizando las clases Board e Images.
- Salida de mensajes: Presenta mensajes de salida y resultados de la ejecución de comandos mediante la string salida que se pasa al interprete y al robot.jj

## Diagrama
![mermaid-diagram-2024-10-03-232504](https://github.com/user-attachments/assets/057ec0cd-60f8-4807-8ea7-df02c13a35e3)

## Comandos Disponibles
Despúes de haber modificado el robot

### Movimiento:

MOVE(n): Mueve el robot hacia adelante n pasos.
RIGHT(): Gira el robot 90 grados a la derecha.
HOP(n): Salta n posiciones hacia adelante.
GO(x, y): Mueve el robot a la posición (x, y).

### Manipulación de objetos:

PUT(CHIPS, n): Coloca n fichas en la posición actual.
PUT(BALLOONS, n): Coloca n globos en la posición actual.
PICK(CHIPS, n): Recoge n fichas de la posición actual.
PICK(BALLOONS, n): Recoge n globos de la posición actual.
POP(n): Revienta n globos en la posición actual.

### Estructuras de control y macros:

NEW VAR variable = valor;: Declara una nueva variable.
NEW MACRO nombreMacro() { ... }: Define una macro.
IF (condición) THEN { ... } ELSE { ... } FI;: Estructura condicional.
DO (condición) { ... } OD;: Bucle basado en una condición.
REP n TIMES { ... } PER;: Repite un bloque de instrucciones n veces

## Ejemplos de programa
Se proporcionan algunos ejemplos ya que los puestos en el enunciado del curso estan mal hechos.
```
// Definición de variables
NEW VAR steps = 5;
NEW VAR turns = 3;

// Definición de una macro
NEW MACRO square() {
  REP 4 TIMES {
    MOVE(steps);
    RIGHT();
  } PER;
}

// Ejecución del programa
EXEC {
  square();
  PUT(CHIPS, 10);
  MOVE(2);
  PICK(BALLOONS, 1);
}
```
