# Hoja de referencia: Conventional Commits

Entendemos commit como una **operación que guarda los cambios realizados en un repositorio.** Piénsalo como una "instantánea/screenshot" del estado de un proyecto en un momento determinado. Cada commit **registra los cambios que se han hecho en los archivos,** junto con un mensaje que describe qué se ha modificado y por qué.

## Paso 1: Elegir el tipo del commit
Empezar el mensaje con un tipo que refleje la naturaleza del cambio:

| Etiqueta   | Descripción                                                  | 
| :---       | :---                                                         | 
| `feat`     | Añadir una nueva funcionalidad.                              |
| `fix`      |  Corregir un error.                                          |
| `docs`     | Actualizar documentación.                                    |
| `style`    | Cambio en los estilos (formateo, espacios en blancos, etc).  |
| `refactor` | Reestructuración del código sin cambiar funcionalidades.     |
| `perf`     | Mejoras de rendimiento.                                      |
| `test`     | Añadir o actualizar pruebas.                                 |
| `build`    | Cambios en los scripts de compilación o en las dependencias. |
| `ci`       | Actualizaciones de las configuraciones CI/CD.                |
| `chore`    | Otras tareas (e.g., actualizando el _.gitignore_).           |
| `revert`   | Revertir un commit anterior.                                 |

### Ejemplos: 
- fix: fix token validation issue
- feat: add support for dark mode
- docs: update API documentation
- refactor: simplify database query logic
- perf: optimize image loading performance
- test: add unit tests for new features
- build: update build script to use latest dependencies
- chore: update project dependencies to latest versions
