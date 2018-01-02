•	The two microservices are running and registered:
	Account service:
	
	(https://github.com/siluf/lab6-microservices/blob/test/Documentacion/AccountService.png)
	(https://github.com/siluf/lab6-microservices/blob/test/Documentacion/AccountServiceDesdeRegistrationServerRun.png)
	
	Web Server:
	
	![alt text] (https://github.com/siluf/lab6-microservices/blob/test/Documentacion/WebService.png)
	![alt text] (https://github.com/siluf/lab6-microservices/blob/test/Documentacion/WebServiceDesdeRegistrationService.png)
	
•	A second account microservice is running in the port 4444 and it is registered

	![alt text] (https://github.com/siluf/lab6-microservices/blob/test/Documentacion/Apartado3.png)
	![alt text] (https://github.com/siluf/lab6-microservices/blob/test/Documentacion/Apartado3.1.png)
	
•	A brief report describing what happens when you kill the microservice with port 2222. 
	Can the web service provide information about the accounts? Why?
	
	![alt text] (https://github.com/siluf/lab6-microservices/blob/test/Documentacion/Apartado4.png)
	![alt text] (https://github.com/siluf/lab6-microservices/blob/test/Documentacion/Apartado4.1.png)
	![alt text] (https://github.com/siluf/lab6-microservices/blob/test/Documentacion/Apartado4.2.png)
	
	Cuando se para el servidor que está alojado en el Puerto 2222 y se intenta obtener información sobre ese servidor 
	se devuelve un error de conexión ya que este se encuentra inactivo. Cuando se vuelve a cargar el Account Server solo 
	muestra el servidor alojado en el puerto 4444 y si se quiere obtener información de este si que la proporciona , 
	al encontrarse activo.

