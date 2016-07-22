# calculo
Este repositorio contiene el código fuente del libro de
**Cálculo Diferencial e Integral de funciones de una variable**, de Francisco Javier Pérez González (Universidad de Granada), licenciados bajo *Creative Commons BY-NC-SA*.

El libro original puede descargarse desde la página del [autor](http://www.ugr.es/~fjperez/apuntes.html).

Para compilarlo, simplemente ejecutar `make` o bien:

```bash
latex calculo.tex
dvips calculo.dvi
ps2pdf calculo.ps
```

Y obtenemos el fichero `calculo.pdf`. Probablemente, habrá que ejecutar al menos
dos veces la sentencia `latex calculo.tex` para no obtener referencias rotas.
