# errors_shtml
Páginas de Error Personalizadas. Pra que uses en tu Página Web

Saludos cordiales,

La presente es para poderles hacer llegar
Páginas de Errores personalizadas para su página Web.

Pasos de instalación:

--------LOCAL-WAMPP-XAMPP-HOSTING-------

1.- Descargar o Clonar este repositorio y colocar todos lo shtml dentro de tu raíz
junto con el archivo .htacceess.

2.- Probar si funcionan haciendo llamado a algún archivo inexistente dentro de tu directorio por la URL
ejemplo: #http://localhost(:port - si usan distinto a 80)/holamundo.conf

--------CLUSTER-DIGITAL-OCEAN------

1.- Descargar o Clonar este repositorio y colocar todos lo shtml dentro de tu raíz
junto con el archivo .htacceess.

2.- Ubicar el archivo #apache2.conf dentro de /etc/apache2/

3.- Abrir y reemplazar:

<Directory /var/www/>
	Options Indexes FollowSymLinks
	
	AllowOverride none
	
	Require all granted
	
</Directory>

POR

<Directory /var/www/>
	Options Indexes FollowSymLinks
	
	AllowOverride All
	
	Require all granted
	
</Directory>

4.- Crear un archivo llamado #default dentro de /etc/apache2/sits-avalible/
E ingresar lo siguiente.

<Directory /var/www/html/>
	Options Indexes FollowSymLinks Multiviews
	
	AllowOverride All
	
	Order allow,deny
	
	allow from all
	
</Directory>
