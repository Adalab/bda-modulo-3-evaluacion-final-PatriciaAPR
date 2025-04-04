## OBSERVACIONES DEL DF CUSTOMER FLIGHT
-En la columna de year y month al parecer se repiten los datos
-Hay varias columnas que tienen muchos valores en 0 (flight booked, total fligh, distance, las de los points)
-Loyalty number identificador que podría ser la columna de unión con el otro df
-La tabla tiene 405624 filas , 9 columnas. todas son int (valores enteros), ecepto la una (points acumulate) que es float (valores decimales)
-No tiene valores nulos
-Contiene valores duplicados


## OBSERVACIONES DEL DF LOYALTY HISTORY
-Tiene la columna loyalty number, se confirma que es la columna de unión
-Tiene valores NaN en las columnas de salary, cancelation year, y cancelation month
-Tiene 16737 filas y 15 columnas
-Tiene los siguientes tipos de datos float64(4), int64(2), object(9)
-Buscamos los nulos y parece que existen nulos en salary, cancelation year y cancelatio month
-Al parecer no tiene valores duplicados
-El Describe nos indica que todos los datos son de Canada, 


## DF final
-En la exploración anterior los nulos estaban en salary, cancelation year y cancelatio month. Decido dejar la columna de salario sustituyendo los nulos por la mediana y para las 2 columnas debido a que están relacionadas he creado una columna nueva en donde coloco su relación y la utilizo para contestar a las preguntas
