# Compu Tech Store

Sistema web de gestión para una tienda de productos tecnológicos, desarrollado con PHP y CodeIgniter 4.

## Descripción

Compu Tech Store es una aplicación web orientada a la administración de una tienda de tecnología. El sistema permite gestionar productos, clientes, proveedores, categorías y ventas mediante una interfaz web organizada.

La aplicación implementa autenticación de usuarios y control de acceso basado en roles, diferenciando las funciones disponibles para administradores y usuarios normales.

## Funcionalidades

### Gestión de productos

- Registrar productos.
- Consultar productos.
- Editar información de productos.
- Eliminar productos.
- Administrar precios, stock, categorías, proveedores y estado.

### Gestión comercial

- Registrar y administrar clientes.
- Gestionar proveedores.
- Gestionar categorías.
- Registrar ventas.
- Consultar el detalle de las ventas.

### Usuarios y seguridad

- Inicio de sesión.
- Registro de nuevos usuarios.
- Cierre de sesión.
- Autenticación mediante sesiones.
- Acceso diferenciado por roles.
- Protección de rutas administrativas y de usuario.
- Almacenamiento de contraseñas mediante hash.

### Interfaz

- Página principal de la tienda.
- Catálogo de productos.
- Formularios de registro y edición.
- Modales para iniciar sesión y crear cuentas.
- Carrusel de imágenes.
- Diseño basado en Bootstrap.

## Tecnologías

- PHP
- CodeIgniter 4
- HTML5
- CSS3
- Bootstrap 5
- MySQL
- Composer

## Arquitectura

El proyecto utiliza el patrón MVC de CodeIgniter 4:

- `app/Controllers`: controladores y lógica de las solicitudes.
- `app/Models`: modelos y acceso a los datos.
- `app/Views`: interfaces y plantillas de la aplicación.
- `app/Config`: configuración y rutas.
- `public`: punto de entrada público de la aplicación.

## Módulos principales

- Productos
- Clientes
- Categorías
- Proveedores
- Ventas
- Detalle de ventas
- Usuarios
- Roles
- Departamentos
- Municipios

## Requisitos

- PHP 8.1 o superior
- Composer
- MySQL
- Servidor web compatible con PHP

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/Jenncy/Proyecto-Final---PP.git
   ```

2. Entra al directorio del proyecto:

   ```bash
   cd Proyecto-Final---PP
   ```

3. Instala las dependencias:

   ```bash
   composer install
   ```

4. Crea una copia del archivo de variables de entorno:

   ```bash
   cp env .env
   ```

   En Windows puedes copiar manualmente `env` y renombrarlo como `.env`.

5. Configura en `.env` la URL de la aplicación y los datos de conexión a MySQL.

6. Configura el servidor web para utilizar la carpeta `public` como directorio público.

7. Inicia la aplicación y accede desde el navegador.

## Configuración de seguridad

No publiques credenciales, contraseñas ni claves secretas dentro del archivo `.env`. Utiliza valores locales y conserva únicamente un archivo de ejemplo para documentar la configuración necesaria.

## Estado del proyecto

Proyecto académico funcional desarrollado como proyecto final de programación.

## Mejoras futuras

- Agregar validaciones más completas en los formularios.
- Implementar búsqueda y filtrado de productos.
- Añadir paginación.
- Mejorar el control de inventario.
- Incorporar reportes de ventas.
- Agregar pruebas automatizadas.
- Mejorar el diseño responsive.
- Implementar confirmaciones antes de eliminar registros.
- Usar transacciones para guardar ventas y sus detalles.

## Autores

Proyecto desarrollado por un equipo de estudiantes de programación.
