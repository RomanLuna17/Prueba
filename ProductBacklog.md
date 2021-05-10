# Product Backlog  
Las siguentes son las User Stories del Product Backlog.  
Estas se encuentran en forma de tarjeta, siendo la parte superior el statement de la User Storie y la parte inferior sus criterios de aceptación.

## Epicas  
| Como administrador quiero que al vender materiales se puedan distribuir de manera equitativa las ganancias y que se actualice el stock automaticamente. |
| ----------- |
| - Se debe mantener en todo momento un documento de stock actualizado por material, que contenga los datos de los trabajadores, sus ingresos de materiales y que se actualice con el ingreso o egreso de nuevos materiales. |
| - Se debe, al realizar una venta, decidir de forma justa a qué trabajador se le va a pagar por los materiales vendidos y de qué forma estos se van a restar del stock.|  

| Como ciudadano quiero solicitar a través de una página web la recolección de residuos para que puedan ser reciclados. |
| ----------- |
| - Se deben ingresar los datos personales del ciudadano y la franja horaria de disponibilidad. |
| - Se debe ingresar el tipo de materiales que se desean entregar, su volumen y de ser querido una foto. |
| - Se deben cancelar los pedidos que se encuentren fuera del área cubierta por los cartoneros de la cooperativa. |  

## User Stories
| Como administrador quiero tener un documento con el stock de cada material recolectado, para mantener organizados los materiales, su procedencia y luego venta. |
| ----------- |
| - Se debe crear un documento de tipo .exe por material recolectado por la cooperativa. El nombre debe ser: “Stock_Material”. |
| - Se debe tener en cada fila del documento la siguiente información: Id Cartonero, Nombre y Apellido, Teléfono de contacto, eMail, Última Entrega, Último Pago, Kilaje, Porcentaje del total. |
| - Se debe registrar además un cartonero con nombre “vecino buena onda”, cuya prioridad para cobrar por la venta de materiales será muy baja. |
| - Se debe tener al final el kilaje total disponible y un espacio para ingresar información sobre la última venta en caso de ser deseado. |  

| Como administrador quiero poder ingresar nuevos cartoneros a los documentos para poder mantener el stock actualizado de forma adecuada y justa. |
| ----------- |
| - Se deben ingresar todos los datos del nuevo cartonero y su primer entrega: Id Cartonero, Nombre y Apellido, Teléfono de contacto, eMail, Última Entrega, Kilaje. |
| - Se debe establecer la última fecha de pago como el día en que se lo inscribe, porque esto luego determinará la prioridad para cobrar. |
| - Se debe realizar el porcentaje de forma automática, actualizando el resto de porcentajes a su vez, junto con el kilaje total del material. |  

| Como administrador quiero que con cada ingreso mi stock se actualice automáticamente para poder tener mi stock organizado para la próxima venta. |
| ----------- |
| - Se debe poder decidir entre un nuevo cartonero o un cartonero ya inscripto. |
| - En todos los casos, el kilaje individual, total y el porcentaje de aporte se deben actualizar automáticamente. |  

| Como administrador quiero que se le dé una prioridad a cada cartonero para que en caso de venta, se tome material de los prioritarios y se reparta el pago de forma justa. |
| ----------- |
| - Se debe organizar la lista de prioridad según el último cobro, así de esta forma no pasa tanto tiempo sin que un un cartonero cobre por sus materiales. |
| - Cuando se deban restar materiales, se deben tomar del cartonero prioritario, actualizar la fecha de cobro y pasar al siguiente en la lista de prioridad hasta saciar la demanda. |  

| Como administrador quiero que con cada venta mi stock se actualice automáticamente para poder tener mi stock organizado para la próxima venta. |
| ----------- |
| - Se debe ingresar el kilaje de material vendido y del documento de stock de este material, se va a restar la cantidad vendida a el/los trabajadores con mayor prioridad.|
| - Se debe informar este kilaje restado a cada cada cartonero al administrativo para que este pague por los kilos aportados. |  

| Como administrador quiero tener un programa que me diga cuanto corresponde pagarle a cada cartonero por la venta realizada. |
| ----------- |
| - Se deben tener el kilaje total vendido, el monto total recibido y el mensaje automático que dice la cantidad de kilos tomada de cada cartonero. |
| - La ganancia del “vecino buena onda” debe ser dirigida a la cooperativa, esto debe ser notificado junto con el resto de los montos. |  

| Como ciudadano quiero llenar la planilla de inscripción con mis datos para que pasen a buscar mis residuos reciclables. |
| ----------- |
| - Se deben pedir los siguientes datos: Nombre, apellido, dirección y teléfono. |
| - En el caso que la distancia del lugar de retiro sea mayor a 6km del centro de acopio, el sistema deberá denegar la solicitud de recolección e informarle al ciudadano que lo acerque personalmente al centro de acopio. |  

| Como ciudadano quiero elegir la franja horaria de disponibilidad para que se retiren los residuos. |
| ----------- |
| - Se debe dar la opción de horario de 9 a 12hs o 13 a 17hs. |  

| Como ciudadano quiero poder indicar el volumen de los materiales a recoger, para que los pase a buscar un vehículo con capacidad suficiente. |
| ----------- |
| - Se podrá elegir entre varias categorías: a) entra en una caja b) entra en el baúl de un auto, c) entra en la caja de una camioneta, d) es necesario un camión. |  

| Como ciudadano quiero poder subir una foto de los materiales, para que el cartonero o la administración puedan ver de qué se trata. |
| ----------- |
| - Se debe dar la opción de subir archivos .jpg, .gif y .png de hasta 1 Mb. |  


## Epicas

| Como administrador de la página quiero que se genere una lista diaria organizando los recorridos diarios de cada cartonero.|
| -------------------------------------------------------------------------------------------------------------------------- |
| - El sistema generará automáticamente el listado.                                                                          |
| - El listado será enviado al email de la secretaría de la cooperativa.                                                     |
| - Se deberá ser equitativo con todos los cartoneros registrados.                                                           |
| - No se deberá asignar de forma diaria a un cartonero más de lo que puede transportar en su vehículo.                      |
| - El total del recorrido de un cartonero no debe superar los 6km.                                                          |
| - En aquellos casos donde el volumen a retirar corresponde a la categoría “a”, solo se le deberá asignar a un              |
|   cartonero en caso de que el lugar de recolección quede en su camino a otras viviendas con categorías de volumen          |
|   mayores (es decir, “b”, “c” y “d”).                                                                                      |


| Como administrador quiero poder crear cuentas en el sistema para poder agregar, modificar y acceder a los datos.           |
| -------------------------------------------------------------------------------------------------------------------------- |
| - La página web debe contar con una sección de login o registro para las secretarias.                                      |


## User Stories

| Como sistema quiero que el listado automático se genere y envíe diariamente para poder organizar los recorridos del dia    |
| -------------------------------------------------------------------------------------------------------------------------- |
| - Por defecto, el listado se generará de lunes a viernes, a las 8am.                                                       |
| - El listado se enviará al mail de la secretaria.                                                                          |


| Como sistema debo tener en cuenta que no se deberá asignar de forma diaria a un cartonero más de lo que puede transportar en su vehículo.                                                                                                            |
| -------------------------------------------------------------------------------------------------------------------------- |
| - Una vez superada la capacidad de un determinado cartonero (indicada en el listado de cartoneros), el mismo ya no se      |
|  tiene en cuenta en las asignaciones de las recolecciones restantes en ese día.                                            |


| Como sistema debo tener en cuenta que el total del recorrido de un cartonero no debe superar una cierta distancia.         |
| -------------------------------------------------------------------------------------------------------------------------- |
| - Por defecto la distancia máxima será de 6km.                                                                             |
| - Incluye la vuelta hasta el depósito.                                                                                     |
| - En aquellos casos donde el volumen a retirar corresponde a la categoría “a”, solo se le deberá asignar a un cartonero    |
|   en caso de que el lugar de recolección quede en su camino a otras viviendas con categorías de volumen mayores            |
|   (es decir, “b”, “c” y “d”).                                                                                              |


| Como sistema debo incluir las direcciones no visitadas en el listado del dia siguiente.                                    |
| -------------------------------------------------------------------------------------------------------------------------- |
| - Los cartoneros informan que domicilios fueron visitados y cuáles no.                                                     |
| - Los no visitados tienen mayor prioridad en la lista del día siguiente.                                                   |


| Como administración quiero poder modificar la configuración de la generación automática.                                   |
| -------------------------------------------------------------------------------------------------------------------------- |
| - Se puede cambiar el mail al cual se envía el listado.                                                                    |
| - Se puede configurar la hora y los días en los que se genera el listado.                                                  |
| - Se puede cambiar la distancia máxima del recorrido de los cartoneros.                                                    |


| Como administrador quiero poder dar de alta una secretaria.                                                                |
| -------------------------------------------------------------------------------------------------------------------------- |
| - Se debe solicitar a la secretaria nombre de usuario, la contraseña y la confirmación de la contraseña y una clave        |
|   para que usuarios externos no puedan registrarse.                                                                        |
| - Se debe verificar que el nombre de usuario no exista                                                                     |
| - Se debe verificar que las contraseñas coinciden.                                                                         |


| Como administrador quiero poder permitir a la secretaria poder loguearse.                                                  |
| ---------------------------------------------------------------------------------------------------------------------------|
| - Se solicita a la secretaría el nombre de usuario y la contraseña.                                                        |
| - Se verifica que sean correctos.                                                                                          |



## Epicas

|Como ciudadano quiero ofrecer la recolección de residuos de otros usuarios para poder aprovechar mi espacio sobrante.       |
| -------------------------------------------------------------------------------------------------------------------------- |
| - Se deben solicitar datos al usuario.                                                                                     |
| - Se debe generar un post que solo incluirá (por motivos de privacidad) la zona geográfica (que se calculará a partir      |
|   de la dirección), el espacio disponible y el texto libre.                                                                |
| - Se debe enviar un email al ciudadano que generó la oferta de transporte con los datos de los postulantes.                |
| - Se debe permitir al ciudadano que generó la oferta aceptar o rechazar la postulación. En caso de aceptarla, los datos    |
|   previamente cargados del ciudadano que generó la oferta se enviarán al postulante para que puedan coordinar el viaje.    |
|   En caso de rechazarla, se enviará una notificación al postulante.                                                        |


## User Stories

| Como ciudadano quiero poder ingresar mis datos para poder coordinar con quien se postule                                   |
| -------------------------------------------------------------------------------------------------------------------------- |
| - Se debe solicitar : nombre, teléfono, email, dirección, espacio disponible y un espacio de texto libre.                  |
| - Se podrá poner un máximo de 25 dígitos en cada apartado excepto el texto libre.                                          |


| Como ciudadano quiero recibir solicitudes de postulantes para así poder ver sus datos y elegir.                            |
| -------------------------------------------------------------------------------------------------------------------------- |
| - Se deben recibir las postulaciones por Mail con los datos del postulante                                                 |


| Como ciudadano quiero poder aceptar/rechazar a los postulantes para así poder elegir la que me interese                    |
| -------------------------------------------------------------------------------------------------------------------------- |
| - En caso de aceptar al postulante se le enviará un mail con todos los datos de quien genero el post para coordinar.       |
| - En caso de rechazar al postulante, se le notificará con un mail.                                                         |

## Epicas

|Como administrador quiero tener una sección que explique cómo deben ser entregados los residuos                             |
| -------------------------------------------------------------------------------------------------------------------------- |
| - La sección debe tener una lista de todos los materiales que son aceptados                                                |
| - Debe explicarse de forma clara cómo son las condiciones de entrega de cada uno de los materiales                         |
| - Se debe poder modificar la lista de elementos materiales y sus condiciones de entrega en caso de ser necesarios          |

## User stories

|Como administrador quiero crear una lista en la cual especifique cuales son los materiales que cada uno de los ciudadanos puede reciclar en nuestro centro de acopio                                                                       |
| -------------------------------------------------------------------------------------------------------------------------- |
| - Se debe crear una lista que contenga los materiales aceptados                                                            |
| - Los materiales aceptados son: papel, cartón, envases plásticos, latas de conserva, tetrabrik, envases de aluminio y botellas de vidrio                                                                                |


|Como administrador quiero modificar la lista de los materiales que son aceptados para ser reciclados                        |
| -------------------------------------------------------------------------------------------------------------------------- |
|  - Se debe poder agregar o eliminar la lista de materiales que son aceptados por la farbica                                |


| Como administrador quiero tener un apartado en la página web donde se especifiquen las condiciones en las que deben ser entregados los materiales                                                                                    |
| -------------------------------------------------------------------------------------------------------------------------- |
| Se debe explicar de forma clara que condiciones deben tener los materiales al llegar al centro de acopio                   |
| Cada material tiene su propia condición de aceptación                                                                      |

## Epicas

| Como administrador quiero registrar el peso de todos los materiales recolectados                                           |
| -------------------------------------------------------------------------------------------------------------------------- |
| Se deben ingresar los datos del cartonero que arriba con los materiales                                                    |
| Cada uno de los materiales que llegan al centro deben ser clasificados según su tipo                                       |
| Se debe ingresar la cantidad (en kilos) de cada uno de los materiales que fueron recibidos                                 |

## User stories

| Como administrador quiero ingresar los datos de cada cartonero que llega al centro con sus materiales                      |
| -------------------------------------------------------------------------------------------------------------------------- |
| Se debe tener registro de los datos de cada cartonero que acerca sus objetos                                               |
| En caso de que el cartonero no esté registrado en el sistema, se debera ofrecer la posibilidad de registrarlo              |


| Como administrador quiero ingresar los datos de los materiales que fueron acercados al centro por un vecino                |
| -------------------------------------------------------------------------------------------------------------------------- |
| Existen objetos que son acercados al centro por vecinos que forman parte de una comunidad recicladora, estos objetos deben |
| ser registrados en el sistema, y deben imputarse a un vecino genérico denominado “vecino buena onda”                       |


| Como administrador quiero elegir la categoría de cada uno de los materiales que arriban al centro de acopio                |
| -------------------------------------------------------------------------------------------------------------------------- |
| Cada material que llega al centro (ya sea acercado por un vecino o por un cartonero) es separado y definido según su categoría |
| Cada tipo de material es pesado con una balanza con tecnología Bluetooth para guardar todos los pesos de los materiales obtenidos |
