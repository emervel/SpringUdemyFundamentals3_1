SpringBeansDemo
1.SpringBeansApplication: 
	-puedes ver como se arranca Spring y como acceder a un Bean creado en la misma clase (user) o recuperado por el framework (datasource). 
	-ojo que en el ComponentScan le tienes que decir en que paquetes debe buscar los beans
2.PageController: 
	-es un ejemplo perfecto de como inyectar una dependencia de tipo Service (NotificationService) usando el autowired sobre un set (tb podria ser sobre un constructor). 
	-tiene los RequestMapping para indicarte a donde ir
	-tiene un Value para setear en una valiable un valor de un properties
3.DataSourceConfig:
	-es de tipo Configuration para carga un bean llamado dataSource y que tendra valores distintos segun sea el profile de development o production
4.application.propeties
	-tienes propiedades definidas por mi como pageController.msg=Hello from properties
	-tienes propiedades de Spring que podemos cambiar como server.port=8080
	-la variable de Spring spring.profiles.active te dira que profile estas usando para la aplicacion
5.Persona
	-permite rellenar automaticamente todos los valores del POJO con los valores del propeties
  








--COMANDOS PARA CREAR SUBIR TU REPOSITORIO EN LOCAL AL GIT (primero tienes que haber creado un repositorio en github por la web, en este caso lo llame Prueba)
>git init
--aqui es donde he añadido los ficheros que queria
>git add -A
>git commit -m "first commit"
>git remote add origin https://github.com/emervel/Prueba.git
>git push -u origin master


--COMANDOS PARA DESCARGAR UN REPOSITORIO EN LOCAL Y HACER CAMBIOS
>git clone https://github.com/emervel/Prueba.git
--aqui es donde he añadido o modificado los ficheros que queria
>git add -A
>git commit -m "Second commit"
>git push -u origin master

--COMANDOS PARA ACTUALIZAR LOS CAMBIOS CON LO QUE HAY EN EL REPOSITORIO Y LUEGO ANADIR LOS MIOS
>git pull origin master
>git add -A
>git commit -m "Second commit"
>git push -u origin master



