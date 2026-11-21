MADUCAPP - PRIMERA INTERFAZ 0.1

Abrir index.html en el navegador. No requiere instalación ni conexión.
Datos ficticios. El selector superior cambia entre administrador y nutriólogo para probar la interfaz; NO es un inicio de sesión ni una protección de acceso.

RECORRIDO SUGERIDO
1. Clientes y planes: abrir Ana, revisar dashboard, corregir peso/agua y consultar historial.
2. Profesionales: crear profesional. En el perfil de cliente, asignarlo.
3. Cambiar vista a Nutriólogo: seleccionar profesional; solo se muestran sus clientes en la interfaz.
4. Abrir cliente y agregar nota. Volver a Administrador: aparece en bloque morado pendiente.
5. Cambiar estado de la nota; leerla no la cierra ni cambia porciones.
6. Cocina: marcar un pedido listo. Entregas: confirmar entrega. Solo entonces descuenta una comida, sin afectar checklist.
7. Insumos: revisar existencias, compras pendientes y recepción. El color compara stock con pedidos aún por preparar.
8. Servicios y pagos: registrar activo/inactivo. El cobro es externo.

ALCANCE
Prototipo local: persiste solo en este navegador. La fecha de jornada demo es 20/nov/2026 y hay un pedido posterior del 23/nov. No son clientes reales ni proyección de ventas.
El dashboard de seguimiento en el perfil es una primera vista para administración/profesional. No sustituye ni modifica SAN personal. No integra todavía el dashboard completo del cliente original.
No incluye autenticación, permisos del servidor, base de datos compartida, bloqueo real, correo, WhatsApp ni notificaciones fuera de esta pantalla.
Las porciones se editan para pedidos por preparar; al marcar listo se conserva una copia. Todavía falta programación por fecha de vigencia y el editor completo de planes.
El inventario se ajusta manualmente. Marcar listo no descuenta stock automáticamente. Compras no equivalen a recepción.
Los paquetes conservan conteo y entregas; faltan renovación, pausas, excepciones y ajustes manuales de saldo.
Historial de peso/agua, asignaciones y entregas de prueba; todavía falta incorporar todas las correcciones del cliente original.
No hay pasarela de pagos ni agentes IA.
No contiene información personal de SAN. No reemplazar SAN en GitHub.

PRUEBAS
Validadas funciones con datos simulados: vistas, notas, filtros y reasignación, historial, descuento único, separación del checklist, recepción de insumos y persistencia.
No se pudo ejecutar prueba visual en navegador automatizado por restricciones del entorno. Revisar tamaño móvil y escritorio antes de publicar.

ACTUALIZACIÓN: CALENDARIO DE MENÚ
- Nueva opción en administrador y nutriólogo: Calendario de menú.
- Vista semanal de lunes a viernes y vista mensual con todos los días.
- Flechas para navegar; seleccionar fecha para consultar cinco tiempos.
- Administración crea/edita platillos, guarnición, agua, colación de postre y estado.
- Nutriólogo consulta el menú común sin editarlo.
- Los menús iniciales son ficticios y están en borrador (23-27 nov. 2026).
- Los cambios se conservan en el mismo almacenamiento local del prototipo.
- Cambiar el menú no recalcula automáticamente inventario/recetas ni cambia las órdenes ya creadas. Esa integración está pendiente.

Recordatorios de calendario por fecha, únicos o semanales, visibles en la app.
Mesa de porcionado: seleccionar fecha, consultar gramos por pedido y marcar listo.
Perfil nutricional: administración programa una versión con porciones, indicaciones y rutina.
La fecha del pedido determina la versión aplicable. Los pedidos listos conservan sus gramos.
