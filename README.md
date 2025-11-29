# Gestión de Tareas - Proyecto ASP.NET Core

Este proyecto contiene la implementación de una **aplicación web para la gestión de tareas**, desarrollada utilizando **ASP.NET Core** durante el webinar "Uso de ASP.NET Core". El proyecto sigue el patrón de arquitectura **Modelo-Vista-Controlador (MVC)** y está diseñado para permitir a los usuarios gestionar sus tareas de manera individualizada.

## Funcionalidades Principales
- **Autenticación de Usuarios**: Cada usuario tiene su cuenta personalizada y puede acceder a su lista de tareas.
- **Administración de Tareas**:
  - Crear nuevas tareas desde su cuenta.
  - Consultar y visualizar tareas previamente creadas.
  - Modificar tareas existentes (como la descripción y prioridad).
  - Eliminar tareas que ya no sean necesarias.
- **Filtrado de Tareas**: Los usuarios pueden organizar sus tareas según prioridad o fecha, facilitando la gestión.
- **Almacenamiento de Datos**: La aplicación emplea **Entity Framework Core** y una base de datos SQL Server para gestionar y guardar la información de las tareas y los usuarios.

## Tecnologías Empleadas
- **ASP.NET Core 7.0**: Framework utilizado para el desarrollo de la aplicación web, proporcionando una estructura robusta y eficiente.
- **Entity Framework Core**: Herramienta ORM para manejar las interacciones con la base de datos de manera sencilla y eficiente.
- **SQL Server**: Sistema de gestión de bases de datos utilizado para almacenar la información del proyecto.
- **Bootstrap**: Framework CSS utilizado para asegurar que la interfaz de usuario sea moderna y responsiva en diferentes dispositivos.
