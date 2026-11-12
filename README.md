# Política de privacidad de CREA Aventuras

**Última actualización: 12 de noviembre de 2026**

Esta política explica qué información usa la aplicación **CREA Aventuras** («la app») y cómo se protege. La app es publicada por **CREA Nicaragua** («CREA», «nosotros»). Para consultas, escribe a **tecnologia@creanicaragua.org**.

## 1. Resumen

- CREA Aventuras es una app educativa para **niñas, niños, adolescentes y jóvenes**, de Inicial a Secundaria, y para sus facilitadores.
- **No tiene cuentas, no muestra anuncios, no usa analítica ni rastreo publicitario, no tiene compras y no vende datos.**
- **No pide nombre, apellidos, correo, fotos, ubicación, contactos, cámara ni micrófono.**
- El apodo, el dibujo y los registros completos de estrellas y progreso se guardan **solo en la tablet**. El tutor opcional utiliza un resumen de aprendizaje (sección 4.2).
- Los juegos funcionan **sin internet**.
- Hay tres casos en que algo sale de la tablet, todos descritos en la sección 4: la **voz natural** y las **preguntas actualizadas** (solo con CREA Home), el **tutor con inteligencia artificial** (opcional, apagado por defecto y que solo se enciende con un **código de CREA**) y los **reportes** de una sugerencia de ese tutor.
- La app declara el permiso de **internet**, pero **no se conecta a ningún servidor** mientras nadie active el tutor con un código de CREA ni envíe un reporte. No lleva ninguna llave ni PIN dentro.

## 2. Información que se queda en la tablet

Se guarda en el almacenamiento privado de la app, al que otras apps no tienen acceso, y no entra en copias de seguridad. **Estos archivos completos no se envían.** Si se activa el tutor, se transmite un resumen de resultados y una huella del identificador de instalación, como explica la sección 4.2; los reportes pendientes se envían según la sección 4.3.

**De cada perfil** (se elimina al borrar ese perfil: cada persona puede borrar el suyo desde Inicio → Perfiles, y el facilitador puede borrar cualquiera):

- el **apodo** y un **dibujo (avatar)** que cada persona elige (no se pide ni se guarda el nombre real);
- las **estrellas, niveles, logros** y los **resultados de la evaluación inicial**;
- cuántas veces se acierta cada pregunta, para repasar lo que cuesta más;
- la etapa de juego y el último tema de la sopa de letras;
- si el tutor con inteligencia artificial está activado en ese perfil y, en ese caso, una **nota de confirmación**: la fecha en que un facilitador lo activó y la versión de esta política. La nota no dice quién lo activó.

**De la tablet, no de un perfil** (no se elimina al borrar un perfil; se elimina al desinstalar la app o al borrar sus datos desde los ajustes de Android):

- la lista de perfiles y cuál está en uso, y el progreso del perfil **Invitado** (un facilitador puede reiniciarlo en Ayuda);
- audios de voz natural ya descargados, para no pedirlos otra vez (solo con CREA Home);
- los **reportes de sugerencias** del tutor que aún no se pudieron enviar (sección 4.3): el texto reportado y el motivo, sin datos del perfil;
- si la tablet se activó con un código de CREA (sección 3): el **token de activación** que entrega el servidor, el **PIN de facilitador** que creó la persona (guardado con sal y un cifrado irreversible, nunca en claro), el número de intentos fallidos del PIN y un **identificador al azar de la instalación** (sección 4.2). De este identificador y del token sí se envía algo cuando se usa el tutor.

## 3. Activación con un código de CREA

**Sin activar** (el caso normal), la app no se conecta a ningún servidor: los juegos, los perfiles, la evaluación y la ruta de aprendizaje funcionan solo en la tablet. Con **CREA Home**, otra app de CREA que tienen sus tablets, la app solo se comunica con ella, después de comprobar su firma (sección 4.1).

Para usar el **tutor con inteligencia artificial** sin CREA Home hace falta un **código de activación que da CREA** (a una familia, un centro o un grupo). Un facilitador lo escribe en Ayuda → «Tengo un código»:

- La app envía por internet, de forma cifrada (HTTPS), al servidor de CREA: **el código** y **la huella de un identificador al azar** que crea en esa instalación (no sale del aparato: no es el IMEI, el número de serie ni el identificador de publicidad).
- El servidor responde con un **token de activación**, ligado a esa tablet, que vence a los 90 días o antes. Si CREA **revoca** el código, el token deja de valer y el tutor se apaga solo.
- El servidor guarda por cada código: la etiqueta que le puso CREA, cuántas tablets puede usar, su vencimiento y su estado; y por cada tablet, la huella del identificador y la fecha. **No guarda el código en claro** ni la dirección IP (solo cuenta intentos para frenar abusos).
- La persona **crea su propio PIN de facilitador** (4 a 8 números), que se guarda en la tablet con sal y cifrado irreversible. Abre el modo facilitador: se cierra solo a los 15 minutos y al salir de la app; solo cambia lo que se ve (guía de los juegos, etapa, perfiles, tutor) y no concede permisos del sistema. CREA no puede recuperar el PIN: si se olvida, se quita la activación y se vuelve a empezar.
- **Quitar la activación** (en el modo facilitador) borra de la tablet el token y el PIN. Los perfiles y el progreso no se tocan.

La activación no activa el tutor por sí sola: después, un facilitador debe activarlo perfil por perfil (sección 4.2).

## 4. Información que sale de la tablet

Solo en estos tres casos.

### 4.1 Con CREA Home: preguntas, modo facilitador y voz natural

CREA Aventuras puede pedirle a CREA Home:

- **Preguntas actualizadas** por CREA (de un catálogo editado por docentes). La app no envía nada para recibirlas.
- **Si el facilitador activó su modo** en CREA Home con su PIN.
- **Voz natural:** el texto de una pregunta, una pista, una palabra o una historia de la app (contenido educativo, no escrito por la persona) se envía a través de CREA Home al servidor de CREA y a un proveedor de voz para generar el audio.

### 4.2 Tutor con inteligencia artificial (opcional)

El tutor propone una ruta de tres actividades de la app. La escribe **Claude, un sistema de inteligencia artificial de la empresa Anthropic**, no una persona, y la app lo indica junto a la ruta.

**Cuándo se usa.** Solo si se cumplen todas estas condiciones: el perfil no es el Invitado; el perfil hizo la evaluación inicial; un facilitador, con el modo facilitador abierto, lo activó para ese perfil después de leer un aviso con lo que se envía. CREA pide a sus facilitadores activarlo únicamente cuando la familia lo autorizó. **La app no comprueba ni guarda esa autorización**: solo anota en la tablet la fecha de la activación. Cuando esta política cambia, la app **desactiva el tutor en los perfiles que lo tenían activado** con la política anterior, sin borrar su progreso, y no vuelve a enviar nada de ese perfil hasta que un facilitador lo active de nuevo.

**Qué se envía** cada vez que se pide una ruta:

- un **resumen de aprendizaje del perfil**: para cada actividad posible, el juego, la etapa, el nivel, cuántas partidas recientes hay (hasta 3) y el porcentaje de acierto en ellas, junto con textos fijos de la app (el objetivo del juego y el motivo de la sugerencia);
- el **token de activación** y un **código de la tablet** (la huella del identificador al azar de la instalación, que no se obtiene del aparato ni de un perfil). Con CREA Home, el código de la tablet lo pone el sistema de CREA y esta app no lo conoce;
- como en cualquier conexión por internet, el servidor y su proveedor de alojamiento reciben la **dirección IP** de la red desde la que se conecta la tablet.

**Qué no se envía:** el apodo, el dibujo, el identificador del perfil, las respuestas una por una, las fechas de las partidas ni datos de otros perfiles.

Este resumen **no lleva el nombre ni el apodo, pero no es anónimo en sentido estricto**: es un dato seudónimo. Va acompañado de un código que se repite en esa tablet, y describe el avance de una persona concreta de un grupo pequeño.

**A dónde va y qué se guarda.**

- El **servidor de CREA** (alojado en Render) recibe el resumen y el código, y reenvía solo el resumen a Anthropic. No guarda el resumen ni la respuesta. Guarda **contadores de uso**: cuántas consultas hizo cada tablet y cada código de activación cada día, para limitar a 30 por tablet y día y un tope diario por código, y totales diarios y mensuales del servicio. Los contadores diarios se borran solos a los 40 días aproximadamente y los mensuales, a los 400 días aproximadamente. El proveedor de alojamiento puede conservar registros técnicos de las conexiones según sus propias condiciones.
- **Anthropic** recibe el resumen (no el código de la tablet) para generar la ruta y lo trata según sus condiciones para clientes de su API.
- La respuesta (un texto corto y tres actividades de la app) se muestra en la tablet. La app descarta cualquier respuesta que no sean actividades de su propia lista.

**Cómo desactivarlo.** Un facilitador lo desactiva en Inicio → Mi ruta de aprendizaje → Opciones del tutor; al hacerlo se borra la nota de confirmación y la app deja de enviar el resumen de ese perfil. La familia puede pedirlo en cualquier momento escribiendo a CREA. Sin el tutor, o sin conexión, la ruta se calcula **en la propia tablet**.

### 4.3 Reportar una sugerencia del tutor

Junto a la ruta escrita por la inteligencia artificial hay un botón «Reportar esta sugerencia». Al usarlo, la app deja de mostrar esa sugerencia y envía a CREA, por el mismo camino que el tutor:

- el texto que escribió la inteligencia artificial y las tres actividades que eligió;
- el motivo que marcó la persona (ofensiva, no adecuada para la edad, o confusa o equivocada);
- la versión de la app.

No se envía el apodo, el perfil ni los resultados. El código de la tablet se usa solo para limitar los reportes a 5 por tablet y día y no se guarda con el reporte. El servidor de CREA conserva cada reporte unos 90 días para revisarlo.

Si en ese momento no hay cómo enviarlo, el reporte queda guardado en la tablet (hasta 20) y la app lo envía más adelante, al abrirse, aunque para entonces el tutor se haya desactivado. Con CREA Home, esto depende de que CREA Home admita el envío de reportes; mientras no lo admita y la tablet no esté activada con un código, los reportes permanecen en la tablet y no llegan a CREA.

## 5. Evaluación inicial y etapas

Al empezar, la app pregunta el grado o la edad y hace diez preguntas cortas de lectura y matemáticas para saber en qué etapa empezar. El resultado es un **punto de partida pedagógico, no una nota**, y se guarda solo en la tablet. Cada estudiante ve los juegos de su etapa.

## 6. Niñez y adolescencia

La app está dirigida a personas menores de edad. CREA la diseñó teniendo en cuenta la política de Familias de Google Play: no contiene anuncios, compras ni enlaces externos, no tiene funciones sociales y no pide datos de contacto. Lo que puede salir de la tablet es únicamente lo descrito en la sección 4; el tutor con inteligencia artificial está desactivado por defecto. El uso con estudiantes lo organiza CREA con las familias y los centros. Las familias pueden pedirle a CREA que desactive el tutor o que borre el perfil de una niña, un niño o un adolescente escribiendo a **tecnologia@creanicaragua.org**.

Esta política describe cómo funciona la app. No es una certificación de cumplimiento de ninguna ley.

## 7. Permisos del dispositivo

La app solicita un solo permiso de Android: **internet**, que solo se usa en los casos de la sección 4 (activar con un código, pedir la ruta del tutor de un perfil que lo tiene activado y enviar un reporte). No pide ubicación, cámara, micrófono, contactos ni almacenamiento. Para leer en voz alta se usa el motor de texto a voz que ya trae la tablet.

## 8. Información que no recopilamos

CREA no recopila nombres, datos de contacto, ubicación, identificadores de publicidad ni del aparato, datos de pago ni informes de errores a través de esta app, y no incluye bibliotecas de publicidad o analítica de terceros. Lo único que CREA recibe de la app es lo descrito en la sección 4.

## 9. Seguridad

Las comunicaciones con el servidor de CREA usan HTTPS. La app **no lleva dentro ninguna llave ni PIN**: el acceso al tutor depende de un token revocable que entrega el servidor, y el PIN de facilitador lo crea cada persona y se guarda en la tablet con sal y cifrado irreversible. Los datos de los perfiles permanecen en el almacenamiento privado de la app.

## 10. Tus opciones y derechos

### Cómo pedir que se borren los datos que CREA tiene

CREA solo tiene datos de la app cuando una tablet se activó con un código (sección 3) o cuando se usó el tutor o se envió un reporte (sección 4). Para pedir que se borren:

1. Escribe a **tecnologia@creanicaragua.org** con el asunto «Borrar datos de CREA Aventuras».
2. Indica el **nombre del grupo o centro** al que CREA dio el código (no hace falta el nombre de ninguna persona menor de edad) y, si lo tienes, la fecha aproximada de la activación.
3. CREA responde y borra lo que corresponda: el registro de esa tablet en el servidor (la huella del identificador y el token) y, si lo pides, revoca el código. No se puede identificar a una persona concreta, solo una tablet o un grupo.
4. **Qué se borra y qué se conserva:** los contadores de consultas se borran solos a los 40 días y los reportes de contenido a los 90 días; el registro de la tablet se borra al atender la solicitud. Los datos que están **solo en la tablet** (perfiles, progreso, PIN) no los tiene CREA: se quitan como se explica abajo.

### Qué puedes hacer tú en la tablet

- **Borrar un perfil:** Inicio → Perfiles → Borrar. Elimina de la tablet el apodo, el dibujo, el progreso, la evaluación y la nota del tutor de ese perfil. No elimina lo que es de la tablet y no del perfil (sección 2).
- **Quitar todo lo que hay en la tablet:** desinstalar la app o borrar sus datos en los ajustes de Android. Eso incluye el token de activación, el PIN de facilitador, el identificador al azar de la instalación, los intentos del PIN y los reportes pendientes.
- **Tutor con inteligencia artificial:** se desactiva como indica la sección 4.2, o se quita la activación de la tablet (sección 3).
- **Contadores de uso y reportes del servidor:** se borran solos en los plazos de las secciones 4.2 y 4.3. Están asociados al código de la tablet o a ningún código, no a un perfil ni a un nombre, por lo que CREA no puede buscarlos por persona.

Como CREA no guarda tu apodo ni tu progreso en servidores, no hay un expediente tuyo que podamos consultar o corregir por ti.

## 11. Cambios en esta política

Si cambia la forma de tratar la información, actualizaremos esta página y la fecha de «Última actualización». Los cambios importantes se avisarán también en la descripción de la versión.

## 12. Contacto

**CREA Nicaragua** — **tecnologia@creanicaragua.org** — **https://www.creanicaragua.org**
