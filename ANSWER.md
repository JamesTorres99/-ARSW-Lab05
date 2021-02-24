# ARSW - Laboratorio 5

## Laboratorio – Laboratorio API REST para la gestión de planos

## Integrantes:

- Eduard Arias
- James Torres

### Descripción
En este ejercicio se va a construír el componente BlueprintsRESTAPI, el cual permita gestionar los planos arquitectónicos de una prestigiosa compañia de diseño. La idea de este API es ofrecer un medio estandarizado e 'independiente de la plataforma' para que las herramientas que se desarrollen a futuro para la compañía puedan gestionar los planos de forma centralizada. El siguiente, es el diagrama de componentes que corresponde a las decisiones arquitectónicas planteadas al inicio del proyecto.

### *PARTE I*

1.2. Modifique el bean de persistecia 'InMemoryBlueprintPersistence' para iniciar con 3 planos.

![bean](./img/media/8.png) 

3. Modifique la clase BlueprintAPIController.

![controller](./img/media/10.png) 
	
4. se verifico el funcionamiento de a aplicación

![app](./img/media/9.png) 

prueba

![app1](./img/media/1.png) 

5. se modifico el controlador para que ahora, acepte peticiones GET al recurso /blueprints/{author} 

![Prueba](./img/media/11.PNG) 

prueba

![app1](./img/media/2.png)

6. se modifico el controlador para que ahora, acepte peticiones GET al recurso /blueprints/{author}/{bpname}

![Prueba](./img/media/12.PNG) 

prueba

![app1](./img/media/15.png)

### *PARTE II*

1.2. se modifico el manejo de peticiones POST (creación de nuevos planos), de manera que un cliente http pueda registrar una nueva orden haciendo una petición POST al recurso ‘planos’, y enviando como contenido de la petición todo el detalle de dicho recurso a través de un documento jSON.

![Prueba](./img/media/13.PNG) 

prueba

![app1](./img/media/3.png)


3. Teniendo en cuenta el autor y numbre del plano registrado

resultado

![app1](./img/media/4.png)


3. se modifico el soporte al verbo PUT para los recursos de la forma '/blueprints/{author}/{bpname}', de manera que sea posible actualizar un plano determinado.

![Prueba](./img/media/14.PNG) 

prueba

![app1](./img/media/6.png)

resultado

![app1](./img/media/7.png)



