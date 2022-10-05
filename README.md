# ACME CLOTHING COMPANY
Acme Clothing es un proyecto de productos y promociones que tiene múltiples funciones como por ejemplo: 
 -añadir producto, eliminarlo, consultar a través de su ID
 -añadir promocion, eliminarla, consultarla y añadir promociones a diferentes productos

Para acceder a la base de datos, en este caso se ha utilizado h2.
Una vez arrancado el proyecto en el siguiente link: localhost:8080/h2-console 
	JDBC URL: jdbc:h2:mem:acme
	username : sa
	password: password


Para arrancar la aplicación, habría que abrir el proyecto en NetBeans, pulsar en el play e irnos a google donde pondremos el siguiente link:
	http://localhost:8080/swagger-ui/

Los EndPoints que nos vamos a encontrar en la aplicación son los siguientes:

	PRENDAS

	- /DEL/api/v1/prendas/{idPrenda} ----> Borrar una prenda
	- /GET/api/v1/prendas/ --------------> Muestra todas las prendas
	- /GET/api/v1/prendas/{idPrenda} ----> Recupera una prenda por el id que se le pase
	- /POST/api/v1/prendas/ -------------> Crea una nueva prenda

	PROMOCIONES

	- /DEL/api/v1/promociones/{idPromo} --> Borra una promocion 
	- /GET/api/v1/promociones/------------> Muestra todas las promociones que hay en la base de datos
	- /GET/api/v1/promociones/{idPromo} --> Recupera una promocion por el id que se le pase
	- /POST/api/v1/promociones/ ----------> Crea una nueva promocion
