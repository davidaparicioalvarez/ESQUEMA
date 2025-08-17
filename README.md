# MyBusinessCentralApp



Proyecto AL desarrollado por David Aparicio Álvarez en APAWARE.

## Estructura del repositorio

Este repositorio sirve como plantilla para nuevos desarrollos de Business Central AL. La estructura está organizada para facilitar el desarrollo, pruebas, documentación y despliegue de extensiones AL.

- **Raíz**: Metadatos y configuración de la solución (`app.json`, `LICENSE`, `README.md`, `.gitignore`, `al.code-workspace`).
- **.github/**: Instrucciones para GitHub Copilot y flujos de trabajo.
- **app/**: Código fuente principal AL, organizado por tipo de objeto:
	- `Codeunits/`, `Pages/`, `PageExtensions/`, `Reports/`, `ReportExtensions/`, `Tables/`, `TableExtensions/`, `Enums/`, `EnumExtensions/`, `Interfaces/`, `Permissions/`, `Queries/`, `dotnet/`.
- **test/**: Estructura de pruebas para AL, actualmente contiene:
	- `TestCodeunits/`, `TestLibraries/`, `TestPages/` (todas vacías, listas para pruebas unitarias, de integración y de interfaz).
- **docs/**: Documentación del proyecto (ejemplo: `architecture.md`).
- **res/**: Recursos, como imágenes de logotipo (`logo/`).
- **scripts/**: Scripts de automatización (ejemplo: `deploy.ps1`).
- **Translations/**: Carpeta para archivos de traducción XLF (actualmente vacía).

La mayoría de las carpetas están vacías y sirven como plantilla para nuevos desarrollos AL siguiendo las mejores prácticas.

