# Manual de Usuario Bonimedios 4


- [Manual de Usuario Bonimedios 4](#manual-de-usuario-bonimedios-4)
  - [Login](#login)
  - [Dashboard](#dashboard)
    - [Filtros](#filtros)
    - [KPI principales](#kpi-principales)
    - [Facturacion Desde - Hasta](#facturacion-desde---hasta)
    - [Distribucion por Medio Clave](#distribucion-por-medio-clave)
    - [Actividad de Directores](#actividad-de-directores)
    - [Billing Medios](#billing-medios)
    - [Share Medio](#share-medio)
  - [Menu Principal y Notificaciones](#menu-principal-y-notificaciones)
  - [Administracion](#administracion)
    - [Catalogos](#catalogos)
      - [Agencias](#agencias)
      - [Medios](#medios)
      - [Soportes](#soportes)
      - [Clientes](#clientes)
    - [Grupos de Bonificacion](#grupos-de-bonificacion)
    - [Usuarios](#usuarios)
    - [Periodos](#periodos)
    - [Metas por Agencia](#metas-por-agencia)
    - [Procesar Real](#procesar-real)
  - [Budget](#budget)
    - [Metas](#metas)
    - [Realizar](#entry-budget)
    - [Aprobar](#aprobar)
    - [Consolidar](#consolidar)
  - [Proyectados](#proyectados)
    - [Metas](#metas-1)
    - [Realizar](#entry-proyection)
    - [Aprobar](#aprobar-1)
    - [Consolidar](#consolidar-1)
  - [Mejor Proyectado](#mejor-proyectado)
    - [Metas](#metas-2)
    - [Realizar](#entry-bp)
    - [Aprobar](#aprobar-2)
    - [Consolidar](#consolidar-2)
  - [Reportes](#reportes)
    - [Data](#data)
    - [BI](#bi)
  - [Notificaciones](#notificaciones)
  - [Reglas de Negocio](#reglas-de-negocio)




## Login

El acceso al sistema comienza con el pantalla de bienvenida y login del sistema. Aqui tendremos que ingresar nuestro usuario y contraseña de red, en la forma :

> nombre.apellido / contraseña de red


![Login](imagenes/00-00-login.png)

Si estos datos son correctos, el sistema presentará el [Dashboard](#Dashboard), de lo contrario, se indicará con una alerta que el nombre de usuario o la contraseña son incorrectos, en cuyo caso debes reingresar los datos correctamente. 

_Recuerda validar con la [Mesa de Ayuda](mailto:mesa.ayuda@havasit.com) que tu usuario y contraseña no se encuentren bloqueados_

## Dashboard

El Home o Dashboard, es la sección principal del sistema y desde donde tendrás el control de todos los detalles, tanto vigentes como históricos, de tu cartera actual.

![Dashboard 1](imagenes/01-00-00-dashboard.png)

![Dashboard 2](imagenes/01-00-01-dashboard.png)

A continuación, describimos cada sección del contenido del dashboard. Cabe destacar que, dependiendo del perfil de tu usuario, podrás ver o no algunas de las secciones descritas.

### Filtros

Este filtro te permite cambiar el perído de análisis de cada KPI y tabla del Dashboard para que considere los datos ingresados para realizar los cálculos.

![Alt text](imagenes/01-01-01-dashboard-filtro.png)

- *Año:* establece el año de proceso deseado, al cambiar de año se actualiza la lista de Períodos de acuerdo a los datos existentes en el año seleccionado. Por omisión, estará seleccionado el año actual
- *Forecast:*, Permite seleccionar el período, dentro del año establecido, sobre el que se desea consultar. Por omisión estará seleccionado el periodo en curso.
- *Ver:* permite filtrar el conjunto de clientes sobre el que deseo revisar datos
- *Período:* permite filtar los meses del análisis

_Estos filtros no tienen efecto en el ingreso de datos, solo son utlizados para filtrar los datos del Dashboard_

### KPI principales

Esta sección presenta los principales indicadores de gestión de nuestra cartera, esta compuesta por los siguientes KPI:

- *INVERSION NETA:* representa el total de la inversión acumulada a la fecha seleccionada
- *CUM:* el es porcentaje de cumplimiento de la inversión _REAL_ respecto de lo _PROYECTADO_ a la fecha.
- *CUM x MEDIO:* es el promedio del porcentaje de cumplimiento por medio a la fecha

![Alt text](imagenes/01-01-01-dashboard-kpi.png)


### Facturacion Desde - Hasta

El siguiente componente nos muestra el detalle de la facturación acumulada a la fecha seleccionada en el filtro, abierta por cada uno de los Medios de la plataforma e indicando en cada columna:

- *Billing Total*, el total del billing para este medio a la fecha (año completo)
- *Ene - Dic*, el total del billing para los meses indicados en el filtro
- *Share Total*, el procentaje que representa cada Medio respecto del total de los billings del período
- *Cum x Medio*, el porcentaje de cumplimiento de cada Medio para los datos del _REAL_ respecto de los _PROYECTADOS_


![Alt text](imagenes/01-01-01-dashboard-facturacion.png)

### Distribucion por Medio Clave

*Solo rol de administrador*

Este componente nos presenta una distribución de la inversión y el share respecto del total para cada Medio Clave (según configuración), indicando además si es Pure Player.

![Alt text](imagenes/01-01-01-dashboard-distribmclave.png)


### Actividad de Directores

*Solo rol de administrador*

Cuadro que nos muestra el detalle del cumplimiento de proceso de proyección mensual para cada director cargado en el sistema. Solo cuando el 100% de ellos han cumplido la etapa final, es posible cerrar el período actual y abrir el siguiente. Este control permite que el administrador tenga, además de una confirmación rápida del estado de cada equipo, entrar al detalle mediante el link *_Ver más detalle_* y tomar el control de la proyección de un equipo forzando su aprobación.

![Alt text](imagenes/01-01-01-dashboard-actividad.png)


### Billing Medios

Este es un cuadro resumen de los billings del período, agrupando los medios homogéneamente según su tipo:

- *DIG*, plataformas digitales
- *PPP*, Pure Players
- *DP*, 
- *TV*, TV abierta
- *TVP* TV paga

![Alt text](imagenes/01-01-01-dashboard-billingxmedios.png)

### Share Medio

De igual modo que el control anterior, esta sección nos entrega un resumen del billing agrupado indicando el porcentaje de cada subconjunto respecto del total del período:

- *SOD,* Share of Digital
- *SOPPP,* Share of Pure Player
- *SDPPPD,* Share of Pure Player Digital
- *SOPD,* Share of Pure Digital
- *SOTV,* Share of TV Abierta
- *SOTVP,* Share of TV Paga

![Alt text](imagenes/01-01-01-dashboard-sharexmedio.png)


## Menu Principal y Notificaciones

El menu principal agrupa todas las funcionalidades del sistema, en un conjunto lógico de accesos y que, dependiendo del rol del usuario conectado, desplegará o no, cada sección.

*Perfiles*

- *Administrador*, gestión, administración y configuración de la plataforma. Tiene accesos a todos los datos independiente de las carteras de clientes de cada usuario.
- *Director*, puede crear, eliminar, aprobar, rechazar e ingresar (modificar) los datos de: budget, proyección mensual y mejor proyectado. También puede descargar informes de su cartera de clientes asignada
- Supervisor, puede ingresar (modificar) los datos de: budget, proyección mensual y mejor proyectado


*Nivel de permisos por rol*

|Opcion|Rol|Descripcion|
|-----|------|------|
|Administracion|Administrador|Configuracion del sistema|
|Budget|Todos|Ingreso proyección para el año siguiente|
|Proyección|Todos|Ingreso de proyección mensual|
|Mejor Proyectado|Todos|Ingreso del mejor proyectado durante mes en curso|
|Reportes|Todos|Descarga de reportes e informes|



![Menu principal](imagenes/01-02-menu.png)


En la sección superior derecha de la aplicación, encontraremos el ícono de acceso a la sección de [notificaciones](#notificaciones) y el botón de logout (salir) del sistema.

![Notificaciones](imagenes/01-03-acciones.png)


## Administracion

El menú de administración, reservado para los roles de *Administrador*, nos permite ajustar la configuración del sistema, sincronizar datos con MMS, gestión de los períodos y procesar manualmente las bonificaciones.

![Menu Administración](imagenes/02-00-00-menu-admin.png)



### Catalogos

Los catálogos son el equivalente a las tablas de _"maestros"_ del sistema, salvo que en nuestro caso, estas vienen sincronizadas desde MMS. El proceso de sincronización puede ser manual mediante el botón de sincronización (adicionalmente esta sincronización se ejecuta automáticamente cuando se actualizan los datos desde MMS):

![Sync](imagenes/02-00-01-boton-sincronizar-maestros.png)

Existen cuatro tablas de maestros, las cuales pueden ser seleccionadas a partir del *selector de catálogo*

![Selector de Catalogos](imagenes/02-00-01-boton-selector-maestros.png)


La equivalencia entre los maestros de MMS y su correspondiente uso en Bonimedios es el siguiente:

|Bonimedios| MMS|Ejemplo|Observacion|
|-----|----|--|--|
|Agencia|Agencias|Arena Media Chile (37)|Todas las agencias, excepto las filtradas por las [reglas de negocio](#reglas-de-negocio)|
|Medio|Submedio|PRENSA GRATUITA (10)|Considera los *submedios*, excepto aquellos filtrados por las [reglas de negocio](#reglas-de-negocio)|
|Soporte|Soporte + Medio + Proveedor|13C (CANAL 13) (17) - CANAL 13 S.P.A.|Consolida todos los soportes por medio y proveedor en un equivalente para cada uno de ellos, conformado por la descripcion del soporte y la descripcion del proveedor ("soporte - proveedor") además de la información del Medio como referencia, excepto los filtrados por las [reglas de negocio](#reglas-de-negocio)|
|Cliente|Grupo|GILDEMEISTER (1)|A partir de los grupos de MMS, solo aquellos no dados de baja o filtrados por las [reglas de negocio](#reglas-de-negocio)|


Todos los catálogos comparten una funcionalidad similar:

- En la parte *izquierda* de la pantalla, el catálogo Bonimedios
- En la parte *derecha* de la pantalla, el equivalente en MMS
  
![Alt text](imagenes/02-01-01-00-catalogo-agencias.png)

Al seleccionar un elemento del catálogo Bonimedios, se muestran sus relaciones en la sección de MMS. 

Inicialmente cada dato de Bonimedios esta relacionado con un equivalente desde MMS.

Es posible asignar múltiples datos de MMS a un solo registro de Bonimedios. Esto se logra con el boton de *Añadir Item*. El resultado de esta operación es que Bonimedios, tratará cualquier información que provenga de MMS desde alguno de los registros enlazados como si fuesen uno solo en Bonimedios, lo que en la práctica agrupará (o sumará) los valores de todos ellos en uno solo. 

Esto puede ser especialmente útil en casos tales como en los que MMS tiene cargada información en múltiples grupos que en realidad son el mismo, pero duplicados erróneamente. En este contexto, podemos asociar todos ellos a uno solo en Bonimedios, logrando una consolidación efectiva de la información.


#### Agencias


![Alt text](imagenes/02-01-01-00-catalogo-agencias.png)


![Alt text](imagenes/02-01-01-01-catalogo-agencias-agregar.png) 
![Alt text](imagenes/02-01-01-02-catalogo-agencias-editar.png) 
![Alt text](imagenes/02-01-01-03-catalogo-agencias-eliminar.png) 
![Alt text](imagenes/02-01-01-04-catalogo-agencias-sincronizar.png) 
![Alt text](imagenes/02-01-01-05-catalogo-agencias-asociar.png)


#### Medios

![Alt text](imagenes/02-01-02-00-catalgo-medios.png) 
![Alt text](imagenes/02-01-02-01-catalgo-medios-agregar.png) 
![Alt text](imagenes/02-01-02-02-catalgo-medios-editar.png) 
![Alt text](imagenes/02-01-02-03-catalgo-medios-eliminar.png) 
![Alt text](imagenes/02-01-02-04-catalgo-medios-sincronizar.png) 
![Alt text](imagenes/02-01-02-05-catalgo-medios-asociar.png)


#### Soportes

![Alt text](imagenes/02-01-03-00-catalogo-soportes.png) 
![Alt text](imagenes/02-01-03-01-catalogo-soportes-agregar.png) 
![Alt text](imagenes/02-01-03-02-catalogo-soportes-editar.png) 
![Alt text](imagenes/02-01-03-03-catalogo-soportes-eliminar.png) 
![Alt text](imagenes/02-01-03-04-catalogo-soportes-sincronizar.png) 
![Alt text](imagenes/02-01-03-05-catalogo-soportes-asociar.png)

#### Clientes

![Alt text](imagenes/02-01-04-00-catalogo-clientes.png) 
![Alt text](imagenes/02-01-04-01-catalogo-clientes-agregar.png) 
![Alt text](imagenes/02-01-04-02-catalogo-clientes-editar.png) 
![Alt text](imagenes/02-01-04-03-catalogo-clientes-elminar.png) 
![Alt text](imagenes/02-01-04-04-catalogo-clientes-sincronizar.png) 
![Alt text](imagenes/02-01-04-05-catalogo-clientes-asociar.png)

### Grupos de Bonificacion

![Alt text](imagenes/02-02-01-00-grupos-bonificacion-catalogo.png) 
![Alt text](imagenes/02-02-01-01-grupos-bonificacion-agregar.png) 
![Alt text](imagenes/02-02-01-02-grupos-bonificacion-editar.png) 
![Alt text](imagenes/02-02-01-03-grupos-bonificacion-eliminar.png) 
![Alt text](imagenes/02-02-01-04-grupos-bonificacion-asociar.png)


### Usuarios


![Alt text](imagenes/02-03-01-00-usuarios.png) 
![Alt text](imagenes/02-03-01-01-usuarios-acciones.png) 
![Alt text](imagenes/02-03-01-02-usuarios-agregar.png) 
![Alt text](imagenes/02-03-01-03-usuarios-reabrir-periodo.png) 
![Alt text](imagenes/02-03-01-04-usuarios-agregar-cliente.png) 
![Alt text](imagenes/02-03-01-04-usuarios-reasignar-cliente.png) 
![Alt text](imagenes/02-03-01-05-usuarios-editar-medios.png) 
![Alt text](imagenes/02-03-01-06-usuarios-desasignar-cliente.png)


### Periodos

![Alt text](imagenes/02-04-01-00-catalogo-periodos.png) 
![Alt text](imagenes/02-04-01-01-catalogo-periodos-crear.png) 
![Alt text](imagenes/02-04-01-02-catalogo-periodos-cerrar.png)


### Metas por Agencia

![Alt text](imagenes/02-05-01-00-metas-agencia.png)

### Procesar Real

![Alt text](imagenes/02-06-01-00-procesar.png)


## Budget
![Alt text](imagenes/03-00-menu-budget.png)

<!-- ### Metas
-->


### Realizar

En la sección, los usuarios tienen la oportunidad de llevar a cabo la proyección anual de la inversión para el próximo año. Este paso es crucial en el ciclo de planificación financiera y estratégica de la agencia, permitiendo a los equipos detallar y ajustar las expectativas de inversión por cliente, medio y soporte.

![Alt text](imagenes/03-02-menu-budget-realizar.png.png)

A continuación, describimos cada sección del contenido del realizar 'budget'.

#### Filtros

  ##### Periodo

  ![Alt text](imagenes/03-02-01-realizar-filtro-periodo.png)

  Este filtro te permite cambiar el perído de análisis de las proyecciones.

  ##### Version

  ![Alt text](imagenes/03-02-01-realizar-filtro-version.png)

  Este filtro te permite alternar entre distintas versiones de las proyecciones realizadas. Al utilizarlo, podrás comparar diferentes escenarios o revisiones de tus datos, facilitando el análisis de cómo han evolucionado tus proyecciones a lo largo del tiempo.

  ##### Clientes

  ![Alt text](imagenes/03-02-01-realizar-filtro-clientes.png)

  Este filtro te permite seleccionar un cliente específico de tu cartera. 


  ##### Medios

  ![Alt text](imagenes/03-02-01-realizar-filtro-medio.png)

  Este filtro te permite realizar una selección múltiple de los medios asignados a los clientes en tu cartera.

  ##### Mes

  ![Alt text](imagenes/03-02-01-realizar-filtro-medio.png)

  Este filtro te permite seleccionar uno o varios meses específicos para que solo aparezcan en la cuadrícula de proyección.

  ##### Distribución

  ![Alt text](imagenes/03-02-01-realizar-filtro-distribucion.png)

  Este filtro te permite definir cómo se distribuye el valor proyectado en un medio específico entre los distintos soportes asignados a ese medio.


#### Exportar

![Alt text](imagenes/03-02-02-realizar-exportar.png)

Este botón te permite exportar toda la información relacionada con el "budget" a un archivo de Excel. Al hacer clic en él, se generará automáticamente un documento que incluye las proyecciones.


#### Agregar Soporte a un Medio

![Alt text](imagenes/03-02-03-realizar-agregar-soporte.png)

Este botón abre un modal que presenta un listado de soportes disponibles específicos para el medio seleccionado.

![Alt text](imagenes/03-02-03-realizar-agregar-soporte-guardar.png)

Al presionarlo, los usuarios pueden navegar por este listado para identificar y seleccionar el soporte deseado que desean agregar a su proyección. Una vez hecho esto, deben confirmar su elección presionando el botón "Seleccionar" dentro del modal. 

#### Eliminar Soporte a un Medio

![Alt text](imagenes/03-02-04-realizar-eliminar-soporte.png)

Este botón esta situado al lado de cada soporte listado, este botón permite a los usuarios remover un soporte específico de su proyección

![Alt text](imagenes/03-02-04-realizar-eliminar-soporte-confirmar.png)

Al presionarlo, se abre un modal de confirmación para asegurar que la eliminación es intencional.

#### Columnas

![Alt text](imagenes/03-02-05-manu-budget-realizar-columnas.png)

Dentro de la cuadrícula de proyección de gestión de "budget", el ítem "Columnas" permite a los usuarios personalizar la visualización de datos al incluir o excluir columnas específicas. Entre las opciones disponibles, se encuentran las columnas (R)"Real" y (B)"Budget".


#### Ingreso de Proyecciones

![Alt text](imagenes/03-02-06-realizar-medio-soporte.png)

El sistema permite el ingreso de proyecciones tanto por medio como por soporte:

- Por Medio: Ingrese montos globales de inversión asignados a cada tipo de medio (ej. televisión, radio, digital).

  Al ingresar proyecciones por medio, la selección de la distribución determina cómo se reparte la inversión entre los soportes asociados a ese medio:

    ![Alt text](imagenes/03-02-06-01-distribucion.png)

    - Equivalente: La inversión se divide por igual entre todos los soportes del medio.

      ![Alt text](imagenes/03-02-06-01-distri-equivalente-select.png)

      ![Alt text](imagenes/03-02-06-01-distri-equivalente-resultado.png)

    - Porcentual: La inversión se distribuye entre los soportes según porcentajes específicos previamente asignados a cada soporte dentro del medio.

      ![Alt text](imagenes/03-02-06-01-distri-porcentual-select.png)

      ![Alt text](imagenes/03-02-06-01-distri-porcentual-resultado.png)


- Por Soporte: Asigne inversiones a soportes específicos dentro de un medio para una planificación más detallada.

  ![Alt text](imagenes/03-02-06-02-proyecion-soporte.png)

##### Operadores 

En la gestión de proyecciones tanto para medios como para soportes, se disponen de dos operadores clave que facilitan la planificación y distribución de la inversión a lo largo del tiempo:

  - Operador ">" (Replicar): Al utilizar este operador junto a un valor ingresado para un mes específico, dicho valor se replicará automáticamente a todos los meses siguientes dentro del año de proyección.

    ![Alt text](imagenes/03-02-06-03-operador-repeticion.png)

    ![Alt text](imagenes/03-02-06-03-operador-repeticion-resultado.png)


  - Operador "/" (Dividir): Este operador divide el valor ingresado para un mes entre todos los meses restantes del período de proyección, incluyendo el mes en curso. 

    ![Alt text](imagenes/03-02-06-03-operador-divisor.png)

    ![Alt text](imagenes/03-02-06-03-operador-divisor-resultado.png)




<!---### Aprobar

### Consolidar
-->
## Proyectados
![Alt text](imagenes/04-00-menu-proyectar.png)

En la sección, los usuarios tienen la oportunidad de llevar a cabo la proyección de la inversión. Este paso es crucial que permite a los equipos detallar y ajustar las expectativas de inversión por cliente, medio y soporte.

![Alt text](imagenes/04-00-proyectar-realizar.png)

A continuación, describimos cada sección del contenido del realizar 'proyeccion'.

#### Filtros

  ##### Periodo

  ![Alt text](imagenes/03-02-01-realizar-filtro-periodo.png)

  Este filtro te permite cambiar el perído de análisis de las proyecciones.

  ##### Version

  ![Alt text](imagenes/03-02-01-realizar-filtro-version.png)

  Este filtro te permite alternar entre distintas versiones de las proyecciones realizadas. Al utilizarlo, podrás comparar diferentes escenarios o revisiones de tus datos, facilitando el análisis de cómo han evolucionado tus proyecciones a lo largo del tiempo.

  ##### Clientes

  ![Alt text](imagenes/03-02-01-realizar-filtro-clientes.png)

  Este filtro te permite seleccionar un cliente específico de tu cartera. 


  ##### Medios

  ![Alt text](imagenes/03-02-01-realizar-filtro-medio.png)

  Este filtro te permite realizar una selección múltiple de los medios asignados a los clientes en tu cartera.

  ##### Mes

  ![Alt text](imagenes/03-02-01-realizar-filtro-medio.png)

  Este filtro te permite seleccionar uno o varios meses específicos para que solo aparezcan en la cuadrícula de proyección.

  ##### Columnas

  ![Alt text](imagenes/04-01-filtro-columna.png)

  El filtro de columnas permite a los usuarios personalizar la visualización de la cuadrícula de proyección seleccionando específicamente qué columnas desean ver.

  ##### Distribución

  ![Alt text](imagenes/03-02-01-realizar-filtro-distribucion.png)

  Este filtro te permite definir cómo se distribuye el valor proyectado en un medio específico entre los distintos soportes asignados a ese medio.


#### Exportar

![Alt text](imagenes/03-02-02-realizar-exportar.png)

Este botón te permite exportar toda la información relacionada con el "proyectado" a un archivo de Excel. Al hacer clic en él, se generará automáticamente un documento que incluye las proyecciones.


#### Agregar Soporte a un Medio

![Alt text](imagenes/03-02-03-realizar-agregar-soporte.png)

Este botón abre un modal que presenta un listado de soportes disponibles específicos para el medio seleccionado.

![Alt text](imagenes/03-02-03-realizar-agregar-soporte-guardar.png)

Al presionarlo, los usuarios pueden navegar por este listado para identificar y seleccionar el soporte deseado que desean agregar a su proyección. Una vez hecho esto, deben confirmar su elección presionando el botón "Seleccionar" dentro del modal. 

#### Eliminar Soporte a un Medio

![Alt text](imagenes/03-02-04-realizar-eliminar-soporte.png)

Este botón esta situado al lado de cada soporte listado, este botón permite a los usuarios remover un soporte específico de su proyección

![Alt text](imagenes/03-02-04-realizar-eliminar-soporte-confirmar.png)

Al presionarlo, se abre un modal de confirmación para asegurar que la eliminación es intencional.

#### Columnas

![Alt text](imagenes/04-02-05-proyeccion-realizar-columnas.png)

Dentro de la cuadrícula de proyección de gestión de "proyectado", el ítem "Columnas" permite a los usuarios personalizar la visualización de datos al incluir o excluir columnas específicas. Entre las opciones disponibles, se encuentran las columnas (R)"Real", (B)"Budget", (P)"Proyectado".


#### Ingreso de Proyecciones

![Alt text](imagenes/03-02-06-realizar-medio-soporte.png)

El sistema permite el ingreso de proyecciones tanto por medio como por soporte:

- Por Medio: Ingrese montos globales de inversión asignados a cada tipo de medio (ej. televisión, radio, digital).

  Al ingresar proyecciones por medio, la selección de la distribución determina cómo se reparte la inversión entre los soportes asociados a ese medio:

    ![Alt text](imagenes/03-02-06-01-distribucion.png)

    - Equivalente: La inversión se divide por igual entre todos los soportes del medio.

      ![Alt text](imagenes/03-02-06-01-distri-equivalente-select.png)

      ![Alt text](imagenes/03-02-06-01-distri-equivalente-resultado.png)

    - Porcentual: La inversión se distribuye entre los soportes según porcentajes específicos previamente asignados a cada soporte dentro del medio.

      ![Alt text](imagenes/03-02-06-01-distri-porcentual-select.png)

      ![Alt text](imagenes/03-02-06-01-distri-porcentual-resultado.png)


- Por Soporte: Asigne inversiones a soportes específicos dentro de un medio para una planificación más detallada.

  ![Alt text](imagenes/03-02-06-02-proyecion-soporte.png)

##### Operadores 

En la gestión de proyecciones tanto para medios como para soportes, se disponen de dos operadores clave que facilitan la planificación y distribución de la inversión a lo largo del tiempo:

  - Operador ">" (Replicar): Al utilizar este operador junto a un valor ingresado para un mes específico, dicho valor se replicará automáticamente a todos los meses siguientes dentro del año de proyección.

    ![Alt text](imagenes/03-02-06-03-operador-repeticion.png)

    ![Alt text](imagenes/03-02-06-03-operador-repeticion-resultado.png)


  - Operador "/" (Dividir): Este operador divide el valor ingresado para un mes entre todos los meses restantes del período de proyección, incluyendo el mes en curso. 

    ![Alt text](imagenes/03-02-06-03-operador-divisor.png)

    ![Alt text](imagenes/03-02-06-03-operador-divisor-resultado.png)


<!--### Metas-->

### Realizar

<!--### Aprobar

### Consolidar-->

## Mejor Proyectado
![Alt text](imagenes/05-00-menu-mejor-proyectado.png)

En la sección, permite a los usuarios realizar ajustes mensuales a las proyecciones para reflejar el escenario más favorable dentro del período actual. 

![Alt text](imagenes/04-00-proyectar-realizar.png)

A continuación, describimos cada sección del contenido del realizar 'mejor proyectado'.

#### Filtros

  ##### Periodo

  ![Alt text](imagenes/03-02-01-realizar-filtro-periodo.png)

  Este filtro te permite cambiar el perído de análisis de las proyecciones.

  ##### Version

  ![Alt text](imagenes/03-02-01-realizar-filtro-version.png)

  Este filtro te permite alternar entre distintas versiones de las proyecciones realizadas. Al utilizarlo, podrás comparar diferentes escenarios o revisiones de tus datos, facilitando el análisis de cómo han evolucionado tus proyecciones a lo largo del tiempo.

  ##### Clientes

  ![Alt text](imagenes/03-02-01-realizar-filtro-clientes.png)

  Este filtro te permite seleccionar un cliente específico de tu cartera. 


  ##### Medios

  ![Alt text](imagenes/03-02-01-realizar-filtro-medio.png)

  Este filtro te permite realizar una selección múltiple de los medios asignados a los clientes en tu cartera.

  ##### Mes

  ![Alt text](imagenes/03-02-01-realizar-filtro-medio.png)

  Este filtro te permite seleccionar uno o varios meses específicos para que solo aparezcan en la cuadrícula de proyección.

  ##### Columnas

  ![Alt text](imagenes/04-01-filtro-columna.png)

  El filtro de columnas permite a los usuarios personalizar la visualización de la cuadrícula de proyección seleccionando específicamente qué columnas desean ver.

  ##### Distribución

  ![Alt text](imagenes/03-02-01-realizar-filtro-distribucion.png)

  Este filtro te permite definir cómo se distribuye el valor proyectado en un medio específico entre los distintos soportes asignados a ese medio.


#### Exportar

![Alt text](imagenes/03-02-02-realizar-exportar.png)

Este botón te permite exportar toda la información relacionada con el "mejor proyectado" a un archivo de Excel. Al hacer clic en él, se generará automáticamente un documento que incluye las proyecciones.


#### Agregar Soporte a un Medio

![Alt text](imagenes/03-02-03-realizar-agregar-soporte.png)

Este botón abre un modal que presenta un listado de soportes disponibles específicos para el medio seleccionado.

![Alt text](imagenes/03-02-03-realizar-agregar-soporte-guardar.png)

Al presionarlo, los usuarios pueden navegar por este listado para identificar y seleccionar el soporte deseado que desean agregar a su proyección. Una vez hecho esto, deben confirmar su elección presionando el botón "Seleccionar" dentro del modal. 

#### Eliminar Soporte a un Medio

![Alt text](imagenes/03-02-04-realizar-eliminar-soporte.png)

Este botón esta situado al lado de cada soporte listado, este botón permite a los usuarios remover un soporte específico de su proyección

![Alt text](imagenes/03-02-04-realizar-eliminar-soporte-confirmar.png)

Al presionarlo, se abre un modal de confirmación para asegurar que la eliminación es intencional.

#### Columnas

![Alt text](imagenes/05-02-05-mp-realizar-columnas.png)

Dentro de la cuadrícula de proyección de gestión de "mejor proyectado", el ítem "Columnas" permite a los usuarios personalizar la visualización de datos al incluir o excluir columnas específicas. Entre las opciones disponibles, se encuentran las columnas (R)"Real", (B)"Budget", (MP)"Mejor Proyectado".


#### Ingreso de Proyecciones

![Alt text](imagenes/03-02-06-realizar-medio-soporte.png)

El sistema permite el ingreso de proyecciones tanto por medio como por soporte:

- Por Medio: Ingrese montos globales de inversión asignados a cada tipo de medio (ej. televisión, radio, digital).

  Al ingresar proyecciones por medio, la selección de la distribución determina cómo se reparte la inversión entre los soportes asociados a ese medio:

    ![Alt text](imagenes/03-02-06-01-distribucion.png)

    - Equivalente: La inversión se divide por igual entre todos los soportes del medio.

      ![Alt text](imagenes/03-02-06-01-distri-equivalente-select.png)

      ![Alt text](imagenes/03-02-06-01-distri-equivalente-resultado.png)

    - Porcentual: La inversión se distribuye entre los soportes según porcentajes específicos previamente asignados a cada soporte dentro del medio.

      ![Alt text](imagenes/03-02-06-01-distri-porcentual-select.png)

      ![Alt text](imagenes/03-02-06-01-distri-porcentual-resultado.png)


- Por Soporte: Asigne inversiones a soportes específicos dentro de un medio para una planificación más detallada.

  ![Alt text](imagenes/03-02-06-02-proyecion-soporte.png)

<!--### Metas-->

### Realizar

<!--### Aprobar

### Consolidar-->

## Reportes

![Alt text](imagenes/06-00-menu-reportes.png)


<!--### Data

### BI

## Notificaciones


## Reglas de Negocio-->
