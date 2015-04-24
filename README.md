#Contenido en una Ventana Emergente con Drupal

> Actualizado al 25-04-2015
>La versión del módulo Colorbox Module es la 7.x-3.5

Para ver la página del vídeo haz [clic aquí](http://drupalalsur.org/videos/mostrar-contenido-en-una-ventana-emergente-con-drupal)

##Instalación

1. Descarga este repositorio.
2. Crea una base de datos con el nombre que quieras.
3. Luego selecciona dicha base he importa la que se encuentra en este directorio. La misma se llama *base_de_datos.sql*
4. Edita el archivo *settings.php* el cual se encuentra en *sites/default/*
y edita las siguientes líneas:

		$databases = array (
		  'default' => 
		  array (
	    'default' => 
	    array (
	      'database' => 'vid_node120',
	      'username' => 'root',
	      'password' => 'root',
	      'host' => 'localhost',
	      'port' => '',
	      'driver' => 'mysql',
	      'prefix' => '',
	   	 ),
		 ),
		);

Remplaza 'database', 'username' y 'password' por tus valores.

Ahora guarda los cambios y ya puedes ingresar al sitio desde el navegador.

###Importante para que funcione

Yo en mi sitio utilice la url http://server/videos/node120, tu tienes que modicar esto por tus valores.
