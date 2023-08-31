# README - Tipos de Pokémon y Colores

Este README proporciona información sobre la función `obtenerColorTipo` y la estructura de datos `tiposDePokemon`, que se utilizan para asignar colores a diferentes tipos de Pokémon en tu proyecto.

## Descripción

En este proyecto, hemos definido un objeto llamado `tiposDePokemon`, que asocia varios tipos de Pokémon con colores representativos. Luego, hemos creado una función llamada `obtenerColorTipo` que toma un tipo de Pokémon como argumento y devuelve el color asociado a ese tipo desde el objeto `tiposDePokemon`.

## Uso

Puedes utilizar la función `obtenerColorTipo` para obtener el color asociado a un tipo de Pokémon específico. Aquí tienes un ejemplo de cómo puedes usarlo en tu código:

```javascript

// Ejemplo de uso
const tipoPokemon = "agua";
const colorAsociado = obtenerColorTipo(tipoPokemon);
console.log(`El color asociado al tipo ${tipoPokemon} es ${colorAsociado}`);
infoDiv.style.backgroundColor = obtenerColorTipo(tipoPokemon);
```

# Ejemplos de Tipos y Colores
Aquí tienes algunos ejemplos de tipos de Pokémon y sus colores asociados:

"agua" → "blue"
"fuego" → "red"
"planta" → "green"

# Instalacion del modulo.
bash
$ npm install paquete

# Exportar la Función.
La función obtenerColorTipo se ha exportado para que puedas utilizarla en otros archivos de tu proyecto. Aquí está cómo puedes importarla y usarla:
```Javascript
import paquete = require('paquete')
const tipoPokemon = "fuego";
let tipo = paquete.obtenerTIpo('vuelo')
```
