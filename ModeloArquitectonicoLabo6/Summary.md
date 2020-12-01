**Problema:**
El problema consiste en implementar una aplicacion la que me permite registrar los empleados que tengo, a su vez tambien editar y eliminar los empleados. Todo esto con vistas agradables y que la informacion este almacenada en una base de datos MySql.

**Patron:**
El Patron Arquitectonico monolitico que se uso para resolver este problema fue el de MVC(Model Vista Controlador), ya que este patron es mayormente usado para desarrollar aplicaciones de interfaces de usuario, como el problema solicita vistas con una buena experiencia de usuario, este modelo es el ideal para enfocarnos en ese punto y mostrar de la mejor manera los datos que el modelo obtendra de la base de datos.

**Readme:**
Este proyecto funciona con una base de datos local de MySql, para correr la aplicacion primero debe:
-Tener instalada MySql en su ordenador
-Correr las migraciones en el "NuGet Package Manager Console" con el siguiente comando Add-Migration FirstMigration
-Actualizar la base de datos con el siguiente comando Update-Database