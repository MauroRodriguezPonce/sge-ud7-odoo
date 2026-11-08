# Usuarios, grupos y permisos

## Usuarios

| Usuario | Puesto | Correo de acceso | Tipo | Grupos y privilegios por módulo | Justificación |
|---|---|---|---|---|---|
| Mauro Rodríguez Ponce | Responsable de ventas | mauro.rodriguez@gmail.com | Interno | Ventas: Administrador · Inventario: Usuario · Facturación: sin acceso | Ve todos los presupuestos, confirma pedidos y valida las entregas. No necesita facturar. |
| Marta Quintana | Comercial | marta.quintana@gmail.com | Interno | Ventas: Usuario, solo documentos propios · Facturación: sin acceso · Inventario: sin acceso | Solo crea y gestiona sus propios presupuestos. No necesita ver contabilidad ni stock. |
| Daniel Ferrer | Administración y facturación | daniel.ferrer@gmail.com | Interno | Facturación: Facturación · Ventas: Usuario, todos los documentos · Inventario: sin acceso | Crea la factura desde el pedido, la publica y registra el pago. No gestiona ventas (no es administrador de Ventas). |
| Hotel Mirador S.A. (contacto) | Cliente | hotelmirador@gmail.com | Portal | Acceso al portal web: solo sus propios presupuestos, pedidos y facturas | Es un cliente externo. Solo debe consultar sus documentos, sin acceder al backend. |

## Tipo de usuario asignado

- **Interno:** persona de la empresa con acceso al backend de Odoo (menús y aplicaciones). Su acceso se limita con grupos y permisos por aplicación. Lo tienen Mauro, Marta y Daniel porque son empleados que trabajan dentro de Odoo.
- **Portal:** persona externa, normalmente un cliente, que entra por la web para consultar y firmar sus propios documentos. No ve el backend. Lo tiene el contacto de Hotel Mirador S.A.
- **Público:** visitante anónimo del sitio web, sin cuenta ni login. No he asignado este tipo a nadie, porque todos los usuarios de la práctica tienen que iniciar sesión.