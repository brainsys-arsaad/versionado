---
layout: default
title: Registro de cambios
navegacion:
  contenido:
    - nombre: "Pendiente de liberación"
      link: "registro-cambios#pendiente-de-liberación"
  versiones:
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
### Agregado
- Se agrego accion en nomencladores para poder duplicar nomencladores.

### Modificado
- Se refactorizo formulario de nomencladores
- Se refactorizo formulario de tarifas
- Se modificaron permisos en retiros para poder editar la observación de los retiros no emitidos.
- Se modificaron formularios de impresión de retiros para que si no tienen un remitente asignado que muestre los datos del cliente.

## 2021.12.17
---
### Agregado
- Se genera modulo de atención a clientes con consultas de trazabilidad

### Modificado
- Se refactorizo formulario de clientes.
- Se corrige mapeo de acciones de planillas.
- Se refactorizo valorizacion por destino mas largo para que compare bien los recorridos númericos.

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
