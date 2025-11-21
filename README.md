# Resumen del sistema Agenda personal de citas
## Descripcion del caso

La Agenda Personal de Citas es una herramienta pensada para acompañarte en tu rutina diaria y ayudarte a mantener todo bajo control sin complicarte la vida. Con ella puedes organizar tus compromisos, anotar pendientes y visualizar fácilmente cómo se distribuye tu tiempo. Además, te envía recordatorios para que no se te pase ninguna cita importante. En esencia, es una especie de asistente personal que te ayuda a mantenerte al día y a manejar tu tiempo de forma más tranquila y ordenada.



## Objetivos del sistema

Los objetivos del sistema se enfocan en garantizar que la aplicación cumpla su propósito principal: facilitar la gestión de citas de manera ordenada y eficiente. Para lograrlo, se establecen dos grupos de objetivos:

 Los objetivos del sistema: 
  
  * Lo que el sistema **"Debe hacer"** (Requisitos Funcionales - RF)
      Estos objetivos describen las acciones concretas que el usuario puede realizar dentro de la aplicación. Se centran en proporcionar herramientas prácticas y sencillas para registrar, consultar y gestionar citas de manera efectiva. Esto incluye funcionalidades como crear citas, editar horarios, recibir recordatorios, y ver un resumen de tus compromisos.
  * Las **"caracteristicas"** que debe cumplir (Requisitos No Funcionales - RNF)
     Aquí se detallan las cualidades que el sistema debe tener para garantizar una experiencia fluida, segura y agradable. Se incluyen aspectos como un buen rendimiento, fácil acceso desde diferentes dispositivos, protección de datos personales y una interfaz sencilla e intuitiva para que puedas usar la aplicación sin complicaciones.


## Requerimientos

### Requerimientos funcionales  (RF)
* **RF1 Registrar una nueva cita:** El usuario debe poder crear una cita, incluyendo detalles como la fecha, hora, descripción y ubicación.  
* **RF2 Visualizar citas programadas:** El sistema debe permitir al usuario ver todas sus citas en un calendario o lista organizada, de manera que pueda fácilmente revisar sus compromisos.
* **RF3 Recibir notificaciones de recordatorio:** El sistema debe enviar notificaciones (por ejemplo, en forma de alertas o recordatorios) para avisar al usuario con antelación sobre citas programadas.
* **RF4 Editar o eliminar citas existentes:** El usuario debe poder modificar o eliminar citas previamente registradas de manera fácil y rápida.



### Requerimientos no funcionales (RNF)
* **RNF1 Interfaz intuitiva:** La aplicación debe contar con una interfaz fácil de usar, sin necesidad de manuales complicados. El diseño debe ser claro y accesible para usuarios con distintos niveles de habilidad tecnológica.
* **RNF2 Rendimiento y tiempo de respuesta:** El sistema debe responder rápidamente a las acciones del usuario, con tiempos de carga y respuesta no mayores a 2 segundos en la mayoría de las interacciones.
* **RNF3 Seguridad de los datos:** La aplicación debe garantizar la protección de la información personal del usuario mediante cifrado de datos y medidas de seguridad que prevengan accesos no autorizados.

## Casos de prueba

* **CP1**

   * Tipo: Unitario
   * Requerimiento: RF1
   * Datos: Usuario ingresa la fecha y la hora de la cita
   * Resutado esperado: La cita queda registrada y se programa un aviso previo
   * Resultado obtenido: Exito


* **CP3**

  * Tipo: Unitario
  * Requerimiento: RF2
  * Datos: Usuario ingresa datos de la cita programada
  * Resutado esperado: Aparece cita con todos los horarios 
  * Resultado obtenido: Exito


* **CP4**

  * Tipo: Validacion
  * Requerimiento: RNF2
  * Datos: Acciones realizadas por el usuario
  * Resutado esperado: Rapidez al tener distintas acciones o procesos
  * Resultado obtenido: Exito


* **CP5**

  * Tipo: Validacion
  * Requerimiento: RF3
  * Datos: Ingresa hora para la notificacion del recordatorio
  * Resutado esperado: Deber llegar la notificacion a la hora acordada
  * Resultado obtenido: Exito


## Tipos de propuesta de mantenimiento 

* **Problema:** Algunos usuarios experimentan dificultades al intentar iniciar sesión en la aplicación con sus credenciales, a pesar de que las contraseñas y nombres de usuario son correctos.
 
 
  * **Tipo de Mantenimiento:** Mantenimiento correctivo
  * **Accion:** Investigar y solucionar posibles problemas en el proceso de autenticación, como errores en la verificación de contraseñas o fallos en la base de datos que impiden que los usuarios accedan a sus cuentas.
  * **Justificacion:** Es fundamental garantizar que los usuarios puedan acceder a sus cuentas sin problemas, ya que el acceso sin interrupciones es una de las funciones básicas y esenciales de la aplicación.


* **Problema:** La interfaz de usuario no se adapta correctamente en dispositivos con pantallas más pequeñas, como teléfonos de gama baja o tablets.
  

 
  * **Tipo de Mantenimiento:** Mantenimiento Perfectivo
  * **Accion:** Rediseñar la interfaz de usuario para hacerla más responsiva, asegurándose de que se ajuste correctamente a diferentes tamaños de pantalla y dispositivos, optimizando la experiencia en dispositivos móviles.
  * **Justificacion:** Mejorar la compatibilidad de la interfaz con una variedad de dispositivos es clave para aumentar la accesibilidad y asegurar que todos los usuarios, independientemente de su equipo, puedan usar la aplicación de forma cómoda y eficaz.


## Reflexion sobre el control de versiones 

El control de versiones es una herramienta clave para llevar un registro organizado del desarrollo de un proyecto. Gracias a él, podemos ver qué cambios se han hecho, solucionar problemas rápidamente, y si algo sale mal, revertir a una versión anterior sin perder información importante.

Publicar el proyecto en plataformas como GitHub agrega aún más beneficios. No solo tenemos un respaldo seguro del código, sino que también facilita el trabajo en equipo. Gracias a las ramas, podemos experimentar con nuevas ideas sin que afecten al código principal, y cada vez que se hace una actualización, queda registrada de manera clara y accesible. Esto permite tener un control total sobre el proyecto, asegurando que crezca de forma ordenada y sin complicaciones.
