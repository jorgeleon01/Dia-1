# Manual de Procesos   #

Este repositorio contiene los procesos que se desarrollan frecuentemente .

Se ha creado como repositorio con control de versiones, para facilitar las actualizaciones y busquedas en la documentacion.

De esta forma procesos obsoletos pueden ser eliminados en un commit, y nunca se perderan realmente, porque se pueden ver las lineas eliminadas. Asimismo al momento de agregar documentación queda registro de quien, cuándo y cómo se modificó

# Generar Documento en PDF

Para generar este manual en PDF se utiliza:

https://github.com/walle/gimli: una libreria escrita en ruby
https://wkhtmltopdf.org/:

```
$gem install gimli
gimli -file pages/ -cover pages/z-cover.md -w '--toc --footer-right "[page]/[toPage]"' -s media/documentation.css -merge -outputfilename Manual
```

## Indice ###

### Actividades Diarias

* 


### Actividades Semanales

* Tarea1


### Actividades Mensuales

* Tarea1



### Actividades onDemand

* Tarea1


### Procesos automáticos

* Tarea1



### ACCIONES CRÍTICAS

* Tarea1

