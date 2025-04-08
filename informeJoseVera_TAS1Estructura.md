# Practica servidor web
## 1. Titulo
"Comandos de linux (creación y manipulación de archivos en linux)"
## 2. Tiempo de duración
45 minutos aproximadamente para desarrollar la práctica.

## 3. Fundamentos:
Linux es un sistema operativo basado en línea de comandos que permite interactuar directamente con el sistema mediante instrucciones llamadas comandos. Entre los más básicos están **pwd** para ver la ruta actual, **ls** para listar archivos, y **cd** para moverse entre carpetas. Para crear y gestionar archivos se usan comandos como **touch**, **mkdir**, **cp**, **mv** y **rm**, mientras que para ver el contenido de archivos están **cat**, **head**, **tail**, **more** y **less**. También es posible gestionar permisos con **chmod**, usuarios con **whoami** y ejecutar tareas como administrador con **sudo**. Estos comandos son esenciales para realizar operaciones básicas y tener control sobre el sistema sin necesidad de una interfaz gráfica.

## 4. Conocimientos previos.
Para realizar esta practica el estudiante necesita tener claro los siguientes temas:
- Comandos linux.

## 5. Objetivos a alcanzar
- Crear una estructura de carpetas.
- Manipulación de archivos.
- Redirección y concatenación.
- Eliminación de archivos y carpetas.

## 6. Equipo necesario:
- Computador con sistema operativo Windows/Linux/Mac.

## 7. Material de apoyo.
- Documentacion sobre comandos en Linux.
- Video tutorial sobre comandos Linux.
  
## 8. Procedimiento
### Paso 1: Crear una estructura de carpetas.
- En tu directorio de trabajo, crea una carpeta llamada proyecto_comandos.
- Dentro de proyecto_comandos, crea tres subcarpetas: documentos, imagenes y scripts.

<img src="imágenes/img1.png" alt="Paso1" width="800"/>

### Paso 2: Manipulación de archivos.
- Dentro de la carpeta documentos, crea un archivo de texto llamado notas.txt.
- Agrega al menos tres líneas de texto en notas.txt utilizando un editor de texto en la terminal (nano, vim) o con redireccionamiento (echo).
- Copia el archivo notas.txt a la carpeta scripts y cambia su nombre a backup_notas.txt.
- Mueve el archivo backup_notas.txt a la carpeta imágenes.

<img src="imágenes/img2.png" alt="Paso2" width="800">
<img src="imágenes/img3.png" alt="Paso2" width="800">
<img src="imágenes/img4.png" alt="Paso2" width="800">
<img src="imágenes/img5.png" alt="Paso2" width="800">

### Paso 3: Redirección y concatenación.
- Crea un archivo llamado resumen.txt en documentos.
- Redirecciona el contenido de notas.txt a resumen.txt.
- Añade una nueva línea de texto a resumen.txt sin sobrescribir su contenido.

<img src="imágenes/img6.png" alt="Paso3" width="800">
<img src="imágenes/img7.png" alt="Paso3" width="800">
<img src="imágenes/img8.png" alt="Paso3" width="800">

### Paso 4: Eliminación de archivos y carpetas.
- Elimina el archivo backup_notas.txt de la carpeta imágenes.
- Elimina la carpeta imágenes (solo si está vacía).

<img src="imágenes/img9.png" alt="Paso4" width="800">
<img src="imágenes/img10.png" alt="Paso4" width="800">

### Paso 5: Entrega.
- Vuelca el contenido del comando history a un archivo llamado tarea-s1-nombre_apellido.txt utilizando tuberías.
- Sustituye "nombre_apellido" por tu nombre y apellido correspondiente.

<img src="imágenes/img11.png" alt="Paso5" width="800">

## 9. Resultados esperados:
    
Efectivamente de los 5 pasos de la practica, todos se han cumplido y se pueden verificar con las capturas de pantalla ya seleccionadas.

## 10. Bibliografía
    
- Install WSL | Microsoft Learn. (n.d.). Retrieved April 4, 2025, from https://learn.microsoft.com/en-us/windows/wsl/install
- ¿Qué es Linux y para qué sirve? - Definición. (n.d.). Retrieved April 6, 2025, from https://www.geeknetic.es/Linux/que-es-y-para-que-sirve