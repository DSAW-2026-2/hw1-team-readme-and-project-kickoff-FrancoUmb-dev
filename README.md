# ConectaNegocio

Aplicación web que conecta pequeños comercios con sus proveedores para comparar ofertas, conversar en contexto y hacer seguimiento a pedidos y entregas — sin cambiar de plataforma.

## Problema

Los administradores de pequeños comercios (por ejemplo, una papelería de barrio) que compran productos a varios proveedores no cuentan con un espacio centralizado para:

- Comparar ofertas equivalentes de distintos proveedores (precio, presentación, cantidad mínima, tiempo de entrega).
- Conservar la conversación comercial asociada a cada oferta o pedido específico.
- Consultar el estado de sus pedidos y registrar entregas completas o parciales.

Hoy esa información está repartida entre llamadas, mensajes de WhatsApp, notas sueltas y una plataforma de ventas/inventario que no cubre el proceso de abastecimiento con proveedores. Esto obliga a comparar y hacer seguimiento manualmente, consume tiempo y hace fácil perder el contexto de lo acordado.

## Justificación de aplicación web

No basta con una hoja de cálculo, un grupo de WhatsApp o la herramienta de ventas que ya usa el comercio:

1. **Permisos diferenciados por organización.** Una hoja de cálculo no distingue de forma natural entre lo que puede ver/editar un comerciante y lo que puede ver/editar cada proveedor; una app web sí puede aplicar roles y permisos reales en el backend.
2. **WhatsApp organiza por contacto, no por negociación.** Las conversaciones quedan sueltas por chat, no vinculadas a una oferta o un pedido concreto, así que comparar proveedores implica saltar entre chats y perder contexto.
3. **La herramienta de ventas existente resuelve otro momento del negocio** (registrar ventas e inventario interno), no la relación previa y posterior con el proveedor (comparar, conversar, hacer seguimiento).
4. **Acceso multi-dispositivo sin instalar nada.** Tanto el comerciante como el proveedor pueden entrar desde computador, tableta o celular con el mismo estado sincronizado, sin depender de una app nativa instalada por cada actor.

## Usuarios objetivo

- **Comerciantes:** administradores o propietarios de pequeños comercios (ej. una papelería de barrio) que compran productos a varios proveedores de forma recurrente.
- **Proveedores/distribuidores:** publican productos, reciben pedidos de esos comercios y gestionan su preparación, despacho y entrega.

No es "cualquier negocio" ni "cualquier persona": la primera versión se diseña para este par de roles y este flujo de abastecimiento.

## Historias de usuario

1. Como comerciante, quiero crear una cuenta con mi comercio para acceder a las funciones propias de mi rol.
2. Como comerciante, quiero comparar varias ofertas de un mismo producto para decidir con mejor información sin consultar cada proveedor por separado.
3. Como comerciante, quiero iniciar un chat desde una oferta específica para que el proveedor sepa exactamente a qué producto me refiero.
4. Como comerciante, quiero confirmar las cantidades que recibí de un pedido para poder distinguir entregas completas de entregas parciales.
5. Como proveedor, quiero actualizar el estado de preparación y despacho de un pedido para mantener informado al comerciante sin que tenga que preguntar.

## Roles del equipo

| Integrante | Rol | Responsabilidades |
|---|---|---|
| Sebastian Franco Umbacia | Soporte transversal | Diseño, código, Git |
| Alejandro Caycedo | Apoyo en Figma / diseño | [completar] |
| Catalina Vega Romero | Figma / UX lead | [completar] |
| Jose [FALTA APELLIDO] | Estructura del proyecto / documentación | [completar] |

## Registro de uso de IA

- **Prompt exacto utilizado:** el equipo usó Claude (Anthropic) a lo largo de varias sesiones para redactar el planteamiento del problema y las historias de usuario a partir de las notas de clase sobre el caso de la papelería, para generar el esqueleto HTML semántico, y para organizar la secuencia de tareas del curso semana a semana.
- **Qué cambió respecto a lo que generó la IA:** se reemplazaron ideas de proyecto iniciales (seguimiento de tesis, mantenimiento de conjuntos) por la que sí se validó con el caso real discutido en clase; se corrigieron los identificadores de código a inglés; se completaron los nombres reales del equipo.
- **Por qué se hicieron esos cambios:** para que el documento reflejara el problema realmente validado por el equipo y no un ejemplo genérico, y para cumplir la convención de idioma del curso.

## Deploy

- GitHub Pages: *(lo agregamos cuando lo activemos)*
- Figma: ver `figma-link.txt`