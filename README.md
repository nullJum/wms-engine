WMS Engine — Sistema de Gestión de Almacenes

Proyecto académico enfocado en el desarrollo de un Sistema de Gestión de Almacenes (WMS) diseñado para administrar inventario, entradas y salidas de productos, así como operaciones básicas dentro de un almacén.

Este sistema fue desarrollado como parte de un proyecto académico de ingeniería de software y demuestra la implementación de software logístico basado en bases de datos.


Descripción General

El objetivo de este proyecto es simular un entorno simplificado de gestión de almacenes, donde los usuarios pueden:

Registrar y administrar productos

Controlar niveles de inventario

Registrar entradas de mercancía al almacén

Registrar salidas de productos

Interactuar con una base de datos relacional mediante una aplicación de escritorio

El sistema integra una base de datos en SQL Server con una aplicación desarrollada en .NET, encargada de gestionar las operaciones básicas del almacén.


🛠 Tecnologías Utilizadas

C#

.NET

SQL Server

SQL Server Management Studio (SSMS)

⚙️ Requisitos

Para ejecutar este proyecto necesitas tener instalado:

SQL Server (Express o superior)

SQL Server Management Studio (SSMS)

El script de instalación de la base de datos: InstaladorBD.sql

El código fuente completo del proyecto

🗄 Instalación de la Base de Datos

Este proyecto incluye un script SQL que crea automáticamente la estructura de la base de datos junto con datos de ejemplo.

Pasos

Abrir SQL Server Management Studio (SSMS)

Conectarse a la instancia local de SQL Server

Ir a File → Open → File

Seleccionar el archivo InstaladorBD.sql

Ejecutar el script haciendo clic en Execute o presionando F5

Una vez ejecutado, la base de datos aparecerá en Object Explorer.

🔑 Credenciales de Prueba

El sistema incluye una cuenta de prueba para fines demostrativos.

Campo	Valor
Usuario	admin
Contraseña	123

Estas credenciales se proporcionan únicamente para evaluación académica.


📂 Estructura del Proyecto

El repositorio incluye:

WMS-Engine/
│
├── Database/
│   └── InstaladorBD.sql
│
├── SourceCode/
│   └── Aplicación WMS
│
└── README.md

SourceCode → Aplicación de escritorio desarrollada en C# y .NET

Database → Script SQL para crear la base de datos

README → Documentación del proyecto


⚠️ Aviso

Este proyecto fue desarrollado con fines académicos y puede utilizarse para:

-Estudio
-Pruebas
-Modificaciones educativas

No está diseñado para uso en producción sin mejoras o desarrollo adicional.


Autor:
Alejandro Juárez

GitHub:
https://github.com/nulljum

Proyecto desarrollado bajo JumEngine
