## <1.2.0> - <2024-04-17>

### Sprint learnings

- Pude hacer y entender más las operaciones Crud, junto a sus validaciones , parámetros y argumentos. 
- Entendí más la ruta de la información dentro de la API.
- Entendí más sobre cómo leer y manejar las pruebas e2e.

### Added

- Todas las operaciones Crud funcionan según lo esperado y superan las pruebas
- Más verificaciones
- Más manejo de errores

### Changed

- Se modificaron todas las operaciones CRUD para que tu vieran el comportamiento esperado por la clienta

### Fixed

- Tests: globalSetup y users.spec

### Removed

- Folder crud

## <1.1.1> - <2024-04-10>

### Sprint learnings

- Sobre autenticaciones de usuarios, más sobre operaciones CRUD involucradas para armar el CRUD en el controller
- Específicamente sobre autenticaciones con JWT y qué es uid
- Más sobre el flujo desde mi terminal hacia mongodb y postman
- Estoy entendiendo más sobre middleware
- Estoy entendiendo más sobre el manejo de errores y la asíncronía

### Added

- Creación de todo el CRUD e implementación según cada ruta
- Se agregaron más validaciones para logear
- Se hace verificación de decodedToken

### Changed

- Se modificó operación CRUD asociada a la autenticación

### Fixed

- Tests: globalSetup y users.spec

### Removed

- orders & producta .spec

## <1.1.0> - <2024-04-03>

### Sprint learnings

- Conexión de mongodb con mongoose en el entorno nodejs
- Schemas basados en la documentación
- Model y CRUD 

### Added

- Se instala mongodb y mongoose
- Creación correcta de usuario admin to do 2,

### Changed

- CRUD con mongoose y no con mongodb

### Fixed

- N/A

### Removed

- N/A

## <1.0.0> - <2024-03-27>

### Sprint learnings
- Aprendí sobre la arquitectura de un servidor web (arquitectura de cliente/servidor)
- Trabajé con MongoDB a través de Compass
- Postman para peticiones a la API (HTTP)
- Documentación clienta, empecé a comprender
- Changelog.md
- Github Project

### Added

- N/A

### Changed

- N/A

### Fixed

- N/A

### Removed

- N/A



<!-- // git log --all --since='7 days ago' --oneline --format="* %h %s (%an) %as" -->

<!-- Dado un número de versión MAYOR.MENOR.PARCHES, incrementa lo siguiente:

MAYOR versión cuando realizas cambios incompatibles en la API

MENOR versión cuando agregas funcionalidad de manera compatible hacia atrás

PARCHES versión cuando realizas correcciones de errores compatibles hacia atrás -->

[Versiones semánticas 2.0.0](https://semver.org/)