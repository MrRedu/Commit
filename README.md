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


## Paso 2: Especificar un alcance (opcional)
El alcance aclara la zona afectada del proyecto.

| Etiqueta   | Descripción                     |
| :---       | :---                            |
| `auth`     | Autenticación y autorización.   |
| `ui`       | Interfaz de usuario.            |
| `api`      | API de backend o frontend.      |
| `core`     | Funciones básicas.              |
| `config`   | Archivos de configuración.      |
| `deps`     | Actualizaciones de dependencia. |
| `tests`    | Pruebas.                        |
| `docs`     | Documentación.                  |
| `db`       | Cambios en la base de datos.    |

### Ejemplos:

- docs(readme): add installation instructions
- feat(auth): add MFA (multi-factor authentication) support
- fix(ui): correct mobile menu overflow bug
- refactor(api): migrate user endpoints to GraphQL
- perf(db): optimize slow SQL queries in reports module
- test(e2e): add Cypress tests for checkout flow
- build(docker): update Alpine base image to v3.18
- ci(pipelines): add SonarQube analysis step
- chore(lint): enforce new ESLint rules
- revert(ci): rollback broken deployment script
