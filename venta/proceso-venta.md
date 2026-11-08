# Proceso de venta: del presupuesto a la factura

Cliente: Hotel Mirador S.A. · Fecha: 8 de noviembre de 2026

| Paso | Usuario | Acción | Referencia | Estado |
|---|---|---|---|---|
| 1 | Marta Quintana (Comercial) | Crea el presupuesto con 3 líneas, un descuento del 10 % en el café en grano, plazo de pago de 30 días y fecha de validez | S00026 | Presupuesto |
| 2 | Mauro Rodríguez Ponce (Responsable de ventas) | Confirma el presupuesto | S00026 | Pedido de venta |
| 3 | Mauro Rodríguez Ponce (Responsable de ventas) | Valida la orden de entrega (cantidad hecha = cantidad pedida). El stock del café en grano baja de 200 a 199 unidades | WH/OUT/00012 | Hecho |
| 4 | Daniel Ferrer (Administración y facturación) | Crea la factura desde el pedido, la publica y registra el pago | INV/2026/00010 | Pagado |
| 5 | Mauro Rodríguez Ponce (Responsable de ventas) | Comprueba el estado final del pedido: entregado y facturado | S00026 | Pedido de venta, facturado |

## Documentos

- [Presupuesto (PDF)](presupuesto.pdf)
- [Factura (PDF)](factura.pdf)