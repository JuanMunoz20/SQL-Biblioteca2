127.0.0.1/biblioteca/autores/		http://localhost/phpmyadmin/index.php?route=/database/sql&db=biblioteca

   Mostrando filas 0 -  2 (total de 3, La consulta tardó 0,0004 segundos.)


SELECT * FROM autores;


ID_Autor	Nombre	Nacionalidad	Fecha_Nacimiento	
1	Gabriel García Márquez	Colombiana	1927-03-06	
2	J.K. Rowling	Británica	1965-07-31	
3	George Orwell	Británica	1903-06-25	

127.0.0.1/biblioteca/categorias/		http://localhost/phpmyadmin/index.php?route=/table/sql&db=biblioteca&table=autores

   Mostrando filas 0 -  3 (total de 4, La consulta tardó 0,0004 segundos.)


SELECT * FROM categorias;


ID_Categoria	Nombre_Categoria	
1	Novela	
2	Ciencia Ficción	
3	Fantasía	
4	Ensayo	


127.0.0.1/biblioteca/libros/		http://localhost/phpmyadmin/index.php?route=/table/sql&db=biblioteca&table=categorias

   Mostrando filas 0 -  2 (total de 3, La consulta tardó 0,0005 segundos.)


SELECT * FROM `libros` WHERE 1;


ID_Libro	Titulo	ID_Autor	ID_Categoria	Año_Publicacion	Disponible	
1	Cien Años de Soledad	1	1	1967	1	
2	Harry Potter y la Piedra Filosofal	2	3	1997	1	
3	1984	3	2	1949	1	

127.0.0.1/biblioteca/prestamos/		http://localhost/phpmyadmin/index.php?route=/table/sql&db=biblioteca&table=libros

   Mostrando filas 0 -  1 (total de 2, La consulta tardó 0,0004 segundos.)


SELECT * FROM `prestamos` WHERE 1;


ID_Prestamo	ID_Usuario	ID_Libro	Fecha_Prestamo	Fecha_Devolucion	
1	1	1	2024-08-01	2024-08-15	
2	2	2	2024-08-02	2024-08-16	

127.0.0.1/biblioteca/usuarios/		http://localhost/phpmyadmin/index.php?route=/table/sql&db=biblioteca&table=prestamos_usuarios

   Mostrando filas 0 -  1 (total de 2, La consulta tardó 0,0004 segundos.)


SELECT * FROM `usuarios` WHERE 1;


ID_Usuario	Nombre	Direccion	Telefono	
1	Carlos Martínez	Calle Luna, 123	123456789	
2	Lucía Fernández	Avenida Sol, 456	987654321	
