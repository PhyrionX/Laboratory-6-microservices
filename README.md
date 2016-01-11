# Microservices

## Dos microservicios activos y registrados
![](https://github.com/PhyrionX/Laboratory-6-microservices/blob/master/images/accounts.png)
![](https://github.com/PhyrionX/Laboratory-6-microservices/blob/master/images/web1.png)

## Aqui se muestran los microservicios registrados
![](https://github.com/PhyrionX/Laboratory-6-microservices/blob/master/images/web.png)

## Otro microservicio activo en el puerto 4444
![](https://github.com/PhyrionX/Laboratory-6-microservices/blob/master/images/accounts2.png)

##A brief report describing what happens when you kill the microservice with port 2222. Can the web service provide information about the accounts? Why?

Cuando el servicio en el puerto 2222 es finalizado, detecta que ha caído,  y lo replaza por otro si está disponible.

En este caso el servicio que corre en el puerto 4444.
