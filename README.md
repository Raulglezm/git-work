<center>

# UT1-A1 Documentación y sistema de control de versiones

</center>

***Nombre:*** Raúl González Martín, Alejandro Pérez Martín </br>
***Curso:*** 2º de Ciclo Superior de Desarrollo de Aplicaciones Web.

### ÍNDICE

+ [Introducción](#id1)
+ [Objetivos](#id2)
+ [Material empleado](#id3)
+ [Desarrollo](#id4)
+ [Conclusiones](#id5)


#### ***Introducción***. <a name="id1"></a>

Aquí explicamos brevemente la parte teórica que tiene que ver con la práctica que se va a realizar

#### ***Objetivos***. <a name="id2"></a>

El objetivo de esta práctica es aprender sobre el uso y funcionamiento de git y conseguir mayor soltura a la hora de su uso

#### ***Material empleado***. <a name="id3"></a>

1. Git
2. Github
3. Explorador de archivos
4. Visual Studio
5. Consola de Linux

#### ***Desarrollo***. <a name="id4"></a>

### 1. user1 creará un **repositorio público** llamado **git-work** en su cuenta de GitHub, añadiendo un README.md y una licencia MIT.
#
User1 creará un repositorio público llamado "git-work" en su cuenta de GitHub. Añadirá un archivo README.md para proporcionar información sobre el proyecto y una licencia MIT para establecer los términos de uso.

![ref1]

### 2. user1 clonará el repo y añadirá los ficheros: **index.html**, **bootstrap.min.css** y **cover.css**. Luego subirá los cambios al *upstream*.
#

User1 clonará el repositorio recién creado ("git-work") y añadirá los archivos index.html, bootstrap.min.css, y cover.css. Estos archivos contienen el código y los estilos necesarios para el proyecto. Posteriormente, subirá estos cambios al repositorio remoto (upstream).

![ref2]

![ref3]

### 3. user2 creará un fork de **git-work** desde su cuenta de GitHub.
#

User2 creará un fork del repositorio "git-work" desde su cuenta de GitHub. Esto creará una copia independiente del repositorio en su propia cuenta.

![ref4]

![ref5]

### 4. user2 clonará su fork del repo.
#

User2 creará un fork del repositorio "git-work" desde su cuenta de GitHub. Esto creará una copia independiente del repositorio en su propia cuenta.

![ref6]

![ref7]

### 5. user1 creará una issue con el título "Add custom text for startup contents".
#

User1 creará una issue con el título "Add custom text for startup contents". Esta issue servirá para proponer una mejora o un cambio en el proyecto.

![ref8]

### 6. user2 creará una nueva rama custom-text y modificará el fichero index.html personalizándolo para una supuesta startup.
#

User2 creará una nueva rama llamada "custom-text" y modificará el archivo index.html para personalizarlo según los requisitos de una supuesta startup. Estos cambios se realizarán en la rama "custom-text" para mantenerlos separados de la rama principal.

![ref9]

![ref10]

### 7. user2 enviará un PR a user1.
#

User2 enviará un Pull Request (PR) a User1 para proponer los cambios realizados en la rama "custom-text". Un PR es una solicitud formal para que los cambios sean revisados y fusionados en la rama principal del repositorio.

![ref11]

### 8. user1 probará el PR de user2 en su máquina (copia local) creando previamente un remoto denominado upstream, y realizará ciertos cambios en su copia local que luego deberá subir al propio PR.
#

User1 probará el PR de User2 en su máquina local, creando previamente un remoto denominado "upstream". Durante la revisión, User1 podrá realizar ciertos cambios en su copia local y subirlos al PR para discutirlos con User2. Esta comunicación se llevará a cabo en la página del PR.

![ref12]

![ref13]

### 9. user1 y user2 tendrán una pequeña conversación en la página del PR, donde cada usuario incluirá, al menos, un cambio más.
#

User1 y User2 entablarán una breve conversación en la página del pull request (PR), donde cada uno propondrá y añadirá una modificación adicional.

![ref14]

### 10. user1 finalmente aprobará el PR, cerrará la issue creada (usando una referencia a la misma) y actualizará la rama principal en su copia local.
#

Después de la conversación y los cambios adicionales, User1 aprobará el PR de User2. User1 cerrará la issue creada anteriormente, haciendo referencia a ella en el mensaje de cierre. Además, User1 actualizará la rama principal en su copia local para incluir los cambios aprobados.

![ref15]

### 11. user2 deberá incorporar los cambios de la rama principal de upstream en su propia rama principal.
#

User2 deberá incorporar los cambios de la rama principal de "upstream" en su propia rama principal. Esto asegurará que el trabajo realizado por User2 esté actualizado con los cambios más recientes realizados por otros colaboradores.

![ref16]

### 12. user1 creará una issue con el título "Improve UX with cool colors".
#

Esta issue propondrá una mejora en la experiencia de usuario utilizando colores llamativos.

![ref17]

### 13. user1 cambiará la línea 10 de cover.css a: color: purple;
### 14. user1 hará simplemente un commit local en main → NO HACER git push.
#

User1 cambiará la línea 10 del archivo cover.css a "color: purple;" para aplicar el nuevo color a la interfaz. Este cambio se hará en la rama principal, pero no se subirá al repositorio remoto.

![ref18]

### 15. user2 creará una nueva rama cool-colors y cambiará la línea 10 de cover.css a: color: darkgreen;

Esto modificará el color de la interfaz según los requisitos de la issue creada anteriormente.

![ref20]

### 16. user2 enviará un PR a user1.
#

User2 enviará un PR a User1 para proponer los cambios realizados en la rama "cool-colors".

![ref21]

### 17. user1 probará el PR de user2 (en su copia local). A continuación tratará de mergear el contenido de la rama cool-colors en su rama principal y tendrá que gestionar el conflicto: Dejar el contenido que viene de user2.
#

Tras probar a hacer el merge se ha creado el conflicto, donde tras hacer un rebase se quedan los datos recibidos por el user2

![ref19]

### 18. Después del commit para arreglar el conflicto, user1 modificará la línea 11 de cover.css a: text-shadow: 2px 2px 8px lightgreen;

Tras realizar el commit para resolver el conflicto, User1 modificará la línea 11 del archivo cover.css de la siguiente manera: cambiará "text-shadow" a "text-shadow: 2px 2px 8px lightgreen;".

![ref22]

#### 19. user1 hará un commit especificando en el mensaje de commit el cambio hecho (sombra) y que se cierra la issue creada (usar referencia a la issue). A continuación subirá los cambios a origin/main.
#

User1 hará un commit especificando en el mensaje de commit el cambio hecho (sombra) y que se cierra la issue creada, utilizando una referencia a la issue. A continuación, subirá los cambios a origin/main.

![ref23]

### 20. user1 etiquetará esta versión (en su copia local) como 0.1.0 y después de subir los cambios creará una "release" en GitHub apuntando a esta etiqueta.
#

User1 realizará un commit en el que incluirá un mensaje que indique la modificación realizada (sombra) y que se dará por cerrada la incidencia creada, empleando una referencia a la incidencia. A continuación, enviará los cambios a origin/main.

![ref24]

![ref25]

#
#### ***Conclusiones***.
#
<b>
Durante el desarrollo de esta práctica, hemos tenido la oportunidad de aprender y aplicar conceptos fundamentales relacionados con el uso de Git y GitHub en un entorno de trabajo colaborativo. Algunas de las conclusiones clave que hemos obtenido son las siguientes:
</b>

Git y GitHub como Herramientas Esenciales: Hemos comprendido la importancia de Git como sistema de control de versiones y GitHub como plataforma de colaboración en proyectos de desarrollo de software. Estas herramientas proporcionan un flujo de trabajo sólido para la colaboración entre desarrolladores.

Creación y Configuración de Repositorios: Hemos aprendido cómo crear y configurar repositorios tanto locales como remotos en GitHub. Esto incluye la creación de un repositorio público, el funcionamiento de archivos esenciales como el README.md y la licencia MIT, y la configuración de los flujos de trabajo iniciales.

Trabajo con Ramas: Comprendemos la importancia de trabajar con ramas en Git para mantener el desarrollo aislado y organizado. Hemos creado y gestionado ramas para abordar tareas específicas y desarrollar nuevas características sin afectar a la rama principal.

Gestión de Pull Requests (PR): Hemos aprendido el proceso de enviar y revisar solicitudes de extracción (PR) en GitHub. Esto nos ha permitido colaborar de manera efectiva, realizar revisiones de código y fusionar cambios de manera controlada.

Resolución de Conflictos: Hemos adquirido experiencia en la resolución de conflictos durante la fusión de ramas, un aspecto importante en el trabajo colaborativo. Aprendimos a manejar conflictos de manera eficiente y a tomar decisiones informadas sobre qué cambios mantener.

En general, esta práctica ha fortalecido nuestra comprensión y habilidades en el uso de Git y GitHub como herramientas esenciales para el desarrollo de software colaborativo, aprovechar al máximo las capacidades de control de versiones y colaboración que ofrecen estas herramientas.



[ref1]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.001.png
[ref2]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.002.png
[ref3]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.003.png
[ref4]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.004.png
[ref5]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.005.png
[ref6]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.006.png
[ref7]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.007.png
[ref8]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.008.png
[ref9]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.009.png
[ref10]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.010.png
[ref11]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.011.png
[ref12]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.012.png
[ref13]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.013.png
[ref14]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.014.png
[ref15]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.015.png
[ref16]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.016.png
[ref17]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.017.png
[ref18]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.018.png
[ref19]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.019.png
[ref20]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.020.png
[ref21]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.021.png
[ref22]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.022.png
[ref23]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.023.png
[ref24]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.024.png
[ref25]: img/Aspose.Words.60bda16d-f96d-4aac-8cb8-aca1a3dbafe6.025.png
