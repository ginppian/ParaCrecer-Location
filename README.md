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

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img24.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img25.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img20.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img21.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img22.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img23.png" width="680" height="369">
</p>

<p align="justify">
	Nos apoyaremos del código que viene en la documentación de Google.
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img26.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img27.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img28.png" width="680" height="369">
</p>

<p align="justify">
	El último paso que nos pide <i>Google Maps</i> es crear una <i>CLAVE</i>. Para hacer eso nos dirigimos a <i>GOOGLE CONSOLE API</i> obtenemos la llave, copiamos el código de <i>JAVASCRIPT ASINCRONO</i> (el cual permitirá al resto del navegador procesar el resto de la página mientras se carga el <i>API</i>) y le incrustamos nuestra <i>CLAVE</i>.
</p>

<p align="justify">
	Después de éso abriremos <i>INDEX.HTML</i> en un navegador y tendremos que visualizar nuestro <i>MAPA</i>.
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img29.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img30.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img31.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img32.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img33.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img34.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img35.png" width="680" height="369">
</p>

<p align="center">
	<img src="https://github.com/ginppian/ParaCrecer-Location/blob/master/img/img36.png" width="680" height="369">
</p>

<p align="justify">
	En <i>APP.JS</i> nuestra función <i>INITMAP</i> esta afuera de <i>DOCUMENT READY</i> porque la función asincrona de <i>GOOGLE MAPS</i> se encarga de mandarla a llamar, para el inicio de la <i>APP WEB</i>.
</p>

```javascript
var url = "https://pcubicacion.firebaseio.com/usuarios.json";
var result = {};

$.ajax({
	type: "GET",
	contentType: "application/json; charset=utf-8",
	url: url,
	async: false,
	dataType: "json",
	success: function (data){
		//console.log(data); 
		result = data;
	},
});

console.log(result);
```

```javascript
$(document).ready(function(){
  window.setInterval(getAndDraw, 4000);
});

/*
  // Initialize Firebase
  var config = {
    apiKey: "AIzaSyBjE9Cr6iuDbG8x57_CcJ-9WDcheYmV62Q",
    authDomain: "mapas-50514.firebaseapp.com",
    databaseURL: "https://mapas-50514.firebaseio.com",
    projectId: "mapas-50514",
    storageBucket: "mapas-50514.appspot.com",
    messagingSenderId: "65462666897"
  };
  firebase.initializeApp(config);
  */
  var url = "https://pcubicacion.firebaseio.com/usuarios.json";
  var result = {};

  function getAndDraw(){

    $.when( 

      $.ajax({
        type: "GET",
        contentType: "application/json; charset=utf-8",
        url: url,
        async: false,
        dataType: "json",
        success: function (data){
        //console.log(data); 
        result = data;
      },
    })

      ).then(function( result, textStatus, jqXHR ) {

        console.log('result'+result);
        console.log('textStatus'+textStatus);
        console.log('jqXHR'+jqXHR);
        console.log('jqXHR.status'+jqXHR.status);
        var s = "hola";

        updateMapa(s);

      });


    }

    async function updateMapa(s){
      console.log('s: '+s);
      var LATITUD = Math.floor((Math.random() * 20) + 1);

		//google.maps.event.trigger(map, 'resize');

    var uluru = {lat: LATITUD, lng: LATITUD};
    var map = new google.maps.Map(document.getElementById('map'), {
      zoom: 4,
      center: uluru
    });

    var marker = new google.maps.Marker({
      position: uluru,
      map: map
    });
  }


  function initMap(){

    var uluru = {lat: 15.3000, lng: 101.044};
    var map = new google.maps.Map(document.getElementById('map'), {
      zoom: 4,
      center: uluru
    });

    var marker = new google.maps.Marker({
      position: uluru,
      map: map
    });

  }
```

```

$(document).ready(function(){
  window.setInterval(getAndDraw, 2000);
});

/*
  // Initialize Firebase
  var config = {
    apiKey: "AIzaSyBjE9Cr6iuDbG8x57_CcJ-9WDcheYmV62Q",
    authDomain: "mapas-50514.firebaseapp.com",
    databaseURL: "https://mapas-50514.firebaseio.com",
    projectId: "mapas-50514",
    storageBucket: "mapas-50514.appspot.com",
    messagingSenderId: "65462666897"
  };
  firebase.initializeApp(config);
  */
  var url = "https://pcubicacion.firebaseio.com/usuarios.json";
  var result = {};
  var usr = {};
  var array = [];

  function getAndDraw(){

    $.when( 

      $.ajax({
        type: "GET",
        contentType: "application/json; charset=utf-8",
        url: url,
        async: false,
        dataType: "json",
        success: function (data){
        //console.log(data); 
        result = data;
      },
    })

      ).then(function( result, textStatus, jqXHR ) {

        console.log('result'+result);
        console.log('textStatus'+textStatus);
        console.log('jqXHR'+jqXHR);
        console.log('jqXHR.status'+jqXHR.status);
        var s = "hola";


        // Deserealizar data
        $.each( result, function( key, val ) {

          //console.log("key: "+key+" lat: "+data[key].lat+" lon: "+data[key].lon);
          usr.nombre = key;
          usr.lat = result[key].lat;
          usr.lon = result[key].lon;

          array.push(usr);
        });

        updateMapa(array);

      });


    }

    async function updateMapa(coordenadasArray){
      console.log('coordenadasArray: '+coordenadasArray);

      var LATITUD  = coordenadasArray[0].lat;
      var LONGITUD = coordenadasArray[0].lon;

      var uluru = {lat: LATITUD, lng: LONGITUD};
      var map = new google.maps.Map(document.getElementById('map'), {
        zoom: 4,
        center: uluru
      });

      var marker = new google.maps.Marker({
        position: uluru,
        map: map
      });
    }


    function initMap(){

      var uluru = {lat: 15.3000, lng: 101.044};
      var map = new google.maps.Map(document.getElementById('map'), {
        zoom: 4,
        center: uluru
      });

      var marker = new google.maps.Marker({
        position: uluru,
        map: map
      });

    }
```
## Fuente

<p align="justify">
	<a href="https://developers.google.com/maps/documentation/javascript/adding-a-google-map">Google Maps API</a>.
</p>
