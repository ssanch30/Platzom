# PLATZOM

Platzom es un idioma es un idioma inventado para el [Curso de Fundamentos de JavaScript](https://platzi.com/js)
## Descripcion del Idioma

- Si la palabra   termina con "ar", se le quitan esas dos letras.
- Si la palabra inicia con Z, se le añade "pe" al final.
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitas y unir con un guión medio.
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y sedevuelve la misma palabra pero intercalando letras mayúsculas y minúsculas.


## Instalación

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("soemtemos") // SoMeTeMoS
```

##Créditos

-[Santiago Sanchez](https://github.com/ssanch30/)

##Licencia 
[MIT](https://opensource.org/licenses/MIT)