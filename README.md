Para Crecer Location
==================

## Descripción

<p align="justify">
	El presente sistema pretende mostrar la ubicación en tiempo real de los usuarios.
</p>

## Técnico
<p align="justify">
	Para realizar el siguiente sistema tendremos dos opciones de stack según mi experiencia personal:
</p>

<b>Relacional</b>

<ol>
	<li>
		<p align="justify">
			PHP
		</p>
	</li>
	<li>
		<p align="justify">
			SQL
		</p>
	</li>
	<li>
		<p align="justify">
			AJAX
		</p>
</ol>

<b>No Relacional</b>

<ol>
	<li>
		<p align="justify">
			Firebase
		</p>
	</li>
		</li>
		<li>
		<p align="justify">
			JQuery
		</p>
	</li>
</ol>

## Desarrollo

<p align="juatify">
	Para este caso tomaremos el <i>Stack</i> <b>No Relacional</b> 
</p>

* Firebase

<p align="justify">
	Entramos a <a href="https://firebase.google.com">Firebase</a> con nuestra cuenta de Google.
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img1.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img2.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img3.png" width="680" height="369">
</p>

<p align="justify">
	A continuación nos pregunta en que plataforma por el momento no usaremos esta opción pero son nuestras credenciales que posteriormente asociaremos al proyecto.
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img4.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img5.png" width="680" height="369">
</p>

<p align="justify">
	Modificamos los permisos de la <b>Base Datos</b> por el momento y por razones prácticas lo menejaremos público aun que nos marque en rojo.
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img6.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img7.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img8.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img9.png" width="680" height="369">
</p>

<b>Agregar Datos</b>

<p align="justify">
	Agregamos un <i>Usuario</i> y a continuación una <i>latitud</i> y una <i>longitud</i> para ese usuario. Agregamos la <i>latitud</i> y la <i>longitud</i> a ese usuario pulsando el boton <i>más</i>, en este caso la ubicación de Puebla. Así agregaremos más ciudades.
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img10.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img11.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img12.png" width="680" height="369">
</p>

<p align="justify">
	Para agregar otro <i>Usuario</i> pulsamos en el signo más. Las coordenadas las podemos sacar directamente de <a href="https://www.google.com.mx/maps">Google Maps</a> buscando una dirección y finjandonos en la URL. 
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img13.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img14.png" width="680" height="369">
</p>

<b>Creamos la estructura HTML</b>

<p align="justify">
	Para incrustar el mapa nos basaremos en la documentación oficial de <a href="https://developers.google.com">Google Maps API</a>
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img15.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img16.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img17.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img18.png" width="680" height="369">
</p>

<p align="justify">
	Y seguiremos las instrucciones para incrustar un mapa. El primer paso es crear la estructura <i>HTML</i>. 
</p>

<p align="justify">
	Crearemos 3 archivos básicos: <i>index.html, estilos.css, app.js</i>. Así como instalaremos el <i>FRAMEWORK JQUERY</i> a través de <i>NPM</i> en la consola de <i>GIT SHELL</i> para hacer la programación de <i>JAVASCRIPT</i> más simple.
</p>

## Fuente

<p align="justify">
	<a href="https://developers.google.com/maps/documentation/javascript/adding-a-google-map">Google Maps API</a>.
</p>
