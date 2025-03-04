# Prueba técnica — Django developer

## Objetivo

El objetivo de esta prueba técnica es que el candidato muestre sus habilidades con las herramientas que utilizará luego en su trabajo diario. Está diseñado para verificar las habilidades de desarrollo back-end utilizando Django y su capacidad para resolver problemas.

Pondremos el foco en obtener un **código simple, bien diseñado y organizado, eficaz y testeado**, así como el cumplimiento de todos los requerimientos solicitados.


## Desarrollo del proyecto

- Se deberá clonar este repositorio para poder modificarlo y completarlo con la resolución del proyecto.
- Una vez que su código esté listo, suba el código a un repositorio público propio y envíenos el enlace a dicho repositorio para que lo revisaremos.

## Prueba técnica

1. Se deberá crear un sistema votaciones donde se deberá registrar la información
de los votantes tales como Nombre, Apellidos, Tipo de documento, Número de
documento, Género y Localidad.

2. Se deberá registrar los datos del candidato donde se deberá guardar la
información del nombre, el partido y la localidad

3. Una vez registrado los votantes y los candidatos se deberá registrar el
voto donde se deberá ingresar el votante y el candidato por el cual votará, para
votar se deben cumplir también las siguientes restricciones:

a) Deben existir tanto el votante como el Candidatos ingresados.

b) El votante no podrá realizar el voto por un candidato de una localidad diferente.

c) Un votante no podrá realizar más de un voto.

## consideraciones obligatorias

Version python: Python 3.8

Nombre de la base de datos "sistemavotaciones".

La base de datos debe ser SQL SERVER.

El script de la base de datos debe estar debe estar dentro del proyecto.

Se deberá crear al menos 3 api usando django-rest-framework.

Se deberá incluir también `READMEAPP` con instrucciones de configuración/ejecución y cualquier prueba u otra documentación que haya creado como parte de su solución.

Además, agregue la siguiente información a su archivo `READMEAPP`:

- Archivo requirements.txt: Contenido de las librerias utilizadas


## Consideraciones

Para los datos de: 

Genero:
* Femenino
* Masculino

TipoDocumento:
* Cedula de ciudadanía
* Cédula de extranjería

Localidad:
A
B
C
D
E

## Requisitos de Stack

Importante saber:
- No es necesario crear un entorno de desarrollo/producción.
- Se pueden utilizar otras librerías que crea conveniente, aunque se recomienda proporcionar una solución básica ajustada a lo solicitado, ya que nuestro objetivo principal es evaluar sus habilidades con Django y python.

## Opcionales

- incorporar JWT en su backend, para que solo se pueda acceder a las vistar estando autenticado.

