# Parcial 1, parte práctica

# Todoist

Para esta parte, decidimos realizar una suite de pruebas utilizando `cypress` para tomar capturas de pantalla sobre la aplicación. Además, las capturas que decidimos tomar fueron:

## A nivel externo:

- El home de la aplicación sin estar logueado: [link](https://todoist.com/)
- La página de cómo funciona: [link](https://todoist.com/tour)
- La página de Premium: [link](https://todoist.com/premium)
- La página de business: [link](https://todoist.com/business)
- La página de precios: [link](https://todoist.com/pricing)
- El modal de registro
- El modal de iniciar sesión
- La página de recuperar contraseña


Sin embargo, decidimos dejar fuera la página de [plantillas](https://todoist.com/templates/?lang=es) debido a que consideramos que al ser plantillas, son bastante propensas a cambiar y, por tanto, una prueba de regresión visual no será muy útil en esta página.

## Ya logueados:

- La pestaña de Hoy
- Crear una tarea
- La bandeja de entrada
- La pestaña de próximos 7 días
- Las tareas del proyecto de bienvenida
- El modal para agregar un proyecto
- El modal para agregar una tarea rápida
- El menú de configuración
- El registro de actividad
- El modal de los atajos del teclado
- La página de configuración de cuenta
- La página de configuración general
- La página de configuración de la suscripción
- La página de configuración del tema
- La página de configuración de Todoist Karma
- La página de configuración de notificaciones
- La página de configuración de integraciones

En esta parte decidimos no probar crear tareas o proyectos debido a que esto podría afectar ejecucuiones futuras pues la interfaz cambiaría. Además, porque ya el proyecto de bienvenida contiene varias tareas y permite apreciar como es la visualización tanto de las tareas como de los proyectos. Finalmente, consideramos que sí hubiese sido una buena idea realizar el flujo para poder cambiar el tema de la aplicación. Sin embargo, por cuestiones del presupuesto (8H por persona) no nos fue posible.

## [Capturas de pantalla](https://github.com/matrujillo10/miso-4208-parcial-1/tree/master/todoist/cypress/screenshots/simple_spec.js)

# RedReader

Para las pruebas de la aplicación RedReader limpia y modificada usamos dos estrategias:

1. Instalación de las aplicaciones y comparar funcionalidades
2. Descomprimir el APK para ver cambios en el código

Dentro de las pruebas realizadas entre las aplicaciones encontramos 10 errores que listamos a continuación

1. El contorno de la aplicación es rosado y no rojo
2. La opción account no sirve
3. themes tiene la funcionalidad de account
4. No está la opción de Subreddis suscritos en el home
5. La opción "Página principal" envía a "Todo sobre los subreddits"
6. La opción "Todos los subreddits" envía a la "Página principal"
7. En la sección About el orden de los ítems es diferente
8. Al ingresar a novedades, la aplicación se daña
9. No está la opción de "Fijar al menú principal" al seleccionar un subreddit del home
10. No está la opción de "Quitar del menú principal" al "Fijar al menú principal" un subreddit desde el detalle del subreddit

#### Pruebas de la APK limpia

[Parte 1](https://github.com/matrujillo10/miso-4208-parcial-1/blob/master/redReader/imagenes/Pruebas%20APK%20limpia%201.png)
[Parte 2](https://github.com/matrujillo10/miso-4208-parcial-1/blob/master/redReader/imagenes/Pruebas%20APK%20limpia%202.png)

#### Pruebas de la APK modificada

[Parte 1](https://github.com/matrujillo10/miso-4208-parcial-1/blob/master/redReader/imagenes/Pruebas%20APK%20modificada%201.png)
[Parte 2](https://github.com/matrujillo10/miso-4208-parcial-1/blob/master/redReader/imagenes/Pruebas%20APK%20modificada%202.png)
