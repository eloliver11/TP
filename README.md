# TP
TP de algoritmos y estructuras 1


# Byte Travel - Sistema de Venta de Pasajes

## Integrantes


| Nombre y Apellido | Legajo | Usuario de GitHub |
| :--- | :--- | :--- |
| Adriano Rossi| 1170186 | @[usuario1] |
| Royer Rolando, Yampasi Laura | [Legajo 2] | @[usuario2] |
| Agustin Hernan, Barbara | 1224664 | @[usuario3] |
| Martin Adrián Marin  | 1241291 | @eloliver11 |

## Tema del Proyecto

**Sistema de gestión de pasajes**

## Descripción del Proyecto

El sistema para administrar el proceso de venta y gestión de pasajes de micros, vinculando a los clientes con los distintos destino disponibles, sucursales, vendedores etc. Nos circunscribiremos a pasajes de Bus dentro de Argentina.

Su propósito principal es brindar una solución centralizada para gestionar el registro de compradores, vendedores, sucursales, administrar la oferta de destinos y registrar cada pasaje

De esta manera, permitirá estructurar el historial de viajes y generar métricas. Realizar altas, bajas, modificaciones y consultas de las distintas entidades

## Listado de Funcionalidades


* ### Gestión de Entidades (CRUD)

* **Clientes:** Alta, baja, modificación y consulta de la información de los pasajeros.
* **Ciudades:** Alta, baja, modificación y consulta de las ciudades/localidades de partida.
* **Sucursales:** Alta, baja, modificación y consulta de los puntos de venta habilitados.
* **Vendedores:** Alta, baja, modificación y consulta de los empleados de atención y emisión.
* **Formas de Pago:** Alta, baja, modificación y consulta de los medios de pago aceptados (efectivo, tarjeta de crédito/débito, transferencia, etc.).
* **Pasajes:** Alta (emisión), baja (cancelación/anulación), modificación (reprogramación) y consulta de los pasajes registrados, vinculando cliente, origen, destino, sucursal, vendedor, forma de pago, fecha y monto.

### Operaciones de Pasajes
* Emisión y registro de nuevos pasajes (asociando cliente, destino, fecha y monto).
* Modificación o reprogramación de pasajes existentes.
* Cancelación/anulación de pasajes emitidos.

### Consultas
* Búsqueda del historial de pasajes/viajes comprados por un cliente específico.
* Filtrado de pasajes emitidos por rango de fechas o por destino.

### Reportes y Métricas
* Cantidad total de pasajes vendidos por destino.
* Promedio de ventas en un período determinado.
* Identificación de los destinos con mayor demanda.
