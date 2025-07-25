
# Bitacora

Santiago Bustamante

ID:000415198



## contenido:
en este repositorio se encuentra varios archivos en los cuales se muestra y se explica lo que hemos visto en clase, utilizando el desarrollador de git bash y todos los comandos necesarios para usar la consola, usar los comandos y crear repositorios tanto locales como repositorios en la nube con github.

















 ## Documentos
| Enlace | Descripcion |
---------|--------------
[Uso de la consola](./docs/uso_consola.md)| en el archivo se describen los principales comandos usados en git bash
[Repositorio local](./docs/repositorio_local.md)| en este archivo se describe como se crea un repositorio local y los comandos necesarios
[Repositorio remoto](./docs/repositorio_remoto.md)|aqui se encuentra descrito como crear un repositorio remoto y luego sincronizarlo con el local para luego hacer commits y hacer git push

## como clonar el repositorio?

para esto primero hay que conseguir el link del repositorio que se busca clonar, cuando tenemos el link, en este caso seria "https://github.com/hacUPB/git-and-github-Sbustamantega.git" y luego hay que dirigirse a la consola de git y usar el comando git clone seguido del link del repositorio, con esto ya quedará el repositorio copiado localmente, ahora cada que se hagan cambios puede hacerse git push para sincronizarse o git pull para recuperar lo que hay en la nube.



## capturas de pantalla

creacion de los archivos en docs:
<br>
![texto](<imagenes/Captura de pantalla 2025-07-24 174209.jpg>)

realizando commit del archivo readme:
<br>
![alt text](<imagenes/Captura de pantalla 2025-07-24 183626.png>)
<br>
<br>
creacion del archivo .gitignore:
<br>
![alt text](<imagenes/image.png>)
<br>
<br>
haciendo push para sincronizar el repositorio remoto:
<br>
![alt text](<imagenes/image-1.png>)
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>





































[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/SoiS0_7u)
# Unidad No. 1 - Git y GitHub
## Información del estudiante  
Nombre del estudiante:  
Id.:  
---
# Evaluación

### **Descripción de la Actividad:**

El objetivo de esta actividad es crear y estructurar un proyecto de programación utilizando Git y GitHub. Aunque el código fuente será un componente mínimo, el enfoque estará en la organización del proyecto y la documentación de lo aprendido sobre los siguientes temas:

1. Uso de la consola para navegar entre directorios, crear directorios y archivos.
2. Creación de repositorios locales usando comandos de Git.
3. Creación de repositorio remoto en GitHub y sincronización con el repositorio local.

**Instrucciones:**

1. **Crea la estructura del proyecto:**
    - Clona el repositorio de la evaluación.
    - De ahora en adelante seguirás trabajando en tu repositorio local.
    - Ubícate en el directorio raíz llamado `prog-Eval_Template`.
    - Dentro de este directorio, crea las siguientes carpetas:
        - `src`: para almacenar el código fuente.
        - `docs`: para guardar la documentación.
        - `images`: para imágenes relacionadas con el proyecto.
2. **Código fuente:**
    - En la carpeta `src`, crea un script en Python (ej. script.py) con el siguiente código:
        
        ```python
        # Programa para calcular el promedio de una lista de números
        
        print("Bienvenido al programa de cálculo de promedios.")
        print("Ingresa números uno por uno. Escribe 'salir' para terminar.")
        
        # Lista para almacenar los números
        numeros = []
        
        while True:
            entrada = input("Ingresa un número (o escribe 'salir'): ")
            
            if entrada.lower() == 'salir':
                break  # Salir del bucle si el usuario escribe 'salir'
            
            try:
                # Convertir la entrada a número
                numero = float(entrada)
                numeros.append(numero)
            except ValueError:
                print("Por favor, ingresa un número válido.")
                continue
        
        # Verificar si hay números en la lista antes de calcular el promedio
        if len(numeros) > 0:
            promedio = sum(numeros) / len(numeros)
            print(f"El promedio de los números ingresados es: {promedio:.2f}")
        else:
            print("No ingresaste ningún número.")
        
        ```
        
    - Este código es solo un ejemplo básico para incluir un archivo funcional en el proyecto.
3. **Archivo .gitignore:**
    
    Investiga qué es un archivo `.gitignore` y cuál es su función dentro de un proyecto de programación. Crea el archivo `.gitignore` y guárdalo en a tu repositorio. Ahora, según la consulta que hiciste, escribe en él, los nombres de archivos y carpetas que quieres ignorar. Pregunta al profesor en caso de dudas.
    
4. **Documentación:**
    - Dentro de la carpeta `docs`, crea los siguientes archivos de tipo Markdown (.md):
        - `uso_consola.md`: Describe los conceptos aprendidos sobre cómo usar la consola para navegar y crear directorios y archivos. Haz un listado de los principales comandos utilizados en esta unidad.
        - `repositorio_local.md`: Explica cómo crear un repositorio local con comandos de Git.
        - `repositorio_remoto.md`: Detalla el proceso para crear un repositorio remoto en GitHub y sincronizarlo con el repositorio local.
5. **Archivo README.md:**
    - En la raíz del proyecto, encontrarás un archivo `README.md`, es este mismo que estás leyendo. Lo vas a editar y vas a incluir al inicio del archivo la siguiente información:
        - Una breve descripción del contenido de tu repositorio. Recuerda que los archivos README.md están ahí para explicarle a las personas que vean tu repositorio, de qué se trata y qué contiene.
        - Explica cuáles son los pasos necesarios para clonar y ejecutar el proyecto.
        - Crea una tabla de contenido con enlaces a los archivos Markdown de la carpeta `docs`.
6. **Uso de Git:**
    - Realiza commits para cada etapa del desarrollo (creación de carpetas, scripts, archivos Markdown, etc.). **Debes realizar mínimo 10 commits.** Los mensajes que utilices deben ser claros, con buena ortografía y con información relevante sobre el cambio que acabas de realizar.
    - Asegúrate de incluir imágenes con pantallazos de los pasos que realices cuando añadas elementos a tu repositorio y de los comandos de Git que utilices y su resultado.
    - Recuerda que los archivos son de Markdown, por lo tanto, debes utilizar los comandos correctos para que los archivos se puedan visualizar de manera correcta.
7. **Entrega:**
    - Sube los cambios en tu proyecto al repositorio remoto en GitHub.
    - Asegúrate de que toda la documentación esté completa y correctamente estructurada.


[def]: Captura%20de%20pantalla%202025-07-24%20174209.jpg