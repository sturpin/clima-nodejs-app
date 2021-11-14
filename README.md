# Información :information_source:
Aplicación de consola desarrollada en NodeJS que nos permite consultar el clima.

```
=======================
 Seleccione una opción 
=======================

? ¿Qué desea hacer? 
> 1. Buscar ciudad
  2. Historial
  0. Salir
```

# Características :package:
La aplicación nos permite buscar por ciudad. Cada búsqueda que realices se queda almacenada en el **Historial**.

```
Información de la ciudad

Ciudad: Cieza, Región de Murcia, España
Lat: 38.23912
Long: -1.41897
Temperatura: 13.6
Mínima: 12.13
Máxima: 16.34
Cómo está el clima: cielo claro
```

# Cómo empezamos? :notebook_with_decorative_cover:
Para utilizar la aplicación necesitamos tener una cuenta en [Open Weather Map](https://openweathermap.org/) y otra en [Mapbox](https://www.mapbox.com/), el registro es gratuito. Una vez registrados debemos de obtener una _KEY_ para poder utilizar ambos servicios.

Posteriormente renombramos el fichero **example.env** por **.env** y colocamos ahí los _KEY_ que hemos obtenido.

# Herramientas :hammer_and_wrench:
- [NodeJS 16.13.0](https://nodejs.org/en/)
- [Inquirer](https://www.npmjs.com/package/inquirer)
- [Colors](https://www.npmjs.com/package/colors)
- [Dotenv](https://www.npmjs.com/package/dotenv)