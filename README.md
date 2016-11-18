# bat-architecture-common

Este proyecto representa a una **librería de arquitectura** relacionada con los **elementos comunes a cualquier proyecto** que **proporcionaría** la organización **Batman Inc.** (Batman Incorporated) a todo su **sistema de franquicias**.

Esta librería destaca por :
- Definir las clases de **constantes globales **
- Definir las clases "Padre" de muchos de los componentes utilizados (Entidades, etc)
- Definir la excepción genérica propia de la organización (BatException)
- Definir los **frameworks comunes** y su versionado de obligado uso por parte de las franquicias

| Librería de Terceros | Versionado | Descripción |
| ---------- | -----| ------------------------- |
| `commons-lang`         | 3.4 | Utilidades para clases |
| `slf4j-api`   |1.7.16 | Logging |
| `logback`   | 1.1.5 | Implementación de logging |

Este proyecto utiliza la librería **bat-architecture-testing** para poder realizar las pruebas 

## Empezando

Estas instrucciones facilitan el poder disponer de una copia de proyecto totalmente funcional en la máquina local para fines de desarrollo y pruebas. Consulta la información de despliegue para ver como "utilizarlo" :-)

### Pre requisitos

Se definen que elementos se necesitan para instalar el software

```
Tener instalado Java 8 (Se requiere versión 1.5+)
Tener instalado Maven (Se aconseja que sea 3+)
```

**Nota : Se requiere tener generado inicialmente el artefacto bat-architecture-testing**

### Instalación

Pasos a seguir para poder disponer de un entorno de desarrollo

```
Arrancar la consola
Situarse en el PATH de instalación (el lugar donde se encuentra el proyecto )
Verificar que se encuentra disponible el fichero "pom.xml"
Ejecutar el comando : mvn clean install
```

El resultado será la generación de un artefacto en tu repositorio maven

## Ejecución de Test

Este proyecto dispone de 2 test unitarios

| Test | Descripción |
| ------------- | ------------- |
| `GlobalConstantTest`  | Prueba el acceso a todas las constantes de la clase |
| `BatExceptionTest`  | Pruebala generación de la excepción BatException|

## Despliegue

No aplica

## Construir con

* [Maven](https://maven.apache.org/) - Gestión de dependencias

## Versionado

**Nota :** Se utiliza [SemVer](http://semver.org/) para el versionado. 
Para ver las versiones disponibles acceder a los tags del repositorio

## Autores

* **Víctor Madrid** - *Arranque Inicial* 

## Agradecimientos

* [atSistemas](http://atsistemas.com/)
* A mis compañeros
* A todos los seguidores de batman (que somos unos cuantos ;-) )

