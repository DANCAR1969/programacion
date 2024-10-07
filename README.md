# Proyecto de Programación en Python

Este proyecto cubre algunos conceptos básicos de programación en Python. Está diseñado para principiantes que desean aprender cómo manejar variables, imprimir datos en la consola y verificar los tipos de datos.

## Contenidos

1. **Uso de la función `print()`**  
   Aprende a mostrar mensajes en la consola utilizando la función `print()`.

2. **Uso de Variables**  
   Descubre cómo crear variables en Python, asignarles valores y combinarlas en cadenas de texto.  
   - **Sintaxis**:  
     ```python
     variable = "valor"
     ```

   - Ejemplo:  
     ```python
     marca = "sony"
     serie = "platino"
     mejorTecnologia = "la mejor " + marca + " " + serie
     print(mejorTecnologia)
     ```

3. **Verificación del tipo de dato de una variable**  
   Aprende a usar la función `type()` para determinar el tipo de una variable.  
   - Ejemplo:  
     ```python
     print(type(mejorTecnologia))  # Verifica que la variable es de tipo cadena (str)
     ```

## Requisitos

- **Python 3.x**  
  Asegúrate de tener instalada una versión de Python 3.x en tu sistema.

- **Jupyter Notebook**  
  Para ejecutar el archivo `.ipynb`, necesitarás Jupyter Notebook. Si no lo tienes instalado, puedes instalarlo con:
  ```bash
  pip install notebook
