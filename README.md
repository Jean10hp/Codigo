# Primer dia con Git/Github

Comando para configurar el usuario y correo

* Para poder ver la version de Git 

~~~bash
git --version
~~~

* Para configurar el correo

~~~bash
git config --global user.email "email"
~~~

* Para poder configurar el usuario

~~~bash
git config --global user.name "username"
~~~ 

* Este comando sirve para empezar a usar el control de versiones 
* Esto solo se hace una vez 

~~~bash
git init
~~~

* Esto sirve para ver el estado de nuestros cambios.

~~~bash
git status
~~~

* Sirve para agregar los archivos a la memoria.

~~~bash
git add .
~~~

* Sirve para registrar los cambios realizados.

~~~bash
git commit -m "comentario"
~~~

* Poder ver el historial de commint

[ ] Git log retorna un 'id' con este id vamos a poder ver el detalle de los cambios que se hicieron en ese commit.

~~~bash
git log
~~~

* Para poder ver el detalle del commit usamos

~~~bash
git show id-commit
~~~

* Este comando sirve para subir al github

~~~bash
git push origin main
~~~