# Simulador de la Ley de Snell
## Descripción
Este proyecto es un simulador gráfico interactivo de la Ley de Snell, que permite visualizar cómo se refracta y refleja un rayo de luz al pasar por diferentes interfaces de materiales. El usuario puede ajustar el número de interfaces, los materiales, y el ángulo de incidencia. El simulador está desarrollado en Python utilizando una interfaz gráfica moderna.
El código principal se encuentra en el archivo  SimuladorLeyDeSnell.py.
Requisitos Previos

## Sistema Operativo: Compatible con Windows, macOS o Linux.
Python: Versión 3.6 o superior. Puedes descargar Python desde ![Python Org](https://www.python.org/)

## Dependencias
El simulador requiere las siguientes bibliotecas:

**tkinter:** Biblioteca estándar de Python para interfaces gráficas. Viene incluida en la mayoría de las instalaciones de Python (no requiere instalación adicional).
**customtkinter:**  Extensión de tkinter para widgets modernos con soporte para temas claro/oscuro. Instálala usando pip:
    textpip install customtkinter
**math:**  Biblioteca estándar de Python para funciones matemáticas (seno, coseno, etc.). Viene incluida en Python (no requiere instalación adicional).

Asegúrate de ejecutar el comando de instalación en un entorno virtual si lo prefieres, para evitar conflictos con otras dependencias.
Instalación

Clona o descarga el repositorio (o copia el código en un archivo llamado Simulador.py).
Instala la dependencia principal:
    <pre>textpip install customtkinter</pre>

## Cómo Ejecutar

Abre una terminal o línea de comandos en el directorio donde se encuentra el archivo Simulador.py.
Ejecuta el script con Python:
    <pre>textpython SimuladorLeyDeSnell.py</pre>
(Si usas Python 3 explícitamente, puedes usar python3 Simulador.py en algunos sistemas).

La ventana del simulador se abrirá automáticamente. Puedes interactuar con el panel de control para cambiar el número de interfaces, el ángulo de incidencia y los materiales de cada capa. El canvas se actualizará en tiempo real.
Notas

Si encuentras errores relacionados con tkinter, verifica que Python esté instalado correctamente y que tkinter esté disponible (en algunos sistemas Linux, puede requerir sudo apt install python3-tk).
El simulador soporta modo claro y oscuro; usa el botón en la parte superior para alternar.
No se requieren permisos especiales ni acceso a internet para ejecutar el código.

Si tienes problemas o sugerencias, ¡abre un issue en el repositorio!
