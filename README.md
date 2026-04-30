## Descripcion del negocio
Nombre: Bodega Monica <br>
Tamaño: Pequeña empresa, operacion individual o familiar <br>
Contexto: Negocio muy comun en el Peru en el cual compran productos de primera
necesidad (alimentos, limpieza, bebidas) al por mayor
para venderlos por unidad al consumidor final. <br>
Justificacion: Se necesita un sistema digital que faciliter sumar el monto de la venta que hasta ahoras se realiza de forma manual un cuaderno, para asi evitar errores al monto que el cliente haga su compra.

## Identificar el problema y la solución
El negocio opera de forma manual a travez del uso de un cuaderno. Esto genera tres problemas:
Problema <br>
- Pérdida de dinero: Los "fiados" se olvidan, se anotan mal o el papel se pierde.
- El stock: El negocio no sabe que se acabó la leche hasta que un cliente se lo pide y no hay.
- Ineficiencia: Tardar demasiado en buscar precios o calcular totales en horas pico.
La Solución <br>
Un sistema de gestión centralizado que automatice el control de inventario y vincule las ventas directamente <br>
con un historial de deudas por cliente, haciendo que cada producto este registrado.

## Preanálisis
Necesidades
-Digitalizar el catálogo de productos y precios.
-Llevar un registro histórico de quién debe, cuánto debe y cuándo compró.
-Reducir el tiempo de atención al cliente en el mostrador.

Estudio de visibilidad
- Operativa: Siempre que la interfaz sea minimalista y diseñada para alguien que no es experto en computación
- Económica: Altamente viable. El uso de software open source (Apache, MySQL) reduce los costos de licencia a cero.

Alcance del Sistema
- Registro de Ventas (Efectivo y Crédito).
- Gestión de Clientes y Cobro de Deudas.

## Análisis de Requerimientos
## Requerimientos Funcionales
| Codigo | Descripcion |
|---|---|
| RF01 | El sistema debe permitir agregar, editar y eliminar productos. |
| RF02 | El sistema debe calcular el total y descontar stock al realizar una venta.|
| RF03 | El sistema debe permitir elegir entre pago en "Efectivo" o "Fiado" |
| RF04 | El sistema debe permitir asignar una venta como "pendiente" a un cliente específico. |
| RF05 | El sistema debe registrar ventas seleccionando productos y calculando el total automáticamente |

## Requerimientos No Funcionales
 
| Codigo | Tipo | Descripcion |
|---|---|---|
| RNF01 | Rendimiento | El sistema debe procesar el registro de una venta y generar la respuesta en menos de 2 segundos. |
| RNF02 | Usabilidad | La interfaz debe ser simple y fácil de usar, pensada para una navegación rápida |
| RNF03 | Seguridad | El sistema debe requerir un usuario y contraseña para acceder a la gestión de inventario y deudas. |
| RNF03 | Seguridad | El sistema debe ser accesible desde cualquier navegador web moderno |


