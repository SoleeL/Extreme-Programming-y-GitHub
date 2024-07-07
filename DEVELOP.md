# Extreme Programming y GitHub

## 0 Prefacio

### 0.1 Motivacion

El autor puede explicar por qué decidió escribir el libro, qué lo inspiró y cuál es la relevancia del tema tratado.

### 0.2 Proposito

Se describe el objetivo principal del libro, qué pretende lograr y a quién está dirigido. Esto puede incluir la audiencia a la que está destinado (por ejemplo, estudiantes, profesionales, investigadores, etc.).

### 0.3 Contexto y Antecedentes

Puede proporcionar información sobre el contexto en el que se escribió el libro, incluyendo cualquier investigación previa, estudios o experiencias personales que influyeron en el contenido.

### 0.4 Agradecimientos

Es común que el autor agradezca a las personas y organizaciones que contribuyeron de alguna manera a la creación del libro, como colegas, familiares, instituciones o financiadores.

### 0.5 Estructura

A menudo se ofrece una visión general de la organización del libro, describiendo brevemente los capítulos o secciones principales para orientar al lector sobre cómo está estructurada la información.

### 0.6 Notas

El autor puede incluir cualquier advertencia, como limitaciones del contenido, o notas sobre el estilo de escritura o el uso de terminología específica.

ESTE REPOSITORIO SERA UN EJEMPLO DE LA IMPLEMENTACION DE ESTA METODOLOGIA, por lo que no deberia ser dificil de seguir los ejemplos.

### 0.7 Comentarios y Preguntas

Redirigir a los issues de este repositorio

## 1 Customer's user stories

### 1.1 Que es?

Primera etapa de bla bla bla

Cuando nace el proyecto??

Las Customer's user stories son un conjunto inicial de funcionalidades (**User Stories**) que describen el Producto deseado o [Final product](#8-final-release).

Las User Stories o Historias de usuario son ... y en XP estan conformadas comumente por Requerimientos y Escenarios de prueba.

### 1.2 Donde estan en GitHub?

#### 1.2.1 Organizations

No es un requisito, pero si tu proyecto es o llega a ser muy grande, y depende de muchos repositorios, es recomendada la creacion de una **Organizacion**.

Podemos ver que Framework's muy conocidos como Vue o Angular tienen sus propias Organizaciones que pertenecen a una cuenta. De esta forma podemos tener aislados los proyectos y repositorios relacionados a nuestro **Producto**.

#### 1.2.2 Project


// TODO

### 1.3 Cual es el resultado?

#### 1.3.1 Entrada: Historias de usuario

Lo siguiente es definir un listado de **Historias de usuario**:

* Registro de Usuario
* Inicio de Sesión
* Recuperación de Contraseña
* Actualización de Perfil de Usuario
* Subida de Contenido Multimedia
* Comentarios en Publicaciones
* Me Gusta en Publicaciones
* Seguimiento de Usuarios
* Búsqueda de Usuarios y Contenido
* Notificaciones en Tiempo Real
* Mensajería Directa entre Usuarios
* Moderación de Contenido
* Reporte de Contenido Inapropiado
* Gestión de Configuraciones de Privacidad
* Integración de Autenticación de Terceros (OAuth)
* Visualización de Estadísticas de Interacción
* Compartición de Contenido en Otras Redes Sociales
* Implementación de Temas Oscuro/Claro
* Sincronización de Contenido Offline
* Gestión de Contenido Destacado
* Integración de Publicidad
* Creación de Grupos y Comunidades
* Moderación de Grupos y Comunidades
* Soporte para Etiquetas y Hashtags
* Servicio de API para Terceros
* Documentación de API para Desarrolladores
* Gestión de Permisos de Terceros
* Administración de Usuarios
* Control de Acceso y Roles
* Análisis de Datos y Reportes
* Gestión de Contenido Publicado
* Soporte y Atención al Cliente
* Integración de Métodos de Pago
* Configuración de Preferencias de Notificaciones
* Personalización de Feed de Noticias

#### 1.3.2 Salida: El Proyecto

Lo primero es la creacion de un Proyecto (Project) en GitHub (Personal o de Organizacion).

Project: Social-Appv1.0

Lo creamos con esa etiqueta de v1.0 entendiendo que ante la posibilidad de que el proyecto evolucione o necesite una redefinicion tras finalizada esta 1era version, existira una 2da o mas.

#### 1.3.3 Salida: **Requerimientos**

<!-- TODO -->

#### 1.3.4 Salida: **Test scenarios**

<!-- TODO -->

## 2 Release Planning

### 2.1 Que es?

Es cuando se identifica y priorizan los **Requerimientos**, y se crean estimaciones iniciales.

Tambien es cuando en base a los **Requerimientos** se plantea la creacion de **Productos de software** como aplicaciones web, aplicaciones escritorio, aplicaciones moviles, apis de servicio, infraestructura, pipelines o documentacion. Todos estos recursos se convierten en funcionalidades a traves del desarrollo o creacion de codigo. Y todo este codigo (fuente) es comunmente recopilado en servicios de gestion de versiones como GitHub.

### 2.2 Donde estan en GitHub?

#### 2.2.1 Repositorie

Es donde el codigo fuente de un producto de software es contenido y gestionadas sus versiones.

En un proyecto de software 

#### 2.2.2 Projects: Custom fields

Tenemos que ir a las configuraciones de nuestro **Project** y agregar un **Custom field** con el nombre de **Small release**.

### 2.3 Cual es el resultado?

#### 2.3.1 Entrada: Requerimientos

La entrada a esta etapa son los **Requerimientos** de las **Historias de usuario** que vienen de [Customer's user stories](#1-customers-user-stories), las devueltos de [Spikes](#3-spikes) y nacidas en los [Small release](#6-acceptace-testing-listening-to-feedback).

#### 2.3.2 Salida: Productos de software/Repositorios

Lo siguiente es considerar las **Requerimientos** (User Stories) y reconocer que **Productos de software**/**Repositorios** son necesario.

Listado de **Productos de software**/**Repositorios** necesarios:

* Mobile App (Frontend)
  * ```social-app-android```
  * ```social-app-ios```
* Backend Services
  * ```social-app-backend```
  * ```social-app-auth-service```
  * ```social-app-notifications-service```
  * ```social-app-messaging-service```
  * ```social-app-media-service```
  * ```social-app-search-service```
  * ```social-app-analytics-service```
  * ```social-app-api-gateway```
* Third-party Integrations
  * ```social-app-third-party-implementations```
  * ```social-app-api-documentation```
  * ```social-app-oauth-integration```
* Admin Services
  * ```social-app-admin-frontend```
  * ```social-app-admin-backend```
* Common Libraries
  * ```social-app-common-utils```
  * ```social-app-shared-models```
  * ```social-app-sdk```
* Infrastructure
  * ```social-app-infrastructure```
  * ```social-app-deployment-scripts```
  * ```social-app-terraform-scripts```
* Documentation
  * ```social-app-docs```
  * ```social-app-api-docs```
* Configuration and Secrets Management
  * ```social-app-configurations```
  * ```social-app-secrets-management```
* CI/CD Pipelines
  * ```social-app-cicd-pipelines```

#### 2.3.3 Salida: Release plan

El resultado es un **Plan de lanzamiento** de los **Historias de usuario** a largo plazo con varios **Small release**'s.

* Small Release v0.1: Funcionalidades Básicas de Usuario
  * Registro de Usuario
  * Inicio de Sesión
  * Recuperación de Contraseña
  * Actualización de Perfil de Usuario
  * Integración de Autenticación de Terceros (OAuth)
* Small Release v0.2: Interacciones Básicas de Contenido
  * Subida de Contenido Multimedia
  * Comentarios en Publicaciones
  * Me Gusta en Publicaciones
  * Seguimiento de Usuarios
  * Búsqueda de Usuarios y Contenido
  * Notificaciones en Tiempo Real
* Small Release v0.3: Interacciones Avanzadas y Personalización
  * Mensajería Directa entre Usuarios
  * Visualización de Estadísticas de Interacción
  * Compartición de Contenido en Otras Redes Sociales
  * Implementación de Temas Oscuro/Claro
  * Configuración de Preferencias de Notificaciones
  * Personalización de Feed de Noticias
* Small Release v0.4: Gestión de Contenido y Comunidades
  * Moderación de Contenido
  * Reporte de Contenido Inapropiado
  * Gestión de Contenido Destacado
  * Creación de Grupos y Comunidades
  * Moderación de Grupos y Comunidades
  * Soporte para Etiquetas y Hashtags
* Small Release v0.5: Integraciones y Administración Avanzada
  * Integración de Publicidad
  * Sincronización de Contenido Offline
  * Servicio de API para Terceros
  * Documentación de API para Desarrolladores
  * Gestión de Permisos de Terceros
  * Administración de Usuarios
  * Control de Acceso y Roles
* Small Release v0.6: Funcionalidades Avanzadas y Soporte
  * Análisis de Datos y Reportes
  * Soporte y Atención al Cliente
  * Integración de Métodos de Pago

## 3 Spikes

### 3.1 Que son los Spikes?

## 4 Iteration planning and desing

### 4.1 Que es un Iteration planning and desing?

### 4.2 Donde estan los Iteration planning and desing en GitHub?

#### 4.2.1 Issue

Issues

Issues del repositorio, la unidad minima colaborativa

Historias de usuario -> Issues

Es comun que una **Historia de usuario** no se traduzca en una unica **Issue**, ya que en caso de contar con multiples **Productos de software** esta podria afectar a una o mas. Por lo que de igual forma por cada **Historia de usuario** podriamos tener una o mas **Issue**'s en distintos **Repositories**.

#### 4.2.2 Iteration

Los Iteration planning and desing se ven reflejados en los **Project**. Aqui puedes encontrar la documentacion de como crearlos y hacerlos visibles en un **Project**.

Por ejemplo, si tuvieras 3 Iteration's, tendrias que crear algo como:

* Iteration plan 1 (duracion de 2 semanas)
* Iteration plan 2 (duracion de 2 semanas)
* Iteration plan 3 (duracion de 2 semanas)

#### 4.2.3 Milestone

Ahora, ya sea que tengamos uno o mas **Productos de software**/**Repositories**, tenemos que relacionar  

 en los Milestones o Hitos en Github.

### 4.3 Cual es el resultado?

#### 4.3.1 Entrada: Small release plan

La entrada a esta etapa viene del resultado de [Release planning](#2-release-planning).

* Small Release v0.1: Funcionalidades Básicas de Usuario
  * Registro de Usuario
  * Inicio de Sesión
  * Recuperación de Contraseña
  * Actualización de Perfil de Usuario
  * Integración de Autenticación de Terceros (OAuth)

#### 4.3.2 Salida: Iteration plan

* Iteration plan 1: Implementar el Registro de Usuario y el Inicio de Sesión
  * repositorio: social-app-backend
    * Issue: Implementar endpoints para Registro de Usuario -> POST /api/users/register
    * Issue: Implementar lógica de Inicio de Sesión -> POST /api/users/login
  * repositorio: social-app-api-gateway
    * Issue: Configurar y gestionar los servicios backend a través del gateway.
    * Issue: Implementar autenticación y autorización para endpoints.
    * Issue: Configurar rutas y endpoints para la autenticación.
  * repositorio: social-app-android
    * Issue: Implementar la interfaz de registro de usuario
    * Issue: Implementar la interfaz de inicio de sesión
  * repositorio: social-app-ios
    * Issue: Implementar la interfaz de registro de usuario
    * Issue: Implementar la interfaz de inicio de sesión

* Iteration plan 2: Implementar la Recuperación de Contraseña y Actualización de Perfil de Usuario
  * repositorio: social-app-backend
    * Issue: Implementar Recuperación de Contraseña -> POST /api/users/forgot-password
  * repositorio: social-app-android
    * Issue: Implementar la interfaz de recuperación de contraseña
    * Issue: Implementar la interfaz de actualizacion de perfil de usuario
  * repositorio: social-app-ios
    * Issue: Implementar la interfaz de recuperación de contraseña
    * Issue: Implementar la interfaz de actualizacion de perfil de usuario

* Iteration plan 3: Integración de Autenticación de Terceros (OAuth)
  * repositorio: social-app-auth-service
    * Issue: Implementar el registro de usuario a traves de OAuth
    * Issue: Implementar el inicio de sesion a traves de OAuth
  * repositorio: social-app-android
    * Issue: Implementar la interfaz de registro de usuario a traves de OAuth
    * Issue: Implementar la interfaz de inicio de sesion a traves de OAuth
  * repositorio: social-app-ios
    * Issue: Implementar la interfaz de registro de usuario a traves de OAuth
    * Issue: Implementar la interfaz de inicio de sesion a traves de OAuth

Todos los Issue del Small Release v0.1 deber ser asignados al Milestone v0.1.

## 5 Iteration

### 5.1 Que es?

### 5.2 Donde esta en GitHub?

### 5.3 Cual es resultado?

* Latest version: Extreme Programming y GitHub v0.1

## 6 Acceptace testing, listening to feedback

### 6.1 Que es?

### 6.2 Donde esta en GitHub?

### 6.3 Cual es resultado?

Customer approval

## 7 Small release

### 7.1 Que es?

### 7.2 Donde esta en GitHub?

tags con SemVer (Versionado Semántico v2.0.0: MAYOR.MENOR.PARCHE) actualizacion del MENOR.

El primer tag para un Small release corresponde a v0.1

### 7.3 Cual es resultado?

La entrada a esta etapa viene de ...

Tras un analisis podemos obtener nuevas historias de usuario, las cuales deben pasar por [Release planning](#2-release-planning), ser agregadas a los Projects correspondiente y definir su Milestone/Hito.

Ejemplo:

* New user story, next release:
  * User Story * Issue: Redactar "Customer's user stories: Que son las User Stories?"
  * User Story * Issue: Redactar "Small release: New user story, next release"
  * User Story * Issue: Redactar "Small release: Final product"

Podemos tomar la primera tarea y agregarla al "Project: Customer's user stories" y al Milestone v0.2. Mientras que la 2da y 3ra se agregan a "Project: Small release" y a un nuevo Milestone v0.4

* Release plan
  * Project: Customer's user stories
    * Milestone: Customer's user stories v0.2
      * User Story * Issue: Redactar "Customer's user stories: Que son las User Stories?"
  * Project: Small release
    * Milestone: Small release v0.4
      * User Story * Issue: Redactar "Small release: New user story, next release"
      * User Story * Issue: Redactar "Small release: Final product"

## 8 Final release

### 8.1 Que es?

### 8.2 Donde esta en GitHub?

tags con SemVer (Versionado Semántico 2.0.0: MAYOR.MENOR.PARCHE) actualizacion del MAYOR.

El primer tag para un Final release corresponde a v1.0

### 8.3 Cual es resultado?

La entrada a esta etapa viene de ...
