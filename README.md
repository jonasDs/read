read
====

![simpleweather.js logo](http://fc03.deviantart.net/fs70/i/2011/010/4/d/simple_weather_by_dijaysazon-d36unip.png)

#### Simpel weerbericht voor op jouw site #####

## Beschrijving
GeolocationandWeather.js is een javascript bestandje die via geolocatie jouw plaats bepaald en daarna het weer 
terug geeft gebaseerd op die locatie. Het doel is eigenlijk vlug en simpel een weerbericht te kunnen plaatsen 
op gelijk welke site, door middel van simpele addities. Het is zo makkelijk als een paar script tags toe voegen 
en een simpele <div> aan te maken.

# Bevat
* simpleWeather API
* geolocation van html5
* GeolocationandWeather.js
* GeolocationandWeather.css

## Hoe implementeren ?
Eerst voeg je een simpele link toe naar je css file.

```
<link href="./Geolocation.css" rel="Stylesheet">
```

Daarna voegen we ook de noodzakelijke scripts toe.

```
<script src="./lib/jquery.js"></script>
<script src="./lib/jquery.simpleWeather-2.3.min.js"></script>
<script src="./Geolocation.js"></script>
```

Als we deze zaken hebben toegevoegd is het alleen nog maar noodzakelijk om een simpele <div> toe te voegen waarin
het weerbericht wordt teruggegeven.

```
<div id="weather"></div>
```
