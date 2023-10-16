# Bobatea - Sistema de Gestión de Ventas y Compras

Bobatea es un sistema de gestión de ventas y compras de productos desarrollado en PHP y MySQL. Este sistema está diseñado para ayudarte a administrar eficientemente las transacciones de ventas y compras de tu negocio.

## Características

- Registro de productos: Permite agregar y gestionar los productos disponibles en tu tienda, incluyendo información detallada como nombre, precio, cantidad en stock, y categoría.
- Gestión de inventario: Realiza un seguimiento en tiempo real de la cantidad de productos en stock.
- Ventas: Registra las ventas de productos a tus clientes, calcula el precio total y actualiza automáticamente el inventario.
- Compras: Registra las compras de productos que haces a tus proveedores, manteniendo un registro completo de tus transacciones.
- Informes y estadísticas: Genera informes de ventas, compras e inventario para tomar decisiones informadas sobre tu negocio.
- Gestión de usuarios: Control de acceso con diferentes roles (administrador, empleado) para garantizar la seguridad de tus datos.
- Interfaz de usuario intuitiva y fácil de usar.

## Requisitos del Sistema

- Servidor web (por ejemplo, Apache) con soporte para PHP.
- Servidor de base de datos MySQL.
- PHP 7.0 o superior.
- Navegador web moderno (se recomienda Chrome o Firefox).

## Instalación

1. Clona el repositorio de Bobatea en tu servidor web:
   
   git clone https://github.com/tuusuario/bobatea.git


2. Crea una base de datos MySQL para Bobatea y configura las credenciales de acceso en el archivo `global.php` y el archivo `conexion.php`
define('DB_HOST', 'tu_host');
define('DB_USER', 'tu_usuario');
define('DB_PASS', 'tu_contraseña');
define('DB_NAME', 'nombre_de_la_base_de_datos');

 3. Importa la estructura de la base de datos desde el archivo database.sql incluido en el repositorio:

mysql -u tu_usuario -p nombre_de_la_base_de_datos < database.sql

   


