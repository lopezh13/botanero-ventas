# botanero-ventas
 Sistema para un restaurante, local donde vendan comida, botanas, etc.

 Para iniciar el sistema se puede de dos maneras que son las siguentes:
 
#1 
(para esta demostracion estamos usando Xampp)
- Debemos estar en la ruta C:\xampp\htdocs
- Dentro de htdocs crear la carpeta: botanero-ventas
- Descarga los archivos del repositorio y descrompime el zip y extraer las carpetas api y dist
- Dentro de botanero-ventas copiar y pegar la carpeta: api y dist

EN EL NAVEGADOR PODEMOS ACCEDER ATRAVEZ DE LA RUTA -> http://localhost/botanero-ventas/dist

#2 (demostracion usando xampp - la segunda opcion te permite interactuar con el codigo fuente, para que puedas realizar los ajustes de acuerdo a tu necesidad)
- Descarga los archvios del repositorio y descromprime el zip
- Guardalos en la ruta -> C:\xampp\htdocs\botanero-ventas
- Puedes usar el editor de tu preferencia en mi caso uso Visual Studio Code
- Dentro de la terminal de VSC ejecuta el comando << npm install >> esto crea las dependecias necesarias para el proyecto
- Una vez ejecutado el comando anterior se ejecuta el comando << npm run dev >> y esperamos que se inicie
- Al ejecutar el comando anterior nos dara la siguente ruta -> http://localhost:8080 la pegamos en el navegador y nos saldra el inicio de sesión o mejor dicho la configuracion de nuestro local o negocios ya que esto nos permitira iniciar la base de datos 

  POSIBLE ERROR AL INICAR
  - A la hora de iniciar el sistema se podria presentar que la pantalla se queda congelada cargando esto se soluciona creando la carpeta << mesa_ocupadas >> esta se dedebe crear dentro de la carpeta api

![image](https://github.com/lopezh13/botanero-ventas/assets/108281309/37428487-0b5b-4e6b-b487-f63c5a1b23cb)
