# FARMABOL - Sistema de Gestión para Farmacia

## Descripción

FARMABOL es un sistema web desarrollado en PHP y MySQL para la gestión de farmacias. Permite administrar usuarios, clientes, productos, laboratorios, tipos de medicamentos, presentaciones y ventas.

## Tecnologías Utilizadas

* PHP
* MySQL / MariaDB
* HTML5
* CSS3
* JavaScript
* Bootstrap
* AdminLTE
* XAMPP

## Requisitos

Antes de ejecutar el sistema, asegúrese de tener instalado:

* XAMPP (Apache y MySQL)
* Navegador web moderno
* phpMyAdmin

## Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/Dani-gu/FARMABOL.git
```

### 2. Copiar el proyecto

Ubicar la carpeta del proyecto dentro de:

```text
C:\xampp\htdocs\
```

### 3. Iniciar servicios

Abrir XAMPP y encender:

* Apache
* MySQL

### 4. Crear la base de datos

Ingresar a phpMyAdmin:

```text
http://localhost/phpmyadmin
```

Crear una base de datos llamada:

```sql
v_farmacia
```

### 5. Importar la base de datos

Importar el archivo:

```text
v_farmacia.sql
```

### 6. Configurar la conexión

Verificar el archivo:

```text
conexion.php
```

Configuración por defecto:

```php
$host = "localhost";
$user = "root";
$pass = "";
$db = "v_farmacia";
```

Modificar los datos si es necesario.

## Ejecución

Abrir el navegador e ingresar:

```text
http://localhost/FARMABOL
```

## Credenciales de Acceso

Administrador:

Usuario:

```text
admin
```

Contraseña:

```text
admin
```

## Funcionalidades

* Gestión de usuarios
* Gestión de clientes
* Gestión de productos
* Gestión de laboratorios
* Gestión de tipos de medicamentos
* Gestión de presentaciones
* Registro de ventas
* Control de inventario

