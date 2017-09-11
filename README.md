# manu


Con esto puedes ver la documentación de las funciones de latino en la consola

Esta basada en la doc oficial http://documentacion.lenguaje-latino.org/

```
git clone https://github.com/robincoello/manu.git
cd manu
```
y para usar ejecutas 
```
latino manu leer

```

en lugar de ```leer``` pones el nombre de la funcion que deseas el manual

## Como se genera? 

en http://localhost/latino_doc/gestion le pasamos como parametro 

?p=funciones&c=exportar_txt

Asi en /gestion/ se crean fichero .txt estos los movemos a 

```
sudo mv *.txt ~/manual 

```

y listo! 


## todo 
poner los ejemplos y los parametros que aun falta 





