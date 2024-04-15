
# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.


## Tecnologías Utilizadas
- **PHP:** Puedes mencionar algunas características clave de PHP que hacen que sea adecuado para el desarrollo web, como su capacidad para generar contenido dinámico, su amplia compatibilidad con diferentes sistemas operativos y servidores web, y su comunidad activa que ofrece una gran cantidad de recursos y bibliotecas.
- **MySQL:** Además de mencionar que es un sistema de gestión de base de datos, podrías explicar brevemente por qué MySQL es una opción popular para aplicaciones web, destacando su confiabilidad, escalabilidad y compatibilidad con una variedad de lenguajes de programación.
- **HTML & CSS:** Podrías mencionar la importancia de HTML y CSS para la estructura y el diseño de las páginas web, así como también destacar algunas características de Tailwind CSS que lo hacen útil para el desarrollo rápido y la creación de interfaces de usuario consistentes.

## Estructura del repositorio:

- La aplicación podría estar estructurada en una serie de carpetas y archivos. Por ejemplo:
 - Carpeta app/: Contiene los scripts PHP responsables de las operaciones CRUD.
 - Carpeta config/: Podría contener archivos de configuración, como el archivo de conexión a la base de datos.
 - Carpeta sql/: Puede incluir archivos SQL para la creación de la base de datos y la tabla de usuarios.
 - Carpeta public/: Contiene archivos accesibles públicamente, como CSS, JavaScript y archivos de imagen.
 - Archivo index.php: Puede ser el punto de entrada de la aplicación.

## Descripción de archivos clave:

- config/db.php: Archivo de configuración de la base de datos que contiene las credenciales de conexión.
- app/create.php: Script PHP para agregar un nuevo usuario a la base de datos.
- app/read.php: Script PHP para recuperar y mostrar información de usuario de la base de datos.
- app/update.php: Script PHP para actualizar la información de usuario existente.
- app/delete.php: Script PHP para eliminar un usuario de la base de datos.

## Funcionalidades específicas:

- **Validación de formularios:** Podría haber funciones para validar la entrada del usuario y evitar la inserción de datos incorrectos.
- **Paginación de resultados:** Si hay muchos usuarios, la aplicación podría implementar paginación para mostrar resultados en varias páginas.
- **Autenticación de usuarios:** Puede haber un sistema de inicio de sesión para restringir el acceso a ciertas funcionalidades solo a usuarios autenticados.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Instrucciones de instalación y ejecución:

- Se proporcionaría un archivo README.md con instrucciones claras sobre cómo configurar y ejecutar la aplicación en un entorno local.
- Esto incluiría la importación de la base de datos utilizando los archivos SQL proporcionados, configuración del servidor web (como Apache o Nginx), y cualquier otra configuración necesaria.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

