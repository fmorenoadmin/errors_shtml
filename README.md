<p align="center">
	<img src="https://archivos.sistemasongoku.com/fmoreno_7X7KyN5phPGy/imagenes/ico490x458.png" height="320px" title="Icono">
</p>

[![Canal de GitHub](https://img.shields.io/badge/Canal-GitHub-black)](https://github.com/fmorenoadmin)
[![Sígueme en Twitter](https://img.shields.io/twitter/follow/sendgrid.svg?style=social&label=Sígueme)](https://twitter.com/FrankMartinMor1)
[![Sígueme en Facebook](https://img.shields.io/badge/Sígueme-@FrankMartinMA-blue)](https://facebook.com/FrankMartinMA)
[![Sígueme en Facebook](https://img.shields.io/badge/Sígueme-@frankmartinmoreno-ff69b4)](https://instagram.com/frankmartinmoreno)
[![Escríbeme en Facebook](https://img.shields.io/badge/Escríbeme-@FrankMartinMA-blue)](https://m.me/FrankMartinMA)
[![Escríbeme en WhatsApp](https://img.shields.io/badge/Escríbeme-WhathApp-green)](https://wa.me/51924741703)
[![Mi Web](https://img.shields.io/badge/Mi_Página-Web-blueviolet)](https://frankmorenoalburqueque.com)

## errors_shtml
<p>
	Páginas de Error Personalizadas. Para que uses en tu Página Web
	<br>
	Saludos cordiales,
	<br>
	La presente es para poderles hacer llegar
	Páginas de Errores personalizadas para su página Web.
</p>

### Pasos de instalación:

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

4.- Crear un archivo llamado #default dentro de /etc/apache2/sites-avalible/
E ingresar lo siguiente.

<Directory /var/www/html/>

	Options Indexes FollowSymLinks Multiviews	
	AllowOverride All	
	Order allow,deny	
	allow from all
	
</Directory>

<p align="center">
	<label>Moreno Alburqueque Frank Martin</label><br>
	<label>WebMaster - Programador Web PHP</label><br>
	<label><a href="mailto:admin@fmorenoadmin.com.pe">admin@fmorenoadmin.com.pe</a></label><br>
	<label><a href="https://frankmorenoalburqueque.com" target="_blank">https://frankmorenoalburqueque.com</a></label><br>
	<label><a href="tel:924741703">+51 924 741 703</a></label><br>
	<img src="https://archivos.sistemasongoku.com/fmoreno_7X7KyN5phPGy/imagenes/logo480x240.png" width="auto" title="Logo">
</p>
