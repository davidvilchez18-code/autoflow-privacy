# Política de privacidad de InvitaFans — Reacciones de Facebook

**Última actualización:** 30 de octubre de 2026  
**Extensión:** InvitaFans — Reacciones de Facebook, versión 1.5.0  
**Responsable de la extensión:** desarrollador de GitHub [davidvilchez18-code](https://github.com/davidvilchez18-code)

## 1. Finalidad de InvitaFans

InvitaFans es una extensión de Chrome que ayuda a los administradores de páginas de Facebook a gestionar invitaciones para seguir sus páginas desde las listas de reacciones de sus publicaciones. Permite identificar los botones «Invitar», iniciar, pausar, reanudar y detener acciones de invitación, mostrar resultados y aplicar límites y descansos.

La extensión es independiente y no está afiliada, patrocinada ni respaldada por Meta o Facebook.

## 2. Información procesada

Para ofrecer su función, la versión 1.5.0 procesa:

- **Contenido visible en Facebook:** textos y estados de los botones de invitación, reacciones, nombres visibles y enlaces de perfiles que aparecen en la lista abierta por el administrador. Los nombres y enlaces se usan temporalmente en memoria para identificar registros y evitar acciones duplicadas durante la ejecución.
- **Actividad de la extensión:** número de intentos, confirmaciones observadas, contadores, marcas de tiempo, fechas de bloqueo y descansos. Estos registros se guardan en el almacenamiento local del perfil de Chrome mediante `chrome.storage.local`.
- **Estado de la pestaña activa:** información necesaria para localizar y operar sobre la ventana de reacciones abierta en Facebook o Meta Business Suite.

InvitaFans no solicita que el usuario entregue su contraseña de Facebook, números de tarjeta, información de salud ni datos crediticios.

## 3. Cómo se obtiene y utiliza la información

El código de la extensión se ejecuta en los dominios de Facebook declarados en su paquete (`www.facebook.com`, `web.facebook.com` y `business.facebook.com`). Las invitaciones se inician mediante una acción del administrador desde InvitaFans. La información se utiliza exclusivamente para identificar botones disponibles, gestionar los intentos, comprobar los cambios de estado visibles y aplicar las restricciones internas.

## 4. Almacenamiento, conservación y seguridad

Los contadores y marcas de tiempo se guardan **localmente en el perfil de Chrome**, no en una cuenta o servidor del desarrollador. El cálculo del cupo diario utiliza una ventana móvil de 24 horas; los contadores acumulados y ciertos estados pueden mantenerse hasta que se borren los datos de la extensión o se desinstale. Los nombres y enlaces de perfiles utilizados durante el recorrido no se incorporan al historial persistente de invitaciones de la versión 1.5.0.

La extensión no incorpora servicios propios de analítica, publicidad ni seguimiento externo. El acceso a datos del navegador está limitado a los permisos indicados en su manifiesto.

## 5. Comunicación y compartición de datos

La versión 1.5.0 **no contiene funciones destinadas a enviar el historial local de invitaciones ni los nombres de perfiles a servidores del desarrollador**. No vendemos datos personales ni los utilizamos para publicidad, evaluación crediticia u otros fines ajenos a la función descrita.

Cuando el administrador envía una invitación, Facebook/Meta procesa esa acción dentro de su plataforma. Ese tratamiento se rige también por la política de privacidad y las condiciones de Meta. InvitaFans no controla el tratamiento que realiza Meta. Google y GitHub pueden procesar datos propios de sus respectivos servicios cuando se usa Chrome Web Store o se consulta esta página, independientemente del funcionamiento de la extensión.

## 6. Permisos de Chrome

- **storage:** conservar localmente historial, contadores y bloqueos.
- **activeTab:** interactuar con la pestaña activa a solicitud del usuario.
- **scripting:** ejecutar archivos JavaScript incluidos en el paquete de la extensión.
- **notifications:** mostrar avisos sobre límites y bloqueos.
- **Acceso a sitios de Facebook:** identificar las listas de reacciones y estados de invitación únicamente en los dominios declarados.

## 7. Opciones del usuario

El administrador puede pausar o detener la actividad desde la interfaz. También puede desinstalar InvitaFans o borrar los datos almacenados por la extensión desde Chrome. Al hacerlo, se pueden eliminar sus contadores locales y su historial. Para consultas sobre el tratamiento de datos o solicitudes relacionadas con esta política, se puede contactar con el desarrollador mediante los [Issues de GitHub](https://github.com/davidvilchez18-code/autoflow-privacy/issues).

## 8. Menores de edad

InvitaFans está destinada a administradores de páginas, no es un producto diseñado para niños ni solicita que menores de edad proporcionen datos personales a la extensión.

## 9. Cambios de la política

Esta política describe la versión 1.5.0 examinada el 30 de octubre de 2026. Si se incorporan nuevas funciones que alteren la recogida, utilización, conservación o transmisión de datos, la política y las declaraciones de Chrome Web Store deberán actualizarse antes de distribuir dichos cambios.

## 10. Contacto

**Desarrollador:** [davidvilchez18-code](https://github.com/davidvilchez18-code)  
**Consultas:** [Abrir una consulta en GitHub](https://github.com/davidvilchez18-code/autoflow-privacy/issues)
