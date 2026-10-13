# Surtidora Emmanuel — Panel de administración

Vista previa (prototipo) de la app de administración para Surtidora Emmanuel.

## Módulos
- **Resumen**: KPIs de cartera, cobranza semanal, productos por resurtir y cobros pendientes.
- **Clientes**: perfiles con límite de crédito, calificación y historial.
- **Estados de cuenta**: cargos, abonos y saldo por cliente; imprimible a PDF.
- **Inventario**: existencias, márgenes, alertas de stock y ajustes.
- **Créditos**: ventas a plazos con enganche, recargo y abonos semanales.
- **Préstamos**: préstamos en efectivo con interés mensual y frecuencia de pago.

## Usuarios y roles
Al abrir la app se pide iniciar sesión. El primer acceso es `admin` / `admin123` y obliga a cambiar la contraseña.
Solo el **Administrador** crea y gestiona usuarios en el módulo **Usuarios**. Al crear o editar a alguien elige:
- **Administrador**: entra a todo y puede gestionar usuarios.
- **Elegir módulos**: marca uno por uno a qué módulos puede entrar (Cobranza, Catálogo, Clientes, Créditos, Préstamos,
  Estados de cuenta, Reportes, Inventario, Configuración). Inicio siempre está disponible. Hay atajos para marcar
  los módulos típicos de un vendedor o un cobrador.

Cada usuario recibe una contraseña temporal que debe cambiar al entrar.

Las notas de cobro registran el nombre de quien cobró. En este prototipo los usuarios se guardan en el navegador;
en la versión final la validación debe hacerse en un servidor.

## Uso
Abrir `index.html` en el navegador. No requiere instalación.
Los datos son de ejemplo y se reinician al recargar la página.
