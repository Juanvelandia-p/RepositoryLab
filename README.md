Mi primer Proyecto
Este es un tutorial de como crear un Proyecto en maven,ponerlo en un repositorio de git, subirlo a un repositorio remote en GitHub
y hacienda que ignore ciertos archivos
Creando un Proyecto (Maven)
•	Abra un Shell del sistema operativo:
![Descripción de la imagen](resources/1.png)

•	Ubíquese en el directorio donde almacenará sus proyectos: 
    ![alt text](resources/2.png)
•	Cree el proyecto Maven: mvn archetype:generate -DgroupId="edu.escuelaing.arsw.ASE.app" -DartifactId="mi-primera-app" -DarchetypeArtifactId="maven-archetype-quickstart" -DinteractiveMode=false:
    ![alt text](resources/3.png)

 
•	Ejecutar el comando cd mi-primera-app:  
![alt text](resources/image.png)

•	Codigo fuente app.java: 
![alt text](resources/image1.png)

•	Pom.xml: 
![alt text](resuorces/image2.png)
•	Construccion del proyecto con mvn package:
 ![alt text](resuorces/image3.png)
•	Ejecución del proyecto: 
 ![alt text](resources/image4.png)


GIT:
-Version de Git:
 ![alt text](resources/git1.png)
•	Configure su identidad y su editor por defecto:
![alt text](resources/git2.png) 
•	Revise su configuración:
 ![alt text](resources/git3.png)
•	Crear un repositorio:
![alt text](resources/git4.png)
•	Agregar archivos al control de versiones de su repositorio: 
![alt text](resources/git5.png)
•	Confirmar los cambios en GIT y crear una nueva versión (commit):  
![alt text](resources/git6.png)
•	Trabajando con repositorios remotos (remotes):
![alt text](resources/git7.png)
![alt text](resources/git8.png)
![alt text](resources/git9.png)

•	Agregar más archivos a su proyecto de Git y su repositorio remoto:
![alt text](resources/git10.png)
![alt text](resources/git11.png)
![alt text](resources/git12.png)
•	Ignorando algunos archivos: 
 ![alt text](resources/git13.png)
 ![alt text](resources/git14.png)
 ![alt text](resources/git15.png)
 

Ahora Vamos a ver un resumen rapido de la creacion del proyecto y subirlo a git hub:

![alt text](resources/newRepo1.png)
![alt text](resources/newRepo2.png)
![alt text](resources/newRepo3.png)
![alt text](resources/newRepo4.png)
![alt text](resources/NewRepo5.png)