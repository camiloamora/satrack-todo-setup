# Prueba técnica Satrack

### Principales funcionalidades
* La aplicación debe permitir crear tareas
* Asignar una categoria
* Establecer una fecha límite

Se crearon dos repositorios para el frontend y el backend:

[![Web](https://img.shields.io/badge/GitHub-Frontend-14a1f0?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/camiloamora/satrack-frontend)

[![Web](https://img.shields.io/badge/GitHub-Backend-14a1f0?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/camiloamora/satrack-backend)

## Arquitectura seleccionada

![Arquitectura general](image.png)

Para la aplicación se hicieron las siguientes elecciones en tecnologías para completar la prueba:

* La libreria de UI para el frontend se escogieron tres repositorios, una libreria propia de componentes que habia desarrollado y tenia componentes reusables:
* [![Web](https://img.shields.io/badge/GitHub-components-14a1f0?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/camiloamora/zero-components)
* React-select
* React-DatePicker
* La tecnología escogida para el frontend fue Nextjs con react, css. [repo frontend](https://github.com/camiloamora/satrack-frontend)
* La tecnología escogida para el backend fue :net core versión 7.0, para la organización del proyecto se escogio arquitecturas limpias [repo backend](https://github.com/camiloamora/satrack-backend)
* La tecnología escogida para la base de datos fue mongodb, por la versatilidad en la estructura, y me evitaria un extra en el versionado y actualización de la base de datos.

El demo de la aplicación esta funcionando en esta Url:
[Demo App](https://satrack-app-todo.vercel.app/planning)

## Tecnologías cloud utilizadas
*   Para el despliegue de la base de datos se eligion mongo atlas por su facilidad de configuración y capa gratuita.
*   Para el frontend se eligio vercel por su facilidad y capa gratuita
*   Para el backend se eligio Azure con app services, por su facilidad de integración con .net y capa gratuita.

## Modelo de base de datos
* Para la base de datos se utilizo el siguiente schema:

```bash
 {
  Id,
  Description,
  UserId,
  Category,
  Status,
  CreatedAtDate,
  DueDate,
}
```

## Sistema de componentes
* Para los componentes del frontend se utilizo una libreria propia para los componentes de la card, input para ingresar la card, componentes de layout (vertical/horizontal):

* ![image](https://github.com/camiloamora/satrack-todo-setup/assets/2391098/6655cd23-3a8f-47fa-b39f-628b6587c372)
* Preview del diseño básico de la app

* ![image](https://github.com/camiloamora/satrack-todo-setup/assets/2391098/ff36a338-ce39-463b-972a-1c0f3e209a9f)

* ![image](https://github.com/camiloamora/satrack-todo-setup/assets/2391098/e22e9e04-60bc-488f-a8f4-5a285d3f8f4e)


