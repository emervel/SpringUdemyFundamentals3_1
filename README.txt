--COMANDOS PARA CREAR SUBIR TU REPOSITORIO EN LOCAL AL GIT (primero tienes que haber creado un repositorio en github por la web, en este caso lo llame Prueba)
>git init
--aqui es donde he a�adido los ficheros que queria
>git add -A
>git commit -m "first commit"
>git remote add origin https://github.com/emervel/Prueba.git
>git push -u origin master


--COMANDOS PARA DESCARGAR UN REPOSITORIO EN LOCAL Y HACER CAMBIOS
>git clone https://github.com/emervel/Prueba.git
--aqui es donde he a�adido o modificado los ficheros que queria
>git add -A
>git commit -m "Second commit"
>git push -u origin master

--COMANDOS PARA ACTUALIZAR LOS CAMBIOS CON LO QUE HAY EN EL REPOSITORIO Y LUEGO ANADIR LOS MIOS
>git pull origin master
>git add -A
>git commit -m "Second commit"
>git push -u origin master



