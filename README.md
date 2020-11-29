Introducción
Se desarrolló una página web que emula una empresa de servicios musicales, utilizando las herramientas de HTML y CSS aprendidas en clase, a través del versionamiento de GitHub.

Propósito
Este documento describe las funcionalidades del sitio web

Alcance
El código desarrollado permite visualizar un sitio web con los servicios musicales y los integrantes del equipo desarrollador. Este sitio web no permite realizar compras dentro del mismo.

Descripción del producto
Los usuarios son aquellas personas interesadas en adquirir servicios musicales de grabación, edición de partituras y producción de espectáculos

Funciones  del producto
Este software permite la visualización de 5 secciones que contienen:
1. Menú de Inicio
2. Servicios
3. Noticias
4. Miembros del equipo
5. Contacto y link al repositorio de GitHub

Características del usuario
Las capacidades que el usuario debe tener son mínimas, contar con un computador y un mouse para navegar por el sitio web

Restricciones
-EL sitio web solo es informativo
-No permite hacer compras dentro del sitio
-No permite generar solicitudes como generar nombre entre otras

Requisitos específicos
1.Secciónsuperior,cabeceraoheader:estaseccióndeberácontarconelmenúdenavegaciónatrespáginasinternasdelsitiowebysurespectivoenlacealinicio.Debe contar con una imagen que ocupe el ancho del sitio.El menú debe de estar en un tag  <nav></nav>.
2.Seccióndeservicios:aquílosestudiantesdeberándividirenanchodelsitioen3partesyencadapartesedeberáincluirunservicio.Cadaserviciodebecontarconunabrevedescripción,unlogo,íconooimagenqueloidentifiqueyunenlacealdetalledelosservicios.Elelementodondeestánlosserviciosdebedetenerunid=”services”
3.Seccióndenoticias:Elestudianteencargadodelaseccióndenoticias,deberádividirelanchodelsitioweben2filasydoscolumnasparapresentar4noticias.Cadanoticiadebecontarconunresumen,unaimagenyunenlacealeerlanoticiacompleta.El elemento donde están los servicios debe de tener un id=”news”
4.Seccióndeequipo:Elestudiantedeberádividirelanchodelsitioentreelnúmerodeparticipantesdelequipoeincluirjuntoconcadaunounafotooimagen,elnombreyalgún dato como la institución educativa, edad, pasatiempo, entre otros.El elemento donde están los servicios debe de tener un id=”team”
5.SecciónFooteropiedelsitio:elestudiantedeberácrearelpiedelsitiowebendondeseincluyeinformacióndecontacto,deberáestardivididoendospartes,enunasetendrálainformacióndelsitiowebcomoelmotivantedeldesarrolloyelenlacealrepositoriodegithub,yenlaotraloscontactodelosmiembrosdelequipocon sus nombres y roles. La sección debe de estar en un tag <footer></footer>
Requisitos  funcionales
1- El software debe mostrar un banner un menú de inicio
2. Debe visualizar una sección de servicios
3. Debe mostrar una sección de noticias con un link
4. VIsualizar los miembros del equipo
5. Debe contener un footer con información de contacto.
Requisitos no funcionales
-El ancho del sitio debe ser 1200 pixeles
-Que las fotos sean libre de derechos de autor
-Que sea vea en cualquier navegador
-Que los links lleven a la página web deseada

Historia de Usuario 1: Header
Nombre: Menú de Inicio
Funcionalidad: mostrar un menú con los títulos inicio, servicio, noticias y equipo
Criterio de Aceptación: que los enlaces del menú redirijan a las secciones del sitio web

Historia de Usuario 2: Servicios
Nombre: Servicios
Funcionalidad: mostrar 3 servicios musicales, grabación, edición de partituras y producción de eventos
Criterio de Aceptación: despliegue exitoso de los servicios ofrecidos

Historia de Usuario 3: Noticias
Nombre: Noticias
Funcionalidad: mostrar 4 noticias del ámbito musical
Criterio de Aceptación: redirigir a las noticias publicadas

Historia de Usuario 4: Equipo
Nombre: Miembros del Equipo
Funcionalidad: mostrar los miembros del equipo desarrollador
Criterio de Aceptación: despliegue exitoso de los miembros del equipo

Historia de Usuario 5: Footer
Nombre: Footer
Funcionalidad: mostrar los datos de contacto y roles de los miembros del equipo
Criterio de Aceptación: despliegue exitoso de la información de datos de contacto


# Proyecto final Sprint I

Desarrollar un sitio web que conste de 5 secciones, cada sección deberá ser realizada por un estudiante. Los diferentes elementos del sitio web contarán con estilos personalizados creados por los estudiantes y deberán estar condensados en una sola hoja de estilos.

Para iniciar con el desarrollo del sitio web, los estudiantes deberán definir previamente aspectos como ancho del sitio (mínimo 1200px), la información a presentar en el sitio web, diseñar un mockup, borrador o bosquejo, también descargar, diseñar o crear los recursos a utilizar como imágenes, iconos, logos, entre otros y finalmente asignar responsable a cada sección.

El proyecto, deberá manejarse versionado en un repositorio remoto en github, en el que los diferentes miembros del equipo deben tener acceso, no se permite el push directo a las ramas Dev o Master.

## Secciones

- Sección superior, cabecera o header: esta sección deberá contar con el menú de navegación a tres páginas internas del sitio web y su respectivo enlace al inicio. Debe contar con una imagen que ocupe el ancho del sitio.
  El menú debe de estar en un tag `<nav></nav>`.
- Sección de servicios: aquí los estudiantes deberán dividir en ancho del sitio en 3 partes y en cada parte se deberá incluir un servicio. Cada servicio debe contar con una breve descripción, un logo, ícono o imagen que lo identifique y un enlace al detalle de los servicios. El elemento donde están los servicios debe de tener un `id=”services”`
- Sección de noticias: El estudiante encargado de la sección de noticias, deberá dividir el ancho del sitio web en 2 filas y dos columnas para presentar 4 noticias. Cada noticia debe contar con un resumen, una imagen y un enlace a leer la noticia completa.
  El elemento donde están los servicios debe de tener un `id=”news”`

- Sección de equipo: El estudiante deberá dividir el ancho del sitio entre el número de participantes del equipo e incluir junto con cada uno una foto o imagen, el nombre y algún dato como la institución educativa, edad, pasatiempo, entre otros.
  El elemento donde están los servicios debe de tener un `id=”team”`

- Sección Footer o pie del sitio: el estudiante deberá crear el pie del sitio web en donde se incluye información de contacto, deberá estar dividido en dos partes, en una se tendrá la información del sitio web como el motivante del desarrollo y el enlace al repositorio de github, y en la otra los contacto de los miembros del equipo con sus nombres y roles. La sección debe de estar en un tag <footer></footer>
