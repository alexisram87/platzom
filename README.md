# Platzom

Platzom es un idioma inventado para el [curso de fundamentos de JavaScript](https://platzi.com.js) de [platzi]("https://platzi.com.js"), el mejor lugar de educaciòn onLine

##

- Si la palabra termina con "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas

## Instalación

```
npm install platzom
```

## Uso

```
import platzom from "platzon"

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Créditos 
- [alexis](https://https://www.facebook.com/alexis.ramirezmeneses)

## Licencia

[MIT](https://opensource.org/licenses/MIT)