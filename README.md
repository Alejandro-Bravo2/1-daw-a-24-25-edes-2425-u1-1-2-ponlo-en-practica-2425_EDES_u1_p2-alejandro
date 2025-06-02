# Práctica 2: Introducción al desarrollo. Ponlo en práctica. 

Apoyate en los siguientes recursos para realizar la práctica:

[Descripción de la práctica](https://revilofe.github.io/section3/u01/practica/EDES-U1.-Practica011/)


---

# Título de la Actividad

## Identificación de la Actividad
- **ID de la Actividad:** P1.2 - Ponlo en practica
- **Módulo:** EDES
- **Unidad de Trabajo:** P1.2 - Ponlo en practica
- **Fecha de Creación:** 2/05/2025
- **Fecha de Entrega:** 2/05/2025
- **Alumno(s):** 
  - **Nombre y Apellidos:** Alejandro Bravo Calderón
  - **Correo electrónico:** abracal@g.educaand.es
  - **Iniciales del Alumno/Grupo:** abc

## Descripción de la Actividad
[Descripción detallada de la actividad, objetivos, y contexto necesario para comprenderla. Explicar en qué consiste la actividad y qué se espera que el alumno desarrolle o implemente.]

La actividad consiste en comprender el funcionamiento de los distintos lenguajes y como interactuan con el equipo en función del tipo que sea. Por ejemplo los interpretados y compilados. 

Por lo que para desarrollar esta actividad se han realizado 3 códigos en los siguientes lenguajes de programación:
- Java
- Python
- C
Cada uno de los códigos vinculados a estos lenguajes lo que realiza es una muestra de información por terminal.

## Instrucciones de Compilación y Ejecución
1. **Requisitos Previos:**
   - python
   - java
   - jvm 23.02
   - gcc

2. **Pasos para Compilar el Código:**

   Para compilarlo en c:
   ```bash
   gcc main.c -o main
   ```
   Para compilarlo en java:
   ```bash
   javac ImprimirInformacion.java
   ```

3. **Pasos para Ejecutar el Código:**

   Para ejecutarlo en python
   ```bash
   python3 main.py
   ```

   Para ejecutarlo en java
   ```bash
   java ImprimirInformacion
   ```

   Para ejecutarlo en c
   ```bash
   ./main
   ```


## Desarrollo de la Actividad
### Descripción del Desarrollo

La actividad se ha realizando utilizando gcc para la compilación del código en el lenguaje **C**, para la compilación en java he usado **javac**. Para python al ser interpretado no he tenido que compilar ni realizar una generación de código intermedio, con python lo único que he tenido que he tenido que hacer es ejecutarlo ya que python al ser interpretado se irá compilando línea a línea mientras se ejecuta.

### Código Fuente

Código usado para imprimir la información en **C**
https://github.com/Alejandro-Bravo2/1-daw-a-24-25-edes-2425-u1-1-2-ponlo-en-practica-2425_EDES_u1_p2-alejandro/blob/856c7b12976907722fe9ad1c8ce94d5ced054716/src/main.c#L1-L6

Código usado para imprimir la información en **java**
https://github.com/Alejandro-Bravo2/1-daw-a-24-25-edes-2425-u1-1-2-ponlo-en-practica-2425_EDES_u1_p2-alejandro/blob/856c7b12976907722fe9ad1c8ce94d5ced054716/src/ImprimirInformacion.java#L1-L5

Código usado para imprimir la información en **python**
https://github.com/Alejandro-Bravo2/1-daw-a-24-25-edes-2425-u1-1-2-ponlo-en-practica-2425_EDES_u1_p2-alejandro/blob/856c7b12976907722fe9ad1c8ce94d5ced054716/src/main.py#L1-L4




## Documentación Adicional
- **Manual de Usuario:** [Enlace a la documentación del usuario, si existe]
- **Autorización de Permisos:** Verificar que el profesor tenga permisos de lectura en el repositorio para revisar el código.

## Conclusiones


He aprendido a como compilar en java y c además de haber aprendido sobre el código intermedio y código objeto. También he aprendido los distintos niveles que existen en los lenguajes de programación. He aprendido a la importancía de las máquinas virtuales para la portabilidad del código entre sistemas operativos.


## Referencias y Fuentes

https://revilofe.github.io/section3/u01/teoria/EDES-U1.5.-Lenguajes/?h=gcc#211-lenguajes-compilados

https://stackoverflow.com/questions/24819206/using-gcc-to-compile-c-code

https://stackoverflow.com/questions/2279451/how-to-compile-a-java-file-in-java

### Notas Adicionales:
1. **Nombres de Archivos y Repositorios:**
   - Asegúrate de que el nombre del archivo o repositorio siga la estructura definida: `XXX-idActividad-Iniciales`.
2. **Permisos:**
   - Verifica que el profesor tenga los permisos necesarios para acceder al repositorio o documento.
3. **Formato:**
   - Si se entrega en formato PDF o Google Docs, asegúrate de cumplir con el mínimo y máximo de folios establecidos.
4. **Compilación y Ejecución:**
   - Detalla claramente cómo compilar y ejecutar el código, incluyendo las instrucciones en el archivo `README.md`.
