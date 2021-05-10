# Definición operaciones de conteo y teoría de probabilidades para bc

Para ejecutar *bc* con las funciones que predefinimos escribimos:

```bash
$ bc -il bc_defines.bc
```

En el, se implementan una serie de funciones que describo a continuación:

- `comb (n,x)`: Combinaciones de n en x.
- `poisson (s,x)`: Función de probabilidad de la Poisson en x con parámetro s.
- `apoisson (s,x)`: Función de probabilidad acumulada de la Poisson en x con parámetro s.
- `binomial (n,p,x)`: Función de probabilidad de la Binomial en x con parámetros n y p.
- `abinomial (n,p,x)`: Función de probabilidad acumulada de la Binomial en x con parámetros n y p.
- `geometrica (p,x)`: Función de probabilidad de la Geométrica en x con parámetro p.
- `ageometrica (p,x)`: Función de probabilidad acumulada de la Geométrica en x con parámetro p.
- `binomialneg (n,p,x)`: Función de probabilidad de la Binomial Negativa en x con parámetros n y p.
- `abinomialneg (n,p,x)`: Función de probabilidad acumulada de la Binomial Negativa en x con parámetros n y p.
- `hipergeometrica (n,m,k,x)`: Función de probabilidad de la Hipergeométrica en x con parámetros n, m y k.
- `ahipergeometrica (n,m,p,x)`: Función de probabilidad acumulada de la Hipergeométrica en x con parámetros n, m y k.