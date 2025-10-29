# PetNet

Aplicación web para gestionar refugios y adopciones de mascotas (perros) orientada a conectar refugios con adoptantes potenciales. El objetivo de PetNet es facilitar la publicación de perros en adopción por parte de los refugios y agilizar el proceso para que consigan una familia.

## Descripción

- Gestiona fichas de perros (perfil, estado, salud, fotos).
- Permite a adoptantes registrarse, explorar y solicitar adopciones.
- Orientado inicialmente a refugios; más adelante, portal público para adopciones.

## Tecnologías

- **Framework**: Angular 20 (standalone, routing)
- **Estilos**: SCSS
- **Gestión**: Git (flujo de ramas `feature/` y `bugfix/`)

---

Este proyecto fue generado con [Angular CLI](https://github.com/angular/angular-cli) versión 20.3.8.

## Servidor de desarrollo

Para iniciar un servidor de desarrollo local, ejecuta:

```bash
ng serve
```

Una vez en ejecución, abre `http://localhost:4200/`. La aplicación recargará automáticamente al modificar archivos fuente.

## Generación de código (scaffolding)

Angular CLI incluye herramientas potentes de scaffolding. Para generar un nuevo componente, ejecuta:

```bash
ng generate component component-name
```

Para listar esquemas disponibles (como `components`, `directives` o `pipes`), ejecuta:

```bash
ng generate --help
```

## Construcción (build)

Para construir el proyecto, ejecuta:

```bash
ng build
```

Esto compilará el proyecto y almacenará artefactos en `dist/`. El build de producción aplica optimizaciones de rendimiento.

## Ejecutar tests unitarios

Usamos **Jest** para los tests unitarios.

```bash
npm run test
```

Modos útiles:

```bash
npm run test:watch   # ejecución en watch mode
npm run test:ci      # ejecución serial para CI
```

## Tests end-to-end

Para pruebas e2e, ejecuta:

```bash
ng e2e
```

Angular CLI no incluye por defecto un framework e2e; elige el que mejor se adapte a tus necesidades.

## Recursos adicionales

Para más información sobre Angular CLI, visita la [documentación oficial](https://angular.dev/tools/cli).
