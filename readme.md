## Significados de los parametros para Odata###

$filter: Permite filtrar los datos, permite definir criterios de búsqueda
$stock gt 10: con stock mayor a 10.

	•	eq: Igual a.
	•	ne: Diferente de.
	•	lt: Menor que.
	•	le: Menor o igual que.
	•	gt: Mayor que.
	•	ge: Mayor o igual que.

$select: Ayuda a especificar los campos o propiedades que deben ser devueltos
$select=title,author: Devuelvo solo los campos titile y author

$expand: Permite incluir datos relacionados de entidades asociadas. Sirve para jerarquia de los metadatps
$expand=author: Devuelvo los datos del autor

$orderby: Nos ayuda a ordenar los datos según una o más propuedades
$orderby=price desc: Ordeno los datos por precio de forma descendente

$top: Me ayuda  a limitar el resultados de los datos en los n primeros elemtos de la lista que estpy consultando
$top=4: Me devuelve los 4 primeros elemneot de la lista

$skip: Me permite omitir los primeros n elementos de la lista que estoy consultando
$skip=2: Me permite omitir los 2 primeros elementos de la lista

$count: Me ayuda a obtener los los números totales de una entidad o colección de datos
$count=true: Me devuelve el número total de elementos de la lista

$format: Me permite especificar el formato de los datos que se devuelven
$format=json: Me devuelve los datos en formato json

$search: Me permite realizar una búsqueda de texto completo en los datos
$search=pruebas: Busco la palabra pruebas en los datos

$compute: Me permite realizar cálculos en los datos que se devuelven
$compute=price mul 2: Multiplico el precio por 2
