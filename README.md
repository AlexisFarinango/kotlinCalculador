# Programa de Cálculo de Áreas

## Descripción
Este programa, desarrollado en Kotlin, permite calcular el área de figuras geométricas simples mediante un menú interactivo. Las figuras soportadas son:

1. **Cuadrado**  
2. **Círculo**  
3. **Triángulo**

El usuario selecciona una opción del menú, ingresa los valores requeridos (como lado, radio, base o altura) y obtiene el área calculada. También puede salir del programa seleccionando la opción correspondiente.

---

## Requisitos
- Tener instalado el compilador de Kotlin.
- Opcional: Un entorno de desarrollo como IntelliJ IDEA para mayor facilidad de ejecución.

---

## Instrucciones de Uso

1. **Ejecución del Código**
   - Copia el código en un archivo llamado `calculo.kt`.
   - Compila y ejecuta el archivo desde la terminal con los siguientes comandos:
     ```bash
     kotlinc calculo.kt -include-runtime -d calculo.jar
     java -jar calculo.jar
     ```

2. **Uso del Menú**
   - Al ejecutar el programa, aparecerá un menú con las opciones disponibles.
   - Selecciona la figura que deseas calcular ingresando el número correspondiente (1, 2, 3 o 4).
   - Ingresa los valores solicitados según la figura seleccionada:
     - Para el cuadrado: ingresa el lado.
     - Para el círculo: ingresa el radio.
     - Para el triángulo: ingresa la base y la altura.
   - El programa mostrará el resultado del cálculo.

3. **Salir del Programa**
   - Para salir, selecciona la opción `4`.

