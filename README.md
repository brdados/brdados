<!-- README.md is generated from README.Rmd. Please edit that file -->
brdados
=======

[![Travis-CI Build
Status](https://travis-ci.org/brdados/brdados.svg?branch=master)](https://travis-ci.org/brdados/brdados)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/brdados/brdados?branch=master&svg=true)](https://ci.appveyor.com/project/brdados/brdados)

Funções que usamos para produzir nossos gráficos e análises.

Tema
----

Para aplicar o tema para `ggplot2` em um gráfico, basta chamar a função
`tema_brdados` concatenadamente:

``` r
g + geom_point() + tema_brdados()
```
