---
layout: default
title: Registro de cambios
navegacion:
  contenido:
    - nombre: "Pendiente de liberación"
      link: "registro-cambios#pendiente-de-liberación"
  versiones:
    - nombre: "2025.12.26"
      link: "registro-cambios#20251226"
    - nombre: "2025.09.29"
      link: "registro-cambios#20250929"
    - nombre: "2025.07.17"
      link: "registro-cambios#20250717"
    - nombre: "2025.06.13"
      link: "registro-cambios#20250613"
    - nombre: "2025.05.21"
      link: "registro-cambios#20250521"
    - nombre: "2025.04.28"
      link: "registro-cambios#20250428"
    - nombre: "2025.03.27"
      link: "registro-cambios#20250327"
    - nombre: "2024.12.13"
      link: "registro-cambios#20241213"
    - nombre: "2024.10.03"
      link: "registro-cambios#20241003"
    - nombre: "2024.02.06"
      link: "registro-cambios#20240206"
    - nombre: "2023.12.27"
      link: "registro-cambios#20231227"
    - nombre: "2023.10.27"
      link: "registro-cambios#20231027"
    - nombre: "2023.09.19"
      link: "registro-cambios#20230919"
    - nombre: "2023.06.30"
      link: "registro-cambios#20230630"
    - nombre: "2023.05.25"
      link: "registro-cambios#20230524"
    - nombre: "2023.04.21"
      link: "registro-cambios#20230421"
    - nombre: "2023.04.04"
      link: "registro-cambios#20230404"
    - nombre: "2023.02.27"
      link: "registro-cambios#20230227"
    - nombre: "2023.02.02"
      link: "registro-cambios#20230202"
    - nombre: "2022.12.27"
      link: "registro-cambios#20221227"
    - nombre: "2022.11.29"
      link: "registro-cambios#20221129"
    - nombre: "2022.10.27"
      link: "registro-cambios#20221027"
    - nombre: "2022.10.06"
      link: "registro-cambios#20221006"
    - nombre: "2022.09.13"
      link: "registro-cambios#20220913"
    - nombre: "2022.08.26"
      link: "registro-cambios#20220826"
    - nombre: "2022.07.29"
      link: "registro-cambios#20220729"
    - nombre: "2022.06.29"
      link: "registro-cambios#20220629"
    - nombre: "2022.05.06"
      link: "registro-cambios#20220506"
    - nombre: "2022.04.04"
      link: "registro-cambios#20220404"
    - nombre: "2022.03.02"
      link: "registro-cambios#20220302"
    - nombre: "2022.01.27"
      link: "registro-cambios#20220127"
    - nombre: "2021.12.17"
      link: "registro-cambios#20211217"
    - nombre: "2021.11.25"
      link: "registro-cambios#20211125"
    - nombre: "2021.11.03"
      link: "registro-cambios#20211103"
    - nombre: "2021.10.19"
      link: "registro-cambios#20211019"
    - nombre: "2021.10.07"
      link: "registro-cambios#20211007"
    - nombre: "2021.09.07"
      link: "registro-cambios#20210907"
    - nombre: "2021.08.20"
      link: "registro-cambios#20210820"
    - nombre: "2021.07.29"
      link: "registro-cambios#20210729"
    - nombre: "2021.07.07"
      link: "registro-cambios#20210707"
    - nombre: "2021.06.18"
      link: "registro-cambios#20210618"
    - nombre: "2021.04.21"
      link: "registro-cambios#20210421"
    - nombre: "2021.03.04"
      link: "registro-cambios#20210304"
    - nombre: "2021.02.12"
      link: "registro-cambios#20210212"
    - nombre: "2021.01.11"
      link: "registro-cambios#20210111"
    - nombre: "2020.12.22"
      link: "registro-cambios#20201222"
    - nombre: "2020.12.04"
      link: "registro-cambios#20201204"
    - nombre: "2020.11.20"
      link: "registro-cambios#20201120"
    - nombre: "2020.10.26"
      link: "registro-cambios#20201026"
    - nombre: "2020.09.30"
      link: "registro-cambios#20200930"
    - nombre: "2020.08.31"
      link: "registro-cambios#20200831"
    - nombre: "2020.08.04"
      link: "registro-cambios#20200804"     
---
{% include navegacion.html %}
{% include navegacion-contenido.html %}
# Registro de cambios
---
En este archivo se documentaran todo los cambios notables liberados en cada versión.

El formato esta basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/), y para el nombre de versión se utiliza la fecha de lazamiento de la misma en el formato **AAAA.MM.DD**.

## Pendiente de liberación
---

## 2025.12.26
---

### Agregado

- [Maestros] - Ticket #4118 - Se agrega modulo de recorridos logísticos.
- [Maestros] - Ticket #3804 - Se agrega migrador excel de proveedores.
- [Maestros] - Ticket #3925 - Se agregar filtro de rubro y subrubro en modulo de productos.
- [Deposito] - Ticket #4228 - Se agrega modulo de solicitud de cambio de estado.
- [Deposito] - Ticket #3872 - Se agrega modulo de cruce de stock.
- [Integraciones] - Ticket #4166 - Se agrega monitor de solicitudes de cambios de estado.
- [Integraciones] - Ticket #4166 - Se agrega monitor de informes de solicitudes de cambios de estado.
- [Integraciones] - Ticket #4166 - Se agrega monitor de informes de cambios de estado.
- [General] - Seguridad - OWASP - 4. FileUpload sin validar Content-Type real
- [General] - Seguridad - OWASP - 9. Cookies sin HttpOnly y Secure
- [General] - Seguridad - OWASP - 10. Session timeout muy largo.
 
### Modificado

- [Maestros] - Ticket #4118 - Se mueve el modulo de tipos de viaje al menú de Gestión Operaciones
- [Maestros] - Ticket #4118 - Se renombra el modulo de Gestión Costo Transporte a Gestión Financiera
- [Maestros] - Ticket #4118 - Se modifica el modulo de cubo tarifario (tarifa) para que tenga un campo que indique si el cubo tarifario es de Costo o de Venta.
- [Maestros] - Ticket #4118 - Se modifica el modulo de cubo tarifario (tarifa) para que la solapa de Vigencias no se muestra si se esta creando el cubo tarifario
- [Maestros] - Ticket #4118 - Se modifica el modulo de cubo tarifario (tarifa) para que al crear detalles seleccione el recorrido del maestro de recorridos logísticos.
- [Maestros] - Ticket #4118 - Se agrega mensaje de advertencia en carga de detalles en cubo tarifario para que si no se indica una cantidad base en 0, advierta al usuario que la valorización no será tomada cuando el valor sea menor a la cantidad base.
- [Maestros] - Ticket #4118 - Se modifica dentro del cubo tarifario el nombre de la acción Copiar Recorridos por Actualizar Recorridos
- [Maestros] - Ticket #4040 - Se agrega validación en eliminación de sectores para que no permita eliminar con tipos de viajes asignados.
- [Maestros] - Ticket #4040 - Se modifica eliminación de tipos de viaje para que elimine también la relación con sectores.
- [Deposito] - Ticket #3806 - Se refactoriza visualizacion de recepciones en el modulo de recepciones para poder mostrar las cantidades recibidas, pendientes y anuladas.
- [Deposito] - Ticket #4260 - Se corrige bug en alta el pedido ya que si el centro emisor no tiene los 0 adelante no cargaba las unidades y los tiems en la cabecera.
- [Deposito] - Ticket #4259 - Se modifica modulo de recepción para poder cambiar de forma masiva las unidades de medida en la que se recibirán los productos.
- [Deposito] - Ticket #4392 - Se agrega posibilidad de asignar un vehiculo al momento de realizar la lista de envio.
- [Deposito] - Ticket #4358 - Se modifica reporte de informe de pedido detallado para que el codigo de producto este separado de la descripcion.
- [Deposito] - Ticket #4329 - Se agrega filtro de darsena en modulo de pedidos.
- [Deposito] - Ticket #4329 - Se corrige consulta de stock/inventario para que muestren bien la cantidad de ubicaciones.
- [Deposito] - Ticket #43911 - Se corrige carga de recepciones para que indique detalladamente que linea de producto tiene inconsistencias.
- [Deposito] - Ticket #3872 - Se adapta modulo de Stock para que permita consultar por fecha.
- [Distribucion] - Ticket #4072 - Se corrige listado excel de liquidacion de viajes para que muestre los valores de medias de los comprobantes y no los del viaje.
- [Distribucion] - Ticket #4220 - Se corrige accion de resolucion y requerir resolucion de comprobante para que guarde en la etapa el usuario que realizo la acción.
- [Distribucion] - Ticket #865 - Se modifica proceso de devolución para que si esta devolviendo al wms y existe el pedido preparador que actualice las unidades devueltas.
- [General] - Se actualizan todos los proyectos para que trabaje con el ultimo framework 

## 2025.09.29
---

### Agregado

- [Integraciones] - Ticket #4166 - Se agrega monitor de integraciones de tipos de recepcion.
- [Integraciones] - Ticket #4166 - Se agrega monitor de integraciones de importacion de motivos de devolucion.
- [Integraciones] - Ticket #4166 - Se agrega monitor de integraciones de importacion de rubros.
- [Integraciones] - Ticket #4166 - Se agrega monitor de integraciones de importacion de subrubros.

### Modificado

- [Maestros] - Ticket #3990 - Se modifica maestro de almacenes para que obligue a ingresar un ordenamiento para el global de preparación.
- [Maestros] - Ticket #3932 - Se corrige eliminación de empresas de transporte para que al momento de validar si tiene choferes o vehículos asignados no tenga en cuenta los que ya están dados de baja.
- [Maestros] - Ticket #3932 - Se corrige listado de empresas de transporte para que solamente liste las seleccionadas.
- [Maestros] - Ticket #3932 - Se corrige listado de documentaciones de empresas de transporte, choferes y vehículos para que muestre correctamente las documentaciones.
- [Maestros] - Ticket #3965 - Se agregan filtros de categorias de ubicacion, picking y reposicion en filtro de maestro de productos.
- [Maestros] - Ticket #3993/#4103 - Se agrega en maestro de clientes plantilla de muelle y darsena por defecto para poder asignar automaticamente en importador excel y carga manual de pedidos.
- [Maestros/Turnos] - Ticket #3942 - Se agrega en maestro de clientes la parametrizacion para indicar si solicita un vale de recepcion al momento de crear un turno de descarga. 
- [Deposito] - Ticket #4021 - Se agregan indicadores de peso, volumen y valor declarado en la pantalla de preparación automática de pedidos.
- [Deposito] - Ticket #4053 - Se corrige verificador de stock en preparacion de pedidos para que permita mostrar el lote y la serie.
- [VITA] - Ticket #3376 - Se cambia nombre de sistema de liquidacion por VITA.
- [VITA] - Ticket #3376 - Se cambia nombre de modulo tarifa por Cubo Tarifario.
- [VITA] - Ticket #3376 - Se cambian labels para adaptarse a nuevos terminos (Cubo Tarifario, Vigencia Desde, Cantidad Base, Precio Base, Precio Excedente).

## 2025.07.17
---

### Agregado
- [Deposito] - Se agrega proceso de reposicion automatica.
- [Deposito] - Se agrega modulo de generación de etiqueta de bulto vacía.
- [Deposito] - Se agrega impresion al momento de generar el vale de recepcion.

## 2025.06.13
---

### Agregado

- [APIs] - Se agregan apis del sistema de distribucion -> Comprobantes, Viajes y Retiros.
- [Deposito] - Se agrega acción de edición masiv-a de ubicaciones.
- [Deposito] - Se agrega acción de edición masiv-a de ubicaciones.
- **`[RojoSoft]`** - Se agregan integraciones con RojoSoft
- **`[Ninoshka]`** - Se agregan integraciones .Net con AS400.
- **`[Calico]`** - Se agrega integracion de Makita escaneando master series.

### Modificado

- [Sistemas Brainsys] - Se modifican todos los sistemas de Brainsys para que validen que si un usuario no esta activo no le permitan loguearse.
- [Maestros] - En el modulo de productos se limita la cantidad de caracteres del codigo a 15 caracteres.
- [Maestros] - Se adaptan migradores de empresas de transporte, choferes y vehiculo para que se le asigne la documentacion correspondiente segun la regla de documentacion.
- [Maestros] - Se corrige migrador de empresas de transporte para que se le asignen las sucursales a las que tiene permiso el usuario.
- [Maestros] - Se corrige migrador de chofer para que permita asignar el tipo de registro de conducir por el codigo y no el id interno de la base de datos.
- [Deposito] - Se modifica el modulo de recepcion para permitir agergar un nuevo lote en el momento de la recepcion.
- [Deposito] - Se corrigen filtros de ubicaciones en modulos de confirmaciones de recogida y almacenaje.
- [Deposito] - Se modifica filtro de lote en modulo de informe de recepciones para que se pueda filtrar el lote sin necesidad de ingresar un producto.
- [Distribucion] - Se agrega filtro de kilogramos en filtros de comprobantes de entrega y comprobantes dentro del muelle.
- [Distribucion] - Se modifica modulo de adicionales para que no permita asignar adicionales a clientes que no se encuentran dentro del viaje.
- [Turnos] - Se corrige modulo de disponibilidad ya que por momentos mostraba un error que no permitira obtener los dias de la semana para calcular el calendario.
- [Turnos] - Se corrige modulo de turnos para que muestre bien el remitente y para que permita ordena por fecha y hora.
- [APIs] - Se actualizan apis estandar para que utilicen el deposito.
  
## 2025.05.21
---

### Agregado

- [Deposito] - Se agrega modulo de asignación de zonas de recuento a ubicaciones.

### Modificado

- [Maestros] - Se corrige filtro de usuarios para que valide bien el filtro de rol.
- [Maestros] - Se corrige edicion de remitentes para que visualice el cliente y la provincia.
- [Turnos] - Se modificaron los estados por defecto del sistema para que se permitan visualizar en los modulos de seguimiento de turnos de carga y seguimiento de turnos de descarga.
- [Turnos] - Se refactorizo la impresion de descarga agregando la hora del turno y corrigiendo el bug que no permitia mostrar muchos detalles del turno.

## 2025.04.28
---

### Agregado
- [Deposito] - Se agrega modulo de inventario.
- [Deposito] - Se agrega ABM de contenedores.
- [Deposito] - Se agrega ABM de regla de reposicion.
- [Monitor Integraciones] - Se suben monitor de integraciones de Cancelacion de Pedidos.
- **`[Logarte]`** - Se suben integraciones con RustOleum.
- **`[Bronzen]`** - Se suben integraciones con SfgGestion.
- **`[Dada]`** - Se generan integraciones con Peugeot, Fiat y Logitex.
- **`[Urbano]`**: Se suben integraciones de informe de cambios de estado via mail.
- **`[SouthPost]`**: Se suben integraciones de informes de pedido con su tms.

### Modificado
- [Deposito] - Ubicaciones: Se corrige asignacion de permanentes para que valide que la ubicacion no sea multiple producto ni tenga otro producto en stock.
- [Deposito] - Informes Recepciones: Se agregar filtro de estado de recepcion.
- [Deposito] - Consulta de stock: Se corrige ordenamiento por lote ya que no estaba funcionando. El ordenamiento quedo por fecha de vencimiento.
- [Sistema Digitalizacion] - Se finaliza sistema de digitalización.

## 2025.03.27
---

### Agregado
- [Deposito] - Inventario : Se genera modulo de inventario.
- [Deposito] - Bultos : Se genera modulo de consulta de trazabilidad de bultos con impresiones de rotulos.
- [Deposito] - Modulos : Se suben mejoras en los modulos del sistema.
- [APIs] - : Se genera sistema de APIs.
- **`[Klo]`**: Se agregan integraciones con LG.

## 2024.12.13
---

### Agregado
- [Distribucion] - Viajes: Se genera funcionalidad de cierre administrativo del viaje.
- [Deposito] - Modulos : Se suben mejoras en los modulos del sistema.
  
## 2024.10.03
---

### Agregado
- Se genera sistema de digitalización de comprobantes.
- Se genera sistema de reportes de PowerBI.

### Modificado
- Se realiza separación de los sistemas, separando los modelos en soluciones propias (1 solución por cada modelo) y separando las presentaciones en soluciones propias (1 solución por cada sistema). 
- Se normalizan sistemas y modelos para que todos centralicen sus maestros en el sistema de maestros.

## 2024.02.06
---

### Agregado
- Nomencladores: Se agrega migración de datos y descargar de registros en Excel.
- Monitor Proveedores: Se agrega monitor de integraciones para los proveedores.
- Monitor Subclientes: Se agrega monitor de integraciones para los subclientes.
- Monitor Ordenes de Compra: Se agrega monitor de integraciones para las ordenes de compra.
- Configuracion: Se agrega configuracion interna en sistema de distribucion.
- Liquidacion Transportistas: Se agrega modulo de liquidacion de transportistas.

### Modificado
- Interfaz: Se refactoriza generacion de obtencion de id de proceso para que trabaje con una tabla de numerador.
- Clientes: Se agrega código de servicio a la grilla y al control de selección de servicios contratados.
- Servicios: Se agrega a la grilla principal que tipo de servicio es(deposito/distribucion).
- Comprobantes: Se agrega acción de documentación en pantalla de comprobantes del módulo conforme.
- Comprobantes: Se agrega al reporte estándar una columna con el teléfono del destino.
- Viajes: Se agrega validacion en inicio de viaje para que valide que el chofer, vehiculo o acoplado no se encuentre en otro viaje iniciado. Esta puede ser configurable mediante la configuracion del sistema de distribucion.
- **`[Calico]`**: Se agrega al reporte estándar y tráfico de Comprobantes una columna con el teléfono del destino.

## 2023.12.27
---

### Agregado
- Paises: Se agrega listado Excel y migrador.
- Provincias: Se agrega listado Excel y migrador.
- Localidades: Se agrega listado Excel y migrador.
- Clientes: Se agrega listado Excel y migrador.
- Remitentes: Se agrega listado Excel y migrador.
- Destinatarios: Se agrega listado Excel y migrador.
- Empresas de transporte: Se agrega listado Excel y migrador.
- Choferes: Se agrega listado Excel y migrador.
- Vehiculos: Se agrega listado Excel y migrador.

### Modificado
- Comprobantes: Se mueve la accion de Confirmar Llegada del modulo de recepcion al modulo de Conforme.
- Viajes: Se agregaron columnas al listado de liquidación.
- Viajes: En la grilla de viajes se modifica la columna de Valorización para que contemple el valor de los adicionales.
- Viajes: En el reporte de impresion de viajes se agrega en los valores del viaje los valores de los adicionales.
- Atención clientes: Se modifica formulario de etapas para que en la descripcion muestre el codigo y descripcion del tipo de justificacion/novedad/reclamo.
- Turnos: Se modifica modulo de turnos de carga para que permitan asignar pedidos existentes en el WMS.
- Turnos: Se modifica modulo de turnos de descarga para que permitan asignar recepciones existentes en el WMS.

## 2023.10.27
---

### Agregado
- Cancelación de pedidos: Se agrega integración estándar de SQL de cancelación de pedidos.
- **`[Urbano]`**: Se agregan integraciones con Urbano.
  
## 2023.09.19
---

### Agregado
- Comprobantes: Se agrega acción para poder confirmar la llegada a destino de un comprobante.

### Modificado
- Empresas de transporte: Se realiza refactor del modulo. Se agrega posibilidad de asignar documentacion y reporte excel de documentaciones operativas.
- Choferes: Se realiza refactor del modulo. Se agrega posibilidad de asignar documentacion y reporte excel de documentaciones operativas.
- Vehiculos: Se realiza refactor del modulo. Se agrega posibilidad de asignar documentacion y reporte excel de documentaciones operativas.
- Importador comprobantes excel: Se modifica para que la observación que se indica en el excel llegue a las observaciones del comprobante y no a las observaciones del destinatario del comprobante.
- Retiro: Se quita la validación para que permita crear un retiro de un cliente de contado.
- Retiro: Se modifica asignación de comprobantes a retiro para que en las etapas quede identificado a que retiro/comprobante según corresponda quedo asociado.
- Retiro: Se modifica grilla principal para que muestre los datos del transporte del viaje. En el caso que no tenga un viaje mostrara los datos del transporte asignado al retiro.
- Retiro: Se modifica reporte de impresión estándar para que muestre los datos del transporte del viaje. En el caso que no tenga un viaje mostrara los datos del transporte asignado al retiro. Además para que muestre los comprobantes asociados.
- Hojas de ruta: Se modifica reporte de impresión estándar para que ordene los comprobantes por cliente-letra-centroEmisor-número, para que tenga numeradas las filas de comprobantes y ademas se modifica leyenda duplicada de "Firma del Responsable" para que sea "Firma del Transportista".
- Hojas de ruta: Se modifica reporte de impresión por localidad para que tenga numeradas las filas de comprobantes.
- Planilla: Se corrige reporte de impresión para que muestre fecha de emisión y los totales de los comprobantes.
- Planilla: Se modifica proceso de transferencia para que deje en la etapa del comprobante y la planilla a que sector fue transferida en el caso de que haya sido transferida a otro sector.
- Planilla: Se agrega la accion para visualizar las etapas de una planilla.

## 2023.06.30
---

### Modificado
- Regla de valorización: Se corrige carga de regla de valorización ya que no mostraba correctamente el código de la tarifa al momento de editarla.
- Validación de comprobantes: Se refactoriza modulo de validación de comprobantes para que permita aplicar la configuracion por tipo de formulario y además se agrega parametrización por exigencia de importe y valor declarado.
- Comprobantes: Se agregaron datos de numeración de comprobantes y retiros a la tabla principal de comprobantes tblComprobante.
- Comprobantes: Se modifica control de selección de cliente en carga de comprobantes para que el evento a tomar el cliente lo haga al perder el foco del control y no al ir escribiendo en el código.
- Muelles: Se modifica el filtro de la grilla de comprobantes dentro de muelle para que por defecto solo tenga tildado los estados: Sin Confirmar, Confirmado, Recibido y Pendiente de entrega.
- Viajes: Se refactoriza carga de viajes desde comprobantes para que permita asignar retiros al momento de la carga del viaje.
- Almacenaje de comprobantes: Se refactoriza modulo de almacenaje.
- Conforme comprobantes: Para el conforme en sucursal destino se agrega la posibilidad de dejar el comprobante como conformado sin viaje.

## 2023.05.24
---

### Agregado:
- **`[Translog]`**: Se agregan integraciones con Whirlpool.

### Modificado
- Filtros: Se cambio el icono que aparece cuando acercamos el cursor a una barra de filtro para que en vez de estar el símbolo "prohibido" este el icono de una manito.
- Regla tipo adicional: Se corrige carga de regla de tipos de adicional para permitir indicar una sucursal para poder filtrar bien el sector. Ya que al tener sectores con mismo código pero distintas sucursales solo traía una.
- Importador Comprobantes: En la plantilla Excel por defecto que se baja en el modulo de importador de comprobantes se agregaron 3 hojas. Una para que muestre los datos solo de distribucion, otra con los datos de Wms y otra con los datos de turno.
- Importador Comprobantes: Se modifico importador para permitir que en el Excel se pueda indicar el tipo de comprobante que se quiere importar (Carta de Porte, Nota de devolución, Remito). Si no se indica un tipo, por defecto se utilizara el de remito para no afectar los Excel de cada cliente.
- Conforme de comprobantes: Se modifica formulario de conforme de comprobantes para que no habilite los botones de aceptar y cancelar hasta tanto no se haya cargado toda la pantalla.
- Formulario muelles: Se agrega en fila desplegable de muelles una etiqueta para ver la cantidad de comprobantes del muelle.
- Resolución de comprobantes: Se refactoriza formulario de resolución de comprobantes.
- Resolución de comprobantes: Se sube mejora en reemplazo de comprobantes para que en la etapa de los comprobantes muestre a que comprobante quedo asociado el reemplazo.
- Muelles: En la grilla de comprobantes del formulario de carga/edición de un muelle se agrego la acción de generar viajes con dichos comprobantes siempre y cuando esten en pendiente de entrega ya que genera un nuevo muelle y una hoja de ruta para los comprobantes.
- Comprobantes de entrega: Se agrego acción para generar viajes con comprobantes pendiente de entrega generando un nuevo muelle y una hoja de ruta para los comprobantes.
- Retiros: Se realiza refactor del circuito de retiros.
- Monitor interfaz recepciones Wms: Se agrega filtro por fecha de ingreso y ejecucion de proceso.
- Monitor interfaz pedidos Wms: Se agrega filtro por fecha de ingreso y ejecucion de proceso.

## 2023.04.21
---

### Agregado
- Atención Clientes: Se agrega reporte de trazabilidad en el modulo Atención al cliente/ Trazabilidad donde se mostrara un registro por cada novedad que tenga el comprobante.
- Consulta Stock Consolidado: Se agrega servicio web para consultar el stock consolidado por producto sin trabajar con posicion.

### Modificado
- Comprobantes: Se quita validacion en generacion de comprobantes para que permita crear un comprobante con un cliente contado.
- Muelles: Se corrige listado detallado en Excel para que muestre el transporte del viaje.
- Escáner comprobantes: Se modifica funcionalidad del escáner de comprobantes para que respete el filtro principal de la consulta donde se este utilizando.
- Web Services Recepcion: Se modificaron web services de asignacion de lineas de recepcion, desasignacion de lineas de recepcion y eliminacion de recepciones para que validen bien las lineas completas y ademas para que completen las tablas de vales anulados del WMS (MRAVALC, MRAVALD).
- **`[Brandlive]`**: Se corrige interfaz de informe de pedidos para que el nombre del archivo sea con el nombre definido en el archivo de configuracion mas el nombre original del archivo mas la extension definida en el archivo de configuracion.

## 2023.04.04
---

### Agregado
- Localidades: Se agrega reporte Excel de localidades.

### Modificado
- Servicios: Se agrega la posibilidad de indicar si es un servicio de distribución, de deposito o ambos.
- Servicios: Se agrega en servicios facturables la posibilidad de indicar fecha de vigencia y periodicidad y que estos datos en conjunto con los valores de prefacturación se asignen desde una acción.
- Clientes: Se modifica grilla de servicios contratados para que muestre que tipo de servicio es.
- Comprobantes: Se corrige carga de comprobantes para que valide ingresar una letra valida y no un caracter como letra del comprobante.
- Comprobantes: Se corrige carga de comprobantes para que valide que no se ingresen medidas menores a 0 (cero).
- Viaje: Se modifica grilla de viajes para que muestre el total del valor de los adicionales en la columna de adicionales.
- Viaje: Se modifica el modulo de viajes para que no permita asignar ni desasignar adicionales en viajes creados.
- **`[Merqui]`**: Se modifican procedimientos de facturador de recepción, preparación y almacenamiento diario para que el calculo de paletas lo realice sobre la parametrización del producto.
- **`[Calico]`**: Se refactoriza interfaz de InformeLineasRecibidas para que tenga un log y marque la orden como informada a Bianchi si desde Bianchi informan que la orden no existe ya que se entiende como que ya paso de estado.
- **`[Calico]`**: Se migra interfaz de ImportacionSubclientes para que trabaje con el nuevo codigo de integraciones.
- **`[Calico]`**: Se refactoriza interfaz de ImportacionPedidos para que permita dar de alta subclientes de Ecommerce.

## 2023.02.27
---

### Agregado
- Seguimiento rutas: Se agrega formulario de seguimiento de rutas para poder visualizar la geolocalización de los viajes iniciados con el sistema satelital de POINTER.
- Monitor interfaz: Se agregan en los procesos de interfaz de productos, recepciones, pedidos, informes de recepciones e informes de pedidos listados excel para poder obtener el detalle de los procesos.

### Modificado

- Carta de porte: Se agrega validación para que obligue a ingresar importe y valor declarado.
- Localidades: Se agrega mejora para que solo permita agregar localidades en formularios donde se seleccionan las localidades si el usuario tiene permisos para dar de alta localidades.
- Viajes: Se modifica formulario de impresión de liquidación para que se imprima el código de barra del número de viaje.
- Atencion clientes: Se modifica reporte excel de tracking para que muestre la columna del codigo del destinatario.
- **`[Calico]`**: Se modifica impresión estándar de comprobantes para que muestre el importe del comprobante.

## 2023.02.02
---

### Agregado
- Monitor recepciones: Se agrega acción para obtener listado de las recepciones seleccionadas.

### Modificado
- Gestión de cobranza: Se corrige orden de columnas de fecha de creación y estados.
- Rendición de gestión de cobranza: Se modifica reporte Excel de rendiciones para que muestre los datos del cobro de manera totalizada.
- Planilla de rendición de gestión de cobranza: Se agrega funcionalidad para poder imprimir la planilla al momento de generarla.
- Servicios facturables: Se agregaron campos para poder indicar que código de comprobante, servicio y campo de facturación debe asignar en el sistema de facturación SLIT.
- Liquidación: Se modifica la creación de planilla movimiento para que se pueda persistir el servicio del movimiento. Además se modificaron los procesos de obtencion de movimientos de preparacion y recepcion para que guarden la informacion en una tabla para poder trabajar el proceso de forma automática.

## 2022.12.27
---

### Agregado
- Justificaciones de comprobantes: Se agrega modulo de importación de justificaciones masivas vía Excel.
- Fechas de no entrega: Se agrega formulario de fechas de no entrega para el calculo del lead time.
- Gestion de cobranzas: Se agrega modulo de gestion de cobranza de comprobantes
- **`[Calico]`**: Se agrega reporte "Trafico", similar al estándar de comprobantes de recepción pero mostrando las novedades de los comprobantes.

### Modificado
- Importador Excel: Se agrega posibilidad de importar el importe de un comprobante / contra reembolso de un pedido.
- Localidades: Se realiza refactor de formulario.
- Tipos de viaje: Se corrige formulario para que respete los permisos asignados al usuario.
- Comprobantes: Se corrige formulario de carga de comprobantes para que permita agregar localidades, destinatarios y remitentes nuevos.
- Comprobantes: Se modifica reporte excel estandar para que muestr el importe y el numero de la gestion de cobranza.
- Facturador: Se agrega relación entre cliente y proveedores para que al buscar las recepciones de un cliente solo traiga las que corresponden a sus proveedores asignados.
- **`[Calico]`**: Se mejoran integraciones Emerson para que no se encadenen los procesos si alguno falla y se modifica estructura de temporal de pedidos de Emerson.
- **`[Klo]`**: Se modifica integración de informe de recepciones hacia Derco para permitir informar de forma parcial los vales.

## 2022.11.29
---

### Agregado
- Lead Time: Se agrega interfaz de actualizacion de fechas de entrega de comprobantes segun nomenclador comercial.
- Maestros Wms: Se agregan los maestros de emplazamiento, almacen, compañia y proveedores al Master para poder relacionarlos a los roles/usuarios y asi poder filtrar la informacion en los servicios web estandar de deposito.
- Importación Web Productos Wms: Se modifica integración de importación de productos para que quede registrada en el monitor de integraciones la ejecución y para que los códigos queden guardados en una tabla de relación y en el caso de que sean de mas de 15 caracteres se importen al Wms con un código de 15 caracteres.
- Importación Web Recepciones Wms: Se modifica integración de importación de recepciones para que quede registrada en el monitor de integraciones la ejecución.
- Importación Web Pedidos Wms: Se modifica integración de importación de pedidos para que quede registrada en el monitor de integraciones la ejecución.
- **`[Klo]`**: Se genera trigger de pedidos de asegurador para que se generen autmaticamente vales de recepcion en el almacen de aseguradora.

### Modificado
- Nomencladores: Se corrige filtro por plantilla de muelle y se agrega columna de plantilla de muelle.
- Comprobantes recepción: Se modifica filtro por defecto para que también traiga los comprobantes pendientes de entrega.
- Tipos de adicional: Se corrige carga, grilla y consulta para poder asignar, filtrar y visualizar correctamente la empresa de transporte.
- Hojas de ruta: Se modifica reporte de impresión por localidad para que muestre el valor declarado de los comprobantes.
- Destinatarios: Se corrige filtro de localidad, se permite editar la provincia y se quita validación obsoleta para permitir retiro de un destinatario contado.
- Turnado de comprobantes: Se modifica para permitir guardar en la etapa la nueva fecha y hora de turno.
- Clientes Se quita validación obsoleta para permitir asignar sucursales y tipos de formulario a clientes contado.
- Reglas de valorización: Se corrige carga, grilla y consulta para poder asignar, filtrar y visualizar correctamente el tipo de unidad. Ademas se ordena alfabéticamente el filtro de tipo de viaje.
- Planillas: Se modifica filtro de comprobantes para autocompletar la fecha de emisión con el primer día de la semana.
- Atención clientes: Se agrega búsqueda por escáner en formulario de comprobantes.
- Optimo Camino: Se agrega parametrización para permitir informar la descripcion del muelle en vez de la hoja de ruta.
- Optimo Camino: Se agrega parametrización para permitir informar una especialidad segun los agrupamientos del comprobante.
- Optimo Camino: Se modifica para informar como ventana horario la hora de turno.
- **`[Gestion Logistica SB]`**: Se modifican interfaces de informe de stock vía correo electrónico para que los productos se informen sin los 0 (cero) adelante.
- **`[Calico]`**: Se modifican interfaces de emerson para que tengan tabla de relacion de productos, lotes y series.

## 2022.10.27
---

### Agregado
- **`[Calico]`**: Se agregan interfaces de importacion e informe de pedidos y recepciones para la cuenta Emerson.
- **`[Eternal Software]`**: Se agrega interfaz de informe de paletas desde el WMS.
- **`[Eternal Software]`**: Se agrega interfaz de informe de comprobantes desde el TMS.

### Modificado
- Paradas: Se modifica maestro de paradas e importación de destinatarios y comprobantes para que no valide por nombre y numero de calle sino por domicilio completo.
- Viajes: Se agrega accion en grilla principal para permitir dar de alta las paradas inexistentes.
- Importacion pedidos SQL: Se modifican procedimientos almacenados de importacion de pedidos al WMS para que si el pedido ya existe en el WMS lo mande al historico.
- **`[Intralog]`**: Se modifica interfaz de informador de pedidos de S2GO para que informe las series preparadas. Ademas se agrega validacion para que si el producto maneja serie no se envie el informe hasta tanto las series hayan sidos confirmadas.

## 2022.10.06
---

### Agregado
- Pedidos Wms: Se agrega servicio web de carga de pedidos del wms para que permita crearlos directamente en la bolsa de picking.

### Modificado
- Valorizacion: Se refactoriza formulario de regla de valorizacion y se permite indicar a que cliente corresponde la regla, para que al momento de valorizar un viaje valide que los comprobantes/retiros de dicho viaje sean solo del cliente de la regla. 
- Tarifas: Se modifica para permitir asignar una descripcion a los recorridos.
- Hojas Ruta: Se corrige filtro de hojas de ruta para que permita obtener las hojas de ruta que puede visualizar el usuario.
- Facturador: Se modifica modulo de facturador para que se visualicen las cantidades por paletas según la parametrización del producto.
- Pedidos Wms: Se agrega propiedad de cantidad confirmada en los detalles de los pedidos del WMS para permitir informar la cantidad confirmada de los productos preparados.
- Importador Excel: Se modifica importador de excel de comprobantes para que si no se carga un remitente tome los datos de localidad y domicilio de origen de la sucursal.
- **`[Calyco Uruguay]`**: Se corrigio informe de pedidos de Marvisa para que genere el Excel con otra libreria ya que la actual le generaba errores al cliente.
- **`[Locksley]`**: Se corrigió informe de pedidos para que para que al informar las series no agrupe los detalles de la MSOPEDD porque sino hay series que no se informan.

## 2022.09.13
---

### Agregado
- **`[Klo]`**: Se agrega integracion 947.
- **`[Klo]`**: Se agrega integracion INVRPT.
- **`[Klo]`**: Se agrega integracion de recepciones no integradas (importacion e  informe).
- **`[Calyco Uruguay]`**: Se agrega importacion de pedidos de Marvisa.
- **`[Calyco Uruguay]`**: Se agrega informe de pedidos de Marvisa.

### Modificado
- Viajes: Se realiza refactor sobre modulos de viajes.

## 2022.08.26
---

### Agregado
- Interfaz comprobantes: Se agrego interfaz de anulación de comprobantes desde el WMS hacia el TMS.
- Hojas de ruta: Se agrego nuevo reporteo por Localidad para que ordene alfabéticamente los comprobantes por localidad.
- Atención Clientes: Se agrega funcionalidad para realizar turnado masivo de comprobantes.

### Modificado
- Comprobantes: Se agrego posibilidad de indicar una descripción al almacenar un comprobante desde recepción.
- Conforme: Se modifico proceso de observación y resolución de comprobantes para que por defecto muestre el estado recibido.
- Hojas de ruta: Se modifica grilla principal de hojas de ruta para que indique la cantidad de comprobantes que tiene asociado.
- Hojas de ruta: Se modifica grilla detallada de comprobantes para que muestre el destino del comprobante.
- Simulador de entrega: Se modifica grilla principal del simulador de entrega para que indique los metros cúbicos.
- Atención Clientes: En grilla de comprobantes se agrega columna de fecha de emisión.
- Atención Clientes: En grilla de comprobantes se agregan totales de comprobantes filtrados y seleccionados.
- Atención Clientes: En grilla de comprobantes se tildaron por defecto todos los estados posibles a filtrar.
- Atención Clientes: En las distintas acciones se modifico el combo de reclamo - justificacion - novedad para que permita filtrar por código y descripción.
- Login: Se modifica login para que el boton Ingresar solo se habilite cuando se carga el sector satisfactoriamente.
- **`[Esa Logistica]`**: Se agrega reporte particular de comprobantes para que imprima etiquetas por bultos.

## 2022.07.29
---

### Agregado
- Presentacion Deposito: Se genera solucion para realizar la presentacion web del sistema deposito (wms).
- Paradas: Se genera el maestro de paradas.
- Valorizacion: Se genera valorizacion por parada.
- Argontech: Se genera integracion con Argontech para marcar como digitalizado un comprobante en TMS.
- Informe Sms: Se agrega integracion de informe de SMS.

### Modificado
- Comprobantes: Se modifica para permitir indicar una parada.
- Retiros: Se modifica para permitir indicar una parada.
- Destinatarios: Se modifica para permitir indicar una parada.
- Importador: Se modifica importador de recepciones para que si algún lote en el WMS lo genere automáticamente.
- Turnos: Se modifica carga de detalle de recepción en modulo de turnos para que si algún lote no existe en el WMS lo genere automáticamente.
- Nomencladores: Se modifica seleccion de plantilla de muelle en carga y consulta de nomencladores para que el combo no sea un desplegable y para que no traiga los que estan dados de baja.

## 2022.06.29
---
### Agregado
- Facturador: Se genero modulo de facturacion.
- Tipos de recepcion: Se genero modulo de tipos de recepcion.
- Tipos de pedido: Se genero modulo de tipos de pedido.
- Tipos de transaccion: Se genero modulo de tipos de transaccion.
- Centros de costo: Se genero modulo de centros de costo.
- **`[Calyco Uruguay]`**: Se agrego formulario de inspección en hojas de ruta.

### Modificado
- Conexiones: Se refactorizo controlador y se quito conexion de interfaz.
- Roles: Se refactorizo formulario.
- Usuarios: Se refactorizo formulario y se corrigio bug de que no respetaba las acciones asignadas al rol.
- Cambio sucursal-sector: Se refactorizo para que al cambiar el sector se refresque en el login del sistema.
- Sectores: Se refactorizo formulario y se agrega asignacion de servicios facturables.
- Trazabilidad: Se agrego el campo de tipo de pedido para poder visualizar el tipo de comprobante del wms.
- Importador de pedidos Tienda Nube: Se corrige importador para que obtenga la razon social completa y en el domicilio tenga en cuenta el departamento.
- Débitos Transportistas: Se modifica anulación para que las paletas del debito sean rendidas o se asignen a un retiro de recupero.
- Retiros de recupero: Se modifica para permitir modificar medidas, datos de destino y observación de los retiros de recupero en estado creada y emitida.
- Retiros: Se agrega funcionalidad para turnar un retiro vencido.
- Rendición de paletas: Se agrega reporte de rendición desconsolidado para que aparezcan datos de los retiros de recupero.
- Impresión retiros de recupero: Se modifica para que aparezcan las medidas del retiro de recupero.

## 2022.05.06
---
### Agregado
- Atencion a clientes: Se agrego modulo de atencion a clientes.
- Picking automatico: Se agrego interfaz para llamar al picking automatico de SAAD con parametrizaciones.
- Tienda Nube: Se agrego interfaz de importación de pedidos desde Tienda Nube.
- Tienda Nube: Se agregaron interfaces de informe de pedidos de empaquetado y envio de ordenes a Tienda Nube.
- FedEx: Se agrego interfaz de documentación de envios hacia FedEx.
- FedEx: Se agrego interfaz de obtención de envios desde FedEx.
- **`[Brandlive]`**: Se agrego interfaz de importacion de pedidos de txt.
- **`[Brandlive]`**: Se agrego interfaz de informe de pedidos de txt para las cuentas que no son de Nike.
- **`[Brandlive]`**: Se agrego interfaz de informe de disponibilidad de csv.
- **`[Klo]`**: Se agrego interfaz de importación de cambios de estado (947).

### Modificado
- Comprobantes: Se refactorizo carga de comprobante para que permita asignar solo los tipos de formularios que tiene asignado el cliente.
- Hojas de ruta: Se agregan filtros de flota.
- **`[Calyco Uruguay]`**: Se modifica reporte de liquidacion de viajes para que muestre el recorrido del destino mas lejano.

## 2022.04.04
---
### Agregado
- Nomencladores comerciales: Se genero modulo para dar de alta nomencladores comerciales.

### Modificado
- Simulador de trafico: Se refactorizo formulario.
- Muelles: Se agrego campo de fecha de carga para hacer performantes consultas que necesiten la fecha de creación del muelle.
- Importador excel: Se modifico importador excel para que permita indicar los bultos y los metros cubicos del comprobante. Ademas se agrego la logica para que en el caso de no indicar kilogramos o metros cubicos y el cliente permita calcular dicho valor de acuerdo al coeficiente que lo complete.

## 2022.03.02
---
### Agregado
- Viaje: Se agrego campo de fecha de creacion en tabla de viajes para que sean mas performantes las buquedas por fecha de creacion.

### Modificado
- Adicionales: Se refactorizo formulario.
- Regla de adicionales: Se refactorizo formulario y se agrego posibilidad de inactivar una regla.
- Viaje: Se refactorizo asignación de adicionales para permitir obtener solo las reglas que estan activas y para permitir indicar una observacion al agregar el adicional. La observacion sale tanto en el formulario impreso de adicionales como el listado excel de adicionales.
- Comprobantes de recepcion: Se modifico listado excel estandar para que si el comprobante se encuentra almacenado muestre como fecha de conforme su ocurrencia de pendiente de resolucion o en su defecto su almacenaje.
- Reglas de valorizacion: Se corrige filtro por tarifa. Ya que no reconocia algunas tarifas.

## 2022.01.27
---
### Agregado
- Nomencladores: Se agrego accion para poder duplicar.

### Modificado
- Nomencladores: Se refactorizo formulario.
- Nomencladores: Se modifico combo de plantilla de muelles para que este ordenado alfabeticamente.
- Tarifas: Se refactorizo formulario.
- Retiros: Se modificaron permisos para poder editar la observación de los retiros no emitidos.
- Retiros: Se modificaron formularios de impresión para que si no tienen un remitente asignado que muestre los datos del cliente.
- Comprobante: Se refactorizo carga manual.
- **`[Calico]`**: Se realizo refactor de integraciones de importacion de pedidos y ordenes de retiro del cliente Bianchi.

## 2021.12.17
---
### Agregado
- Se genera modulo de atención a clientes con consultas de trazabilidad
- **`[Bls]`**: Se agrego interfaz de informe de pedidos hacia GroupeSEB.

### Modificado
- Se refactorizo formulario de clientes.
- Se corrige mapeo de acciones de planillas.
- Se refactorizo valorizacion por destino mas largo para que compare bien los recorridos numéricos.

## 2021.11.25
---
### Agregado
- En consulta de muelles se agrego filtro para poder buscar muelles con o sin comprobantes.
- Se agrega ordenamiento en grillas de distribucion.

### Modificado
- Se refactorizo performance de las anulaciones de muelles y en el proceso de anulación por reasignación se agrego funcionalidad para que también mantenga las paletas utilizadas.
- Se refactorizo performance de grilla de comprobantes dentro del modulo de muelles.
- Se refactorizo performance de proceso de anulación de viaje y además se modifico para que limpie el valor del viaje.
- Se refactorizo performance de grilla de muelles dentro del modulo de viajes.
- Se refactorizo performance de emisión de hojas de ruta.
- Se refactorizo performance de anulación de hojas de ruta.
- Se modifica acción de asignación de extra costo para que no se permita asignar si el viaje esta anulado o finalizado.
- Se modificaron filtros de proceso de tms para que autocompleten los filtros de números desde y hasta.
- Se realizo refactor del modulo de planillas.
- Se agregan permisos a todas las acciones de planilla.

## 2021.11.03
---
### Agregado
- En el tipo de unidad se agrego una parametrización para indicar que permite cargar a granel. 
- En el viaje se agrego una parametrización para indicar que sale sin paletas, esto siempre y cuando el tipo de unidad permita carga a granel.

### Modificado
- Se modifica listado Excel de rendición de paletas para mostrar las paletas utilizadas, rendidas, debitadas y a recuperar. 
- Se modifico reporte de viajes y hojas de ruta para que si el viaje sale sin paletas, se pueda visualizar en los reportes.
- Se modifico carga de paletas a muelles para que si tiene un viaje asignado se actualicen las paletas también en el viaje.
 
## 2021.10.19
---

### Agregado
- Se agrego servicio web de carga de pedidos con alta automática de subcliente.
- Se agrego interfaz de envio de etapas de comprobantes de tms hacia Optimo Camino.
- Se agrega accion de tracking de comprobantes para que llamen a la url de optimo camino.
- Se refactoriza login de TMS para que permita consultar el tracking de los comprobantes.
- **`[Calico]`**: Se agregaron interfaces EDI para Energizer.

### Modificado
- **`[Calyco Uruguay]`**: Se modifica listado de liquidación de transportista particular para que en el destino muestre la localidad que selecciono el sistema para pagar el viaje.

## 2021.10.07
---

### Agregado
- Se agrega funcionalidad de asignación de cliente a debito a transportista.
- Se agrega formulario de impresión de retiros de recupero de paletas.
- Se agrego listado de débitos a transportistas.
- Se agrego formulario de impresión de débitos a transportistas.
- Se agrega acción en retiros para permitir editar de forma masiva los datos de destino y los agrupamientos.
- Se agrego servicio web de carga de recepciones con alta automática de proveedor.

### Modificado
- Se modifica accion de creacion de pedidos de WMS para que primero inserte los detalles y despues la cabecera.

## 2021.09.07
---
### Agregado
- Se agrego filtro de scanner en modulo de retiros.
- **`[Foschia]`**: Se agrego interfaz de informe de recepcion hacia Sygemat.
- **`[Foschia]`**: Se agrego interfaz de informe de pedidos hacia Sygemat.

### Modificado
- Se modifico formulario de carga viajes para que al editar un viaje o se cargue un viaje desde el simulador se carguen automáticamente los muelles y retiros.
- Se modifico el filtro de módulos de retiro para que el filtro de numero este abajo de las fechas.

## 2021.08.20
---
### Agregado
- Se agrega pantalla de monitor de proceso de importación de productos.
- Se agrega pantalla de monitor de proceso de importación de códigos de barra.
- Se agrega pantalla de monitor de proceso de importación de recepciones.
- Se agrega pantalla de monitor de proceso de importación de pedidos.
- Se agrega pantalla de monitor de proceso de informe de recepciones.
- Se agrega pantalla de monitor de proceso de informe de pedidos.
- Se agrega pantalla de monitor de proceso de informe de ajustes.
- Se agrega pantalla de monitor de proceso de informe de stock.
- **`[Brandlive]`**: Se agrego interfaz de importación de recepciones.
- **`[Brandlive]`**: Se agrego interfaz de informe de recepciones.
- **`[Brandlive]`**: Se agrego interfaz de informe de pedidos.
- **`[Brandlive]`**: Se agrego interfaz de informe de ajustes.
- **`[Brandlive]`**: Se agrego interfaz de informe de stock.
- **`[Locksley]`**: Se agrego interfaz de importación de productos.
- **`[Locksley]`**: Se agrego interfaz de importación de pedidos.
- **`[Locksley]`**: Se agrego interfaz de informe de pedidos.
- **`[Locksley]`**: Se agrego interfaz de informe de stock.

### Modificado
- Se modifica proceso de importador excel para que la seleccion de procesos sea al comienzo con la carga del excel.
- Se refactorizo llamada al proceso de normalización de comprobantes para que no llame por cada uno a la base de datos.
- Se modifica filtro en modulo de planillas para que busque por defecto la fecha de creación de la planilla desde el primer día de la semana.
- Se refactoriza modulo de rendición de paletas de viaje para que permita filtrar por rendidos y no rendidos.

## 2021.07.29
---
### Modificado
- Se mejora performance de busqueda de muelles en viajes.

## 2021.07.07
---
### Agregado
- Se agregan validaciones de maestros en creacion y edicion de pedidos de SAAD.NET
- Se agregan validaciones de maestros en creacion y edicion de recepciones de SAAD.NET
- Se agrega pantalla de interfaz de seguimiento de recepciones
- Se agrega pantalla de interfaz de seguimiento de pedidos
- **`[Saphirus]`** Se agrega interfaz de informe de recepciones hacia SAAD TSO.
- **`[Calico]`** Se agrega interfaz de informe de prepedidos de Fecovita.

### Modificado
- Se corrige importador de excel para que si el comprobante tiene completo los datos de nombre y numero de calle tanto de origen como de destino que no llame al normalizador de domicilios.
- Se realiza refactor de proceso de valorización.
- Se quitan validaciones de restriccion de horas estimadas y de turnos desde y hasta de solicitudes y ordenes de retiro.
- Se modifica integración de conforme de comprobantes de Optimo Camino para que no filtre solo por los caminos que se envían al móvil sino que tome en cuenta todos los caminos.
- Se agrega filtro por fecha desde y hasta para la obtención de caminos en archivo de configuración.
- Se modifica integración de creación de paradas en Optimo Camino para que envie código y razón social del cliente en el servicio web.
- **`[Intralog]`** Se realizan modificaciones en integraciones EDI con S2GO.

## 2021.06.18
---
### Agregado
- Se agrega funcionalidad para poder indicar por cliente un valor tope para las medidas del comprobante y dias de emision.

### Modificado
- **`[Calico]`** Se modifica integración de informes a OSCM para que permita indicar el pais en el que se esta informando el file.
- Se mejora performance de inicio de viajes.
- Se modifica formulario de turnos de carga para que muestre las paletas del turno de carga.
- Se modifica carga de turno para que el Remito aparezca como Viaje.
- Se modifica el formulario de seguimiento de carga de turnos para que permita mostra el estado de los pedidos asociados a los turnos.
- Se modifica el formulario de tablero de carga de turnos para que permita mostrar el estado de los pedidos asociados a los turnos.
- Se modifica el formulario de tablero de descarga de turnos para que permita mostrar el estado de las recepciones asociadas a los turnos.
- Se modifica el formulario de seguimiento de descarga de turnos para que permita mostrar el estado de las recepciones asociadas a los turnos.
- Se modifica integracion de creación de muelles desde optimo camino hacia TMS para que permita filtrar por sucursal y cliente.
- Se corrige carga de comprobantes de recepción para que complete la fecha de creación.

## 2021.04.21
---
### Agregado
- Creación de cartas de devolución a partir de comprobantes almacenados.
- Anulación de cartas de devolución liberando comprobantes asociados.
- Reporte impreso de cartas de devolución.
- Reporte impreso de cartas de devolución resumido.
- Reporte impreso de cartas de devolución detallado.
- Reporte Excel de cartas de devolución.
- Validación de anulación de comprobantes que salieron en al menos un viaje.
- Creación de cirtuito de retiros de recupero.
- **`[Calico]`** Registro de remito y cantidad procesada en tabla de líneas recibidas en interfaz de Bianchi.
- **`[Calico]`** Actualización de estado de línea recibida según proceso en SAAD en interfaz de Bianchi.
- **`[Calico]`** Proceso de creación de paradas en OptimoCamino con informe de series asociadas a vale de recepción para Telecentro.

### Modificado
- Mejora en importación de archivos Excel de gran tamaño.
- **`[Calico]`** Modificación de proceso de informe de líneas procesadas para que guarde solicitudes enviadas en base de datos en interfaz de Bianchi.
- **`[Calico]`** Modificación de proceso de informe de líneas entregadas para que guarde solicitudes enviadas en base de datos en interfaz de Bianchi.

### Quitado
- **`[Calico]`** Procedimiento almacenado de generación de informes de pedidos procesados en interfaz de Bianchi.

## 2021.03.04
---
### Agregado
- Control de paletas rendidas.
- Control de paletas debitadas a transportistas.
- Control de paletas con vales de recupero.
- Pantalla de rendición de paletas en viajes iniciados o finalizados.
- Manejo de vales de proveedor.
- Nuevo tipo de retiro "Recupero de paletas" para manejo de retiros de recupero de paletas.
- Reporte Excel de paletas a recuperar para retiros del tipo "Recupero de paletas".
- **`[Calico]`** Proceso de cambio de estado de comprobantes como recibidos para Telecentro.

### Modificado
- Carga de remitentes con razón social repetida.
- Carga de clientes sin método de aforo.
- Carga de comprobantes ingresando kilogramos y metros cúbicos si el cliente no tiene asignado un método de aforo.
- Carga de solicitudes de retiro ingresando kilogramos y metros cúbicos si el cliente no tiene asignado un método de aforo.
- **`[Calico]`** Deshabilitación de asignación de datos de transporte inactivos a viajes.
- **`[Calico]`** Marca de agua en reporte impreso estándar de viajes con datos de transporte inactivos.
- **`[Calico]`** Marca de agua en reporte impreso estándar de hojas de ruta con datos de transporte inactivos.
- **`[Calico]`** Logo de cliente en reporte de ordenes de trabajo de Telecentro.
- **`[Calico]`** Piso, departamento y teléfono de destino en reporte de ordenes de trabajo de Telecentro.
- **`[Calico]`** Refactor de proceso de informe de líneas procesadas para Bianchi.

### Corregido
- Ingresos de vales de recepción con productos seriados desde importador Excel.

## 2021.02.12
---
### Agregado
- Columna con cliente y remitente en pantalla de ingreso de turnos.
- Columna con cliente y remitente en pantalla de seguimiento de turnos.
- **`[Plb]`** Tablero de seguimiento de turnos de carga.
- **`[Plb]`** Tablero de seguimiento de turnos de descarga.

### Modificado
- Filtro por defecto con turnos activos en pantalla de ingreso de turnos.
- Filtro por defecto con turnos activos en pantalla de seguimiento de turnos.
- Estados de pedidos visualizados en pantalla de seguimiento turnos de carga.
- Estados de vales de recepción visualizados en pantalla de seguimiento turnos de descarga.
- **`[Calico]`** Asignación de fecha de conforme en tabla TMS_DetalleComprobante al conformar un comprobante pendiente de resolución.
- **`[Calico]`** Asignación de fecha de entrega en tabla TMS_DetalleComprobante al almacenar un comprobante.
- **`[Calico]`** Observación por defecto "Retira cliente" al conformar comprobantes recibidos.

### Corregido
- Inicio de hojas de ruta no emitidas al iniciar viaje.

## 2021.01.11
---
### Agregado
- **`[Calico]`** Pantalla para emisión de reportes impresos de notas de devolución a partir de vales de recepción para cliente Telecentro.
- **`[Calico]`** Interfaz de ingreso de novedades para comprobantes de Telecentro.
- **`[Calico]`** Interfaz de informe de correo electrónico para Raizen.

### Modificado
- Registro de etapa al valorizar viaje.
- Visualización de precio y extra costo en cero en reporte impreso estándar de viajes para viajes anulados.
- Visualización de precio y extra costo en cero en reporte impreso de liquidación de viajes para viajes anulados.
- Visualización de precio y extra costo en cero en reporte impreso de prorrateos de viajes para viajes anulados.
- Visualización de precio y extra costo en cero en reporte Excel estándar de viajes para viajes anulados.
- Visualización de precio y extra costo en cero en reporte Excel de liquidación de viajes para viajes anulados.
- Visualización de unidades en detalle de reporte impreso de notas de devolución.
- Visualización de unidades en detalle de reporte Excel de notas de devolución.

## 2020.12.22
---
### Agregado
- Configuración de validación de emisión de hojas de ruta en viajes iniciados según tipo de viaje.
- Configuración de validación de inicio de viaje con paletas asignadas según tipo de viaje.
- Configuración de validación de finalización de viajes con rendición de paletas según tipo de viaje.
- Configuración de topes en regla de adicionales.
- Filtro de transportes inactivos en carga de viajes

### Modificado
- Mejora de usabilidad en caga de paletas utilizadas por muelle.
- Mejora de usabilidad en caga de paletas utilizadas por viajes.
- Mejoras de performance en integraciones con [OptimoCamino](https://www.optimocamino.com/).

### Corregido
- Redondeo a dos decimales en reporte impreso de adicionales.
- Redondeo a dos decimales en reporte Excel de adicionales.

## 2020.12.04
---
### Agregado
- Consulta de retiros por número de viaje.
- Carga de tipos de adicionales repetidos.

### Modificado
- Calculo de reglas de tipos de adicional por tipo de unidad de acoplado.
- Inicio de viajes con control hojas de ruta y paletas asignadas.

## 2020.11.20
---
### Agregado
- Indicadores visuales de totales asignados a muelle.
- Indicadores visuales de totales asignados a viaje.
- Configuración de formatos en importador Excel.
- Fecha de creación en pantalla de retiros.
- Totales en pantalla de retiros.
- **`[Cic]`** Ingreso y modificación de subclientes desde servicio web.
- **`[Cic]`** Ingreso y modificación de productos desde servicio web.
- **`[Intralog]`** Ingreso de pedidos dese archivos EDI.
- **`[Intralog]`** Informe de pedidos en archivos EDI.
- **`[Klo]`** Ingreso de pedidos desde Excel con formato particular.

### Modificado
- Mejora de usabilidad en caga de paletas utilizadas por muelle.
- Mejora de usabilidad en caga de paletas utilizadas por viajes.
- Mejoras de performance en pantalla de hojas de ruta.
- Valorización de viajes solo al iniciar.
- Creación y modificación de viajes sin calculo de totales.
- Numeración de viajes no bloqueante.
- Carga de devolución con marca en vale de recepción.
- **`[Calico Argentina]`** Reporte impreso de viajes estándar sin extra costo.
- **`[Calico Argentina]`** Reporte impreso de viajes estándar sin columna de paletas.
- **`[Calico Argentina]`** Reporte impreso de viajes estándar con calculo de medidas a paritr de comprobantes asignados a hojas de ruta.
- **`[Calico Argentina]`** Reporte impreso de hojas de ruta estándar sin columna de paletas.

## 2020.10.26
---
### Agregado
- Filtro por ordenes de retiro con comprobantes asignados en consulta de ordenes de retiro.
- Visualización de ordenes de retiro con comprobantes asignados en grilla de ordenes de retiro.
- Filtro por muelles automáticos en consulta de muelles.
- Visualización de muelles automáticos en grilla de muelles.
- Visualización de comprobantes asociados a retiros en detalle de grillas de ordenes de retiro.
- Listado de comprobantes asociados a retiro en detalle de grilla.
- Reporte impreso de extra costos.
- Reporte impreso de prorrateos de viaje.
- Calculo de prorrateos de comprobantes.
- Calculo de prorrateos de retiros.
- Calculo de prorrateos de comprobantes asociados a retiros.
- Interfaz estándar de envío de informes por correo electrónico.
- Configuración de informe por correo electrónico al ejecutar interfaz de movimiento de archivos entre directorios.

### Modificado
- Leyendas de fechas mas descriptivas en reporte impreso de adicionales de viajes.

### Corregido
- Reporte impreso de planillas desfasado al mostrar comprobantes con observaciones muy extensas.
- Filtro de hojas de rutas en viaje devuelve hojas de ruta conformes.

## 2020.09.30
---
### Agregado
- Carga de paletas utilizadas por viajes.
- Seguimiento de interfaces con [OptimoCamino](https://www.optimocamino.com/) desde monitor.
- Proceso automático de movimiento de archivos entre directorios.

### Modificado
- Optimización de performance de pantalla de viajes.
- El reporte impreso estándar de viajes muestra paletas utilizadas.
- El reporte impreso estándar de hojas de ruta muestra paletas utilizadas.
- **`[Calico Argentina]`** El reporte impreso particular de viajes muestra paletas utilizadas.
- **`[Calico Argentina]`** El reporte impreso particular de hojas de ruta muestra paletas utilizadas.

### Quitado
- Finalización automática de viajes.

## 2020.08.31
---
### Agregado
- Proceso de conforme de ordenes de retiro.
- Maestro de tipos de paleta.
- Carga de paletas utilizadas por muelles.

### Modificado
- Optimización de performance de pantalla de muelles.
- Los datos de vehículo y chofer en el ingreso de turnos son de carga libre y no se validan contra los maestros del modulo de flota.

## 2020.08.04
---
### Modificado
- El proceso de valorización de viajes muestra un mensaje con el motivo por el cual no se pudo valorizar en caso de error.
- El tipo de viaje permite indicar si el viaje tiene retorno.
- La carga de viajes completa el origen y destino del viaje con la sucursal en la que esta logueado el usuario si el tipo de viaje seleccionado tiene retorno.
- La empresa de transporte permite configurar si se mostrara el valor del viaje en los reportes.
- El reporte impreso estándar de viajes muestra el valor del viaje dependiendo de la parametrización de la empresa de transporte.
- **`[Calyco Uruguay]`** El reporte impreso particular de viajes muestra fecha y hora estimada de carga del viaje.
- **`[Calyco Uruguay]`** El reporte impreso particular de viajes muestra la observación del viaje.
- **`[Calyco Uruguay]`** El reporte impreso particular de liquidación de transportistas muestra el rango de fechas de emisión utilizadas en el filtro de la consulta de viajes.

### Correcciones
- Selección de roles en pantalla de carga de usuario.
- Mejoras de performance en inicio masivo de viajes.
- Mejoras de performance en valorización masiva de viajes.
