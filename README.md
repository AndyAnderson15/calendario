
# Proyecto - Calendario
Prueba de Conocimientos Técnicos de PHP con Framework Laravel
# Paso 1. Realizar Diagrama del Proyecto 📊
Se desarollo un diagrama para el desarollo del programa, la lógica.
# Paso 2. Instalación de LARAVEL
* Servidor Laragon
* Composer (getcomposer.org) - en el navegador
# Paso 3.  CMD de Laragon
* Crear el proyecto - (laravel new calendario)
* Instalador del composer con laravel - (composer global require laravel/installer)
* Ingresar a la ruta y adentro de la carpeta calendario se debe levantar el proyecto (php artisan serve)
# Paso 4.  Proyecto en Visual Studio Code
* Schema calendario dentro de una base de datos en el archivo (.env)
Importante:
* Realizar migración adentro de laragon.
* Esctructura para crear la tabla es ( php artisan make:migration create_events_table)
# Paso 5.  Crear un Modelo
* Se encarga de comunicar una tabla de una base de datos.
* Se crea con (php artisan make:model Event) - primera con mayúscula y en singular
# Paso 6.  Crear Rutas
* Todos los url de nuestra app
* La url que redirije el cliente

# Paso 7.  Crear Carpetas
* Se crea una carpeta en resource llamado events con ( index.blade.php)
* Tambien se crea el ( edit.blade.php  ) ( create.blade.php )

# Autores 💻
* <p>Anderson Ladino - <a href="https://github.com/AndyAnderson15">AndyAnderson15</a></p>


