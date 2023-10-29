La funcion SI esta dentro de la categoria de Funciones Logicas. Devuelve un resultado dependiente de una o condicion (prueba logica). En su forma mas simple solo permite obtener dos posibles respuestas. En estructuras mas complejas permite obtener todas las respuestas necesarias.

Sintaxis

```
  = Si(Prueba_logica;[valor_si_verdadero];[valor_si_falso])

```

PRUEBA_LOGICA: Caulquier estructura de formula comparativa o funcion que arroje verdadero o falso.
VALOR_SI_VERDADERO: Resultado que devolvera la funcion si la PRUEBA LOGICA arroja VERDADERO.
VALOR_SI_FALSO: Resultado que devolvera la funcion si la PRUEBA LOGICA arroja Falso.


## Funcion si anidada
La funcion SI, en su forma mas simple, da dos opciones de respuesta: el valor_si_verdadero y el valor_si_falso. Pero si anidamos la funcion SI dentro de si misma las posibles respuestas aumentan. Veamos cual seria la estructura.
<br>
<b>Sintaxis</b>:

```
=SI(prueba_logica;[valor_si_verdadero]; SI(prueba_logica;[valor_si_verdadero]; SI(prueba_logica;[valor_si_verdadero];SI(prueba_logica;[valor_si_verdadero];[valor_si_falso]))))

```


