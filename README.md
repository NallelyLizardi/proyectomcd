# Nallely Lizardi proyectomcd
Primer parte.
Al leer la base de datos y usar como prueba con un "header", se encontro que las claves de las columnas se leian como objetos. Asi que se tuvo que cambiar a header(7), para que los datos
pudieran empezar a leerse a partir de esa fila. .
Siguiente paso.

Al momento de usar la funcion describe y notar la falta de informacion, fue cuando se encontro que la base de datos se estaba leyendo desde la fila uno
por lo que se procedio a usar el head(7), apartir de ahi la funcion "describe" nos arrojo los datos que se requerian.

#Siguiente:
Se intenro realizar de diferentes formas y con diferentes funciones las graficas requeridas en el proyecto, pero el programa no arrojo los resultados esperados.

Se intento realizar los demas puntos sin resultados positivos. Se utilizo GroupBy para intentar agrupar los datos, drop para eliminar filas, etc.
Considero que esta situaciones pueden deberse a que en algunas columnas se mezclan datos numericos con datos no numericos o espacios vacios (NaN) 


