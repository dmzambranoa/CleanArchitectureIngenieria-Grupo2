# CleanArchitectureIngenieria-Grupo2
## Taller 2 – Implementación del Patrón Repository xd
### Integrante
### Deisy Zambrano Ariza xd
* Descripción

En este taller se implementó el patrón Repository dentro de una arquitectura Clean Architecture.

Se utilizó como referencia la implementación existente para las entidades Almacén y Categoría, replicando la misma estructura para las demás entidades del sistema.

# Estructura del Proyecto xd   Está dividido en las siguientes capas
### CleanArchitecture.Domain
  Contiene las entidades del dominio y las interfaces de los repositorios.

### CleanArchitecture.Application
  Contiene los servicios o casos de uso que utilizan las interfaces del dominio.

### CleanArchitecture.Infrastructure
  Contiene la implementación concreta de los repositorios y el acceso a la base de datos.

### CleanArchitecture.Presentation
  Contiene los controladores de la API y la configuración de la aplicación.

# Ejecución del proyecto xd

## * Clonar el repositorio
## * Abrir la solución en Visual Studio Installer 2026
## * Restaurar paquetes NuGet
## * Ejecutar el proyecto desde la capa Presentation
