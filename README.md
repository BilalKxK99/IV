# Material docente para la asignatura Infraestructura Virtual

[![Build Status](https://travis-ci.com/github/JJ/IV.svg?branch=master)](https://travis-ci.com/github/JJ/IV)
|
[![Checks README](https://github.com/JJ/Test-Text/workflows/Checks%20README/badge.svg)](https://github.com/JJ/IV/actions?query=workflow%3A%22Comprueba+README%22)
|
[![Lint Markdown](https://github.com/JJ/IV/workflows/Lint%20Markdown/badge.svg)](https://github.com/JJ/IV/actions?query=workflow%3A%22Lint+Markdown%22)

[Infraestructura virtual](https://grados.ugr.es/informatica/pages/infoacademica/guias_docentes/curso_actual/cuarto/tecnologiasdelainformacion/infraestructuravirtual)
es una asignatura obligatoria de la rama "Tecnologías de la Información" del
primer cuatrimestre del cuarto curso del Grado de Ingeniería Informática y
optativa en otras ramas y en el Doble Grado de Informática y Matemáticas.

La asignatura se imparte en el
[curso 2020-2021](https://etsiit.ugr.es/sites/centros/etsiit/public/inline-files/Horarios%20GII%20(20-21).pdf)
~en el aula 3.3 los viernes y en la 3.7 los martes de 9:30 a 11:30 (clases de
"prácticas"), y en la 1.8 los martes de 11:30 a 13:30. Se recuerda a los
estudiantes que en todas las clases será necesario llevar el portátil, ya que
son en realidad clases prácticas~de forma virtual desde las medidas
tomadas por la Junta.

Las clases se quedarán grabadas y almacenadas
[en esta lista de reproducción de YouTube](https://www.youtube.com/playlist?list=PLsYEfmwhBQdKIwbMDIwK64pt3Fs03BDz9).

Se usará [GitHub](https://github.com) para el proyecto, la forma principal de
examinar la asignatura; llamaremos *hitos* a cada una de las entregas que hay
que hacer del mismo.

Estos son los [objetivos de la asignatura](documentos/objetivos.md), cuyas
sesiones de clase se irán reflejando en
[un repositorio de GitHub; este es el de 2020-21](https://github.com/JJ/IV-20-21).

En resumen, nuestra intención es que el estudiante al final de la asignatura sea
capaz de hacer lo siguiente:

1. Definir el entorno de trabajo y pruebas para desarrollo de una aplicación en
   particular y desplegarlo en un PaaS.
2. Usar ese entorno para configurar integración continua en una aplicación.
3. Crear un entorno virtual para desarrollar y alojar la aplicación y comprenda
   el soporte físico de las técnicas usadas para crear tal entorno virtual.
4. Entienda las técnicas de configuración automática de entornos virtuales y
   las sepa aplicar en los entornos anteriores.
5. Use lo aprendido para despliegue masivo de aplicaciones en la nube.

## Temario - Programa de la asignatura

> Previo a la asignatura, es conveniente
> que [consultes este curso](https://jj.github.io/curso-tdd), con
> material suplementario a lo que se imparte en la asignatura. Los
> temas relevantes se enlazarán en cada hito.

Los materiales de la asignatura están enlazados desde abajo y
disponibles con una licencia libre. Los fuentes de los mismos están en
[GitHub](https://github.com/JJ/IV).

La temporización de la asignatura y los objetivos de cada sesión figuran en la
[bitácora](https://github.com/JJ/IV-20-21/blob/master/sesiones/README.md) de
clase. Enlazaremos también en ese fichero las grabaciones que se hagan de las
sesiones en vivo.

1. [Introducción](documentos/temas/Intro_concepto_y_soporte_fisico.md):
   conceptos y soporte físico. Esta introducción es *cultura general*; aunque
   conviene conocerlo, no es imprescindible para llevar a cabo, en general, el
   proyecto de la asignatura. Se aconseja vivamente, sin embargo, leerlo y
   llevar a cabo los ejercicios de autoevaluación.
2. [Iniciación a DevOps: desarrollo basado en pruebas](documentos/temas/Desarrollo_basado_en_pruebas.md).
3. [Usando contenedores](documentos/temas/Contenedores.md).
4. [Integración continua](documentos/temas/Integracion_continua.md).
5. Breve introducción a [REST](documentos/temas/REST.md).
6. Computación [Serverless](documentos/temas/Serverless.md).
7. [Puesta en marcha de microservicios](documentos/temas/Microservicios.md).
8. [Platform as a Service](documentos/temas/PaaS.md).

Estos temas se pueden consultar como material adicional, pero no forman parte
este año del temario de la asignatura:

1. [Introducción e historia de los contenedores](documentos/temas/Intro_contenedores.md).
2. [Técnicas de virtualización](documentos/temas/Tecnicas_de_virtualizacion.md).
3. [Aislamiento de recursos](documentos/temas/Aislamiento_de_recursos.md).
4. [Almacenamiento virtual](documentos/temas/Almacenamiento.md).
5. [Gestión de configuraciones](documentos/temas/Gestion_de_configuraciones.md).

## Seminarios

Material adicional interesante para la asignatura, que se impartirá
(en todo caso) fuera del horario lectivo.

1. [Mini-tutorial de Markdown, por Justo Javier Galera
   (JotaGalera)](documentos/seminarios/tutorial.md).
2. [Introducción ligera al lenguaje Ruby](documentos/seminarios/ruby.md).

## Prácticas - Actividades académicas dirigidas

La parte práctica de esta asignatura consiste en la realización de un
proyecto a lo largo de la asignatura, con diferentes hitos cuyo
contenido corresponde a los objetivos de aprendizaje cumplidos hasta
ese momento. Los proyectos
[consisten en crear la infraestructura virtual junto con una aplicación
desarrollada según el modelo DevOps](documentos/proyecto/README.md). A
grosso modo, los hitos se organizarán de la forma siguiente.

1. [Práctica cero: Uso básico de
   herramientas](documentos/proyecto/0.Repositorio.md).
2. [Organización de los grupos de práctica y creación del
   proyecto](documentos/proyecto/1.Infraestructura.md).
3. [Tests unitarios para la clase/s diseñadas](documentos/proyecto/2.Tests.md).
4. Técnicas de virtualización: [Contenedores](documentos/proyecto/3.Docker.md)
   para pruebas.
5. [Integración continua](documentos/proyecto/4.CI.md)
6. Despliegues [serverless](documentos/proyecto/5.Serverless.md)
7. [Creando microservicios](documentos/proyecto/6.Microservicio.md).
8. Desplegando a la nube:
   [Platform as a Service](documentos/proyecto/7.PaaS.md).

Estas prácticas se han hecho otros años:

1. [Provisionamiento de máquinas
   virtuales](documentos/proyecto/6.Provision.md).
2. [Virtualización de aplicaciones](documentos/proyecto/5.IaaS.md).

## Tutorías virtuales

Las tutorías virtuales se realizarán preferiblemente a través de la plataforma
de trabajo colaborativo
[GitHub](https://github.com/JJ/IV-20-21/issues?state=open) y a través del grupo
de Telegram; habrá que solicitar al profesor ser añadido. Finalmente, el
profesor está disponible por Telegram, Skype y Google Meet (en todos los
casos: `jjmerelo`).

Se creará también una sala específica en Jitsi para las tutorías,
consultar con los profesores la dirección y el horario.

## Criterios de evaluación

Los criterios de evaluación figuran en la
[ficha de la asignatura](https://grados.ugr.es/informatica/pages/infoacademica/guias_docentes/curso_actual/cuarto/tecnologiasdelainformacion/gii_infraestructura_virtual_20172018_firmada)
en la web del grado, y
[se especifican en el repositorio de la clase](https://github.com/JJ/IV-19-20/blob/master/Metodolog%C3%ADa_y_criterios_de_evaluaci%C3%B3n.md).

## Convocatoria extraordinaria (AL FINAL DEL CUATRIMESTRE)

Si no se ha superado la asignatura en la convocatoria ordinaria, en la
extraordinaria habrá que entregar los diferentes hitos del proyecto no
entregados, con los plazos que se anunciarán cuando se pongan las
notas de la convocatoria ordinaria.
