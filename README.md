# 🐾 Sistema de Gestión Veterinaria

## 1. Descripción del proyecto

El Sistema de Gestión Veterinaria es una aplicación web desarrollada para facilitar la administración de los servicios de una veterinaria y mejorar la experiencia de los usuarios al momento de acceder a sus servicios.

La plataforma permite gestionar diferentes roles de usuario, consultar información de la veterinaria, administrar citas y acceder a notificaciones. También incorpora funcionalidades relacionadas con la recuperación de contraseñas y la consulta de la política de tratamiento de datos personales.

El proyecto busca centralizar las principales operaciones de atención veterinaria en una plataforma accesible, organizada e intuitiva.

## 2. Objetivos del proyecto

### Objetivo general

Desarrollar una aplicación web para la gestión de servicios veterinarios que facilite la administración de citas, mejore la comunicación con los usuarios y permita el acceso organizado a las funcionalidades del sistema según el rol asignado.

### Objetivos específicos

- Implementar un sistema de acceso y recuperación de contraseñas.
- Incorporar diferentes roles para organizar el acceso a las funcionalidades.
- Permitir a los usuarios agendar, reprogramar y cancelar citas veterinarias.
- Facilitar la consulta de la ubicación física de la veterinaria.
- Implementar un módulo de notificaciones.
- Proporcionar acceso a la política de tratamiento de datos personales.
- Mejorar la experiencia de navegación mediante una interfaz organizada y adaptable a diferentes dispositivos.

## 3. Funcionalidades principales

### 3.1. Autenticación y acceso

El sistema incorpora funcionalidades para facilitar el ingreso y la administración del acceso de los usuarios.

- Inicio de sesión.
- Recuperación de contraseña.
- Acceso a las funcionalidades según el rol asignado.
- Organización de las opciones disponibles para cada tipo de usuario.

> La implementación de validaciones, envío de correos y mecanismos de restablecimiento seguro depende de los servicios de autenticación configurados en el proyecto.

### 3.2. Política de tratamiento de datos personales

Se incorporó una sección destinada a presentar la política de tratamiento de datos personales de la veterinaria.

Esta sección permite consultar información relacionada con el manejo y la protección de los datos personales, así como las condiciones de su tratamiento por parte de la organización.

### 3.3. Rol de administrador

El acceso administrativo debe concentrar las funciones de configuración y supervisión general de la plataforma, de acuerdo con los módulos implementados.

Las operaciones administrativas disponibles dependerán de los permisos y funcionalidades desarrollados en el sistema.

### 3.4. Rol de recepcionista

El rol de recepcionista está orientado a apoyar la atención al cliente y el seguimiento de las citas programadas.

Entre las funcionalidades incorporadas para este rol se encuentran:

- Consultar las citas programadas para el día.
- Identificar las citas que ya fueron atendidas.
- Visualizar las citas que se encuentran pendientes de atención.
- Facilitar el seguimiento de la agenda diaria de la veterinaria.

Estas funcionalidades permiten mantener una mejor organización de la recepción y apoyar el control de la atención presencial.

### 3.5. Rol de usuario

El rol de usuario está diseñado para que los clientes puedan acceder a los servicios de la veterinaria y administrar sus citas desde la plataforma.

**Funcionalidades disponibles:**

- **Consultar la ubicación:** visualizar la información de ubicación de la veterinaria.
- **Agendar citas:** solicitar una nueva cita veterinaria según las opciones disponibles.
- **Reprogramar citas:** modificar una cita previamente agendada.
- **Cancelar citas:** solicitar la cancelación de una cita registrada.
- **Consultar notificaciones:** visualizar las notificaciones disponibles dentro de la plataforma.
- **Consultar la política de tratamiento de datos:** acceder a la información sobre el tratamiento de los datos personales.
- **Recuperar contraseña:** iniciar el proceso para recuperar el acceso a la cuenta cuando se olviden las credenciales.

## 4. Tecnologías utilizadas

Completa esta sección con las tecnologías que realmente utiliza tu proyecto.

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura de las páginas web. |
| CSS3 | Estilos y presentación visual. |
| Bootstrap | Diseño adaptable y componentes de interfaz, si está integrado. |
| Git | Control de versiones del código fuente. |
| GitHub | Alojamiento del repositorio, si se utiliza. |

**Nota:** la tabla es una referencia inicial. Se deben agregar o eliminar tecnologías según las herramientas utilizadas en el desarrollo real.

## 5. Requisitos del sistema

Para ejecutar el proyecto en un entorno de desarrollo, se recomienda contar con:

- Un sistema operativo compatible con las herramientas utilizadas.
- Un editor de código, como Visual Studio Code.
- Git para administrar el control de versiones.
- Un navegador web actualizado.
- El entorno de ejecución y las dependencias requeridas por el backend, si corresponde.
- Una base de datos configurada, si la aplicación utiliza persistencia de datos.

## 6. Instalación y ejecución

### 6.1. Clonar el repositorio

Abre una terminal y ejecuta:

```bash
git clone URL_DEL_REPOSITORIO
```

Reemplaza `URL_DEL_REPOSITORIO` por la dirección real del repositorio.

### 6.2. Ingresar al proyecto

```bash
cd NOMBRE_DEL_PROYECTO
```

### 6.3. Instalar dependencias

Este paso depende de las tecnologías utilizadas.

Si el proyecto utiliza Node.js y npm:

```bash
npm install
```

Si no utiliza Node.js, sigue el procedimiento de instalación correspondiente a tu entorno de desarrollo.

### 6.4. Configurar variables de entorno

Si la aplicación utiliza variables de entorno, crea el archivo de configuración indicado por el proyecto y define las variables necesarias para la conexión con la base de datos, los servicios de correo y otros servicios externos.

No publiques contraseñas, claves privadas, tokens ni credenciales reales en el repositorio.

### 6.5. Ejecutar la aplicación

Si el proyecto utiliza un script de desarrollo configurado en `package.json`, puedes ejecutar:

```bash
npm run dev
```

Este comando solo aplica si existe un script `dev` definido en el proyecto. En caso contrario, utiliza el comando de ejecución correspondiente a tu configuración.

## 7. Estructura del proyecto

La estructura debe actualizarse para reflejar las carpetas y los archivos reales de la aplicación.

Una organización de referencia podría ser:

```text
veterinaria/
├── public/
│   ├── assets/
│   └── images/
├── src/
│   ├── components/
│   ├── pages/
│   ├── styles/
│   ├── services/
│   └── utils/
├── .gitignore
├── README.md
└── package.json
```

**Descripción de las carpetas:**

- `public/`: recursos estáticos disponibles para la aplicación.
- `assets/`: recursos gráficos y otros archivos utilizados por la interfaz.
- `components/`: componentes reutilizables de la interfaz.
- `pages/`: páginas o vistas principales del sistema.
- `styles/`: hojas de estilo.
- `services/`: comunicación con el backend y servicios externos, si aplica.
- `utils/`: funciones auxiliares reutilizables.
- `README.md`: documentación general del proyecto.
- `package.json`: configuración y dependencias, si el proyecto utiliza Node.js.

Esta estructura es ilustrativa y no implica que todas estas carpetas existan actualmente.

## 8. Gestión de roles y permisos

La plataforma organiza las funcionalidades de acuerdo con los roles definidos en el sistema.

| Rol | Responsabilidad principal |
|---|---|
| Administrador | Supervisión y administración general de la plataforma, según los permisos implementados. |
| Recepcionista | Consulta y seguimiento de las citas del día, identificando las atendidas y pendientes. |
| Usuario | Consulta de ubicación, gestión de citas y visualización de notificaciones. |

La autorización de cada operación debe validarse de acuerdo con los permisos asignados al usuario. Ocultar opciones en la interfaz no sustituye las validaciones de seguridad en el servidor.

## 9. Gestión de citas

El módulo de citas permite al usuario administrar sus solicitudes de atención veterinaria.

### Operaciones disponibles

1. Agendar una cita.
2. Consultar las citas registradas, según las opciones habilitadas.
3. Reprogramar una cita existente.
4. Cancelar una cita.
5. Consultar las notificaciones relacionadas con la atención, cuando se encuentren disponibles.

Las operaciones deben respetar las reglas de disponibilidad, los estados de las citas y las validaciones definidas por el sistema.

## 10. Sistema de notificaciones

La plataforma cuenta con una sección para consultar las notificaciones disponibles para el usuario.

Su propósito es centralizar la información relevante generada por el sistema y facilitar el seguimiento de las novedades relacionadas con sus servicios.

El envío de notificaciones por correo electrónico, SMS o notificaciones push no se considera habilitado a menos que exista una integración específica para esos canales.

## 11. Ubicación de la veterinaria

La aplicación incorpora una funcionalidad para consultar la ubicación física del establecimiento.

Esta característica busca facilitar la llegada de los clientes a la veterinaria y apoyar la asistencia a las citas presenciales.

La forma de presentación —dirección textual, enlace a un mapa o mapa integrado— depende de la implementación realizada.

## 12. Seguridad y protección de datos

El proyecto contempla el acceso a la política de tratamiento de datos personales y la organización de las funcionalidades mediante roles.

Para fortalecer la seguridad de la aplicación, se recomienda:

- Validar los datos recibidos en formularios.
- Implementar controles de autenticación y autorización.
- Proteger las contraseñas mediante mecanismos de almacenamiento seguro.
- Validar los permisos en el backend.
- Evitar la exposición de información sensible.
- Utilizar conexiones HTTPS en producción.
- Mantener las dependencias actualizadas.
- Proteger las credenciales y variables de entorno.
- Aplicar medidas de protección a los datos personales conforme a la normativa colombiana aplicable.

La existencia de una sección con la política de tratamiento de datos no garantiza por sí sola el cumplimiento legal. El documento debe corresponder a las prácticas reales de tratamiento de información de la veterinaria.

## 13. Control de versiones

El desarrollo del proyecto utiliza Git para registrar los cambios realizados durante la implementación de nuevas funcionalidades.

Se recomienda utilizar mensajes de commit descriptivos que permitan identificar el propósito de cada modificación.

Ejemplo:

```bash
git add .
git commit -m "feat: agregar gestión de citas y funcionalidades del usuario"
```

Para consultar el historial de cambios:

```bash
git log --oneline
```

## 14. Pruebas recomendadas

Antes de publicar nuevas versiones, se recomienda verificar los siguientes escenarios:

- Inicio de sesión con credenciales válidas e inválidas.
- Recuperación de contraseña.
- Acceso autorizado según el rol del usuario.
- Consulta de la política de tratamiento de datos.
- Visualización de la ubicación de la veterinaria.
- Registro de nuevas citas.
- Reprogramación de citas existentes.
- Cancelación de citas.
- Consulta de notificaciones.
- Visualización de las citas atendidas y pendientes por parte de recepción.
- Validación de formularios y manejo de errores.
- Adaptación de la interfaz a dispositivos móviles.

## 15. Estado del proyecto

El proyecto se encuentra en desarrollo e incorpora funcionalidades para la autenticación, la recuperación de contraseñas, la consulta de información institucional y la gestión de citas según los roles definidos.

Las funcionalidades adicionales, integraciones externas y procesos de despliegue se documentarán a medida que se implementen y validen.

## 16. Autoría y mantenimiento

**Proyecto:** Sistema de Gestión Veterinaria  
**Tipo:** Aplicación web  
**Área:** Gestión de servicios veterinarios  
**Estado:** En desarrollo  
**Repositorio:** Agregar URL del repositorio  
**Responsable:** Agregar nombre del desarrollador o equipo

---

*Este documento debe mantenerse actualizado con cada cambio significativo en las funcionalidades, las tecnologías, la estructura del código y los procedimientos de instalación del proyecto.*
