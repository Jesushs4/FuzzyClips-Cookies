# Las galletas de la abuela María - Ejercicio de lógica difusa con Fuzzy CLIPS

## Jesús Herrera Sánchez y Denisa Ramona Belean

## Para la ejecución en FuzzyClips:

Copia los archivos bc.clp y bh.clp en FuzzyCLIPS/galletas y cárgalos:
```
(load "galletas/bc.clp")
(load "galletas/bh.clp")
```

Inicializa los hechos y ejecuta las reglas:
```
(reset)
(run)
```

Para ver la gráfica ejecuta:
```
(plot-fuzzy-value t * 150 250 4)
```

Calcula el valor de la temperatura
```
(maximum-defuzzify 4)
```
Valor esperado: 230.0 ºC

Centro de masas:
```
(moment-defuzzify 4)
```
Valor esperado: 206.25 ºC
