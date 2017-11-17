-Primero se instala mySQL:
"sudo apt-get install mysql-server"

-Luego ponemos contraseña al usuario root.

-Para entrar ponemos:
"mysql -u root -p"

-Nos descargamos la bbdd de worlds de internet

-Para pasar la bbdd a mySQL utilizamos el comando:
"mysql -u root -p < world.sql"

-Luego instalamos el php en con el comando:
"sudo apt-get install php-mysql"

-Reiniciamos apache con:
"sudo service apache2 restart"

Y ya tendriamos la bbdd dentro de  nuestro mySQL.

Podemos mirarlo entrando con el comando numero 3 y hacemos un:
"show database;" y veremos las tablas que tenemos, para seleccionar una hay que poner "use *nombre de la tabla*" y ya estariamos.
