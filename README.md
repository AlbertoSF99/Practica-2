# Práctica 2 - Creación de un entorno de ejecución con Azure ML

## Innovaccion Virtual (VII Edición) #IAWizards

### Semana 1 - Sesión 3
En esta práctica se hizo uso del recurso de Azure Machine Learning para crear un entorno de ejecución.

----------------------------------------------------------

#### Requerimientos
- Cuenta de Azure con suscripción.

----------------------------------------------------------

#### Pasos a seguir

1. Ingresar a ‘portal.azure.com’ y buscamos ‘Azure Machine Learning’ para crear uno nuevo. Rellenamos los campos necesarios como suscripción, grupo de recursos, nombre del área de trabajo y región. Una vez hecho esto, le damos en ‘Revisar y crear’ y en ‘Crear’.

![P2I1](https://github.com/AlbertoSF99/Practica-2/blob/main/Images/Sesi%C3%B3n%203%20-%20P2%2001.PNG)

2. Ingresar a la página [ml.azure.com/home](ml.azure.com/home). En esta página aparecerá el área de trabajo que previamente creamos en el portal de Azure. Ingresamos a ‘Ir a área de trabajo’. Dentro de este entorno, buscaremos el apartado de ‘Proceso’ (o ‘Compute’ en inglés) en la pestaña izquierda de la pantalla.

![P2I2](https://github.com/AlbertoSF99/Practica-2/blob/main/Images/Sesi%C3%B3n%203%20-%20P2%2002.PNG)

![P2I3](https://github.com/AlbertoSF99/Practica-2/blob/main/Images/Sesi%C3%B3n%203%20-%20P2%2003.PNG)

3. Dentro de esta pestaña de Proceso, en ‘Instancias de Procesos’ le damos a ‘Nuevo’. Completamos los campos que nos solicitan, y en tamaño de la máquina virtual seleccionamos DS11_v2 como recomendación.

![P2I4](https://github.com/AlbertoSF99/Practica-2/blob/main/Images/Sesi%C3%B3n%203%20-%20P2%2004.PNG)

![P2I5](https://github.com/AlbertoSF99/Practica-2/blob/main/Images/Sesi%C3%B3n%203%20-%20P2%2005.PNG)

4. Ahora, en la pestaña de ‘Notebooks’, dentro de este sitio creamos un archivo, el cual cambiamos el nombre a nuestro gusto pero dejando la extensión `.ipynb` intacta.

![P2I6](https://github.com/AlbertoSF99/Practica-2/blob/main/Images/Sesi%C3%B3n%203%20-%20P2%2006.PNG)

![P2I7](https://github.com/AlbertoSF99/Practica-2/blob/main/Images/Sesi%C3%B3n%203%20-%20P2%2007.PNG)

5. Habiendo creado el archivo, se abrirá un entorno de trabajo para trabajar en lenguaje Python, por lo que escribiremos el código: `print(“Hola Mundo!”)`. Lo ejecutamos y veremos que el programa funciona correctamente.

![P2I8](https://github.com/AlbertoSF99/Practica-2/blob/main/Images/Sesi%C3%B3n%203%20-%20P2%2008.PNG)

***Información adicional:*** No se nos cobrará por crear el grupo de recursos para el Azure Machine Learning, pero para crear la Instancia de Proceso si nos cobrará (Cobra por hora, por lo que es importante detenerlo cuando ya no se use o necesite). Se puede editar el programa en VS Code al estar dentro de la Notebook, en el programa que se ha escrito, en la parte superior hay una opción para realizar dicha acción.
