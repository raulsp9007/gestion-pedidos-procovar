=====================================
GESTOR DE PEDIDOS - VERSIÓN SIMPLE
=====================================

📱 ABRIR:
---------
1. Doble clic en: index.html
   (Se abre en navegador automáticamente)

2. O clic derecho → Abrir con → Chrome/Firefox/Edge


⚙️ FUNCIONES:
--------------
✅ Crear pedidos nuevos
✅ Agregar múltiples productos por pedido
✅ Validación automática de stock
✅ Autocomplete de clientes (historial)
✅ Enviar pedidos por WhatsApp
✅ Editar inventario
✅ Ver todos los pedidos del día
✅ Guardado automático (en navegador)


📲 ENVIAR POR WHATSAPP:
-----------------------
1. Agrega un pedido
2. En tabla "Pedidos del Día", clic botón 💬 verde
3. Se abre WhatsApp Web automáticamente
4. Mensaje ya está formateado
5. Solo clic "Enviar"

Requiere: WhatsApp Web en navegador (wa.web.whatsapp.com)
O: WhatsApp Desktop instalada


📦 INVENTARIO:
---------------
Productos iniciales:
- M300 (50 unidades)
- M330 (100 unidades)
- P330 (80 unidades)
- P500 (60 unidades)
- P1000 (40 unidades)
- P1500 (30 unidades)

Editar stock: Clic ✏️ en cada producto


🎨 DATOS GUARDADOS:
--------------------
Todo se guarda automáticamente en localStorage
(No necesita internet para guardar)

Si limpias caché del navegador: PIERDES datos
Recomendación: exporta regularmente


🔧 AGREGAR MÁS PRODUCTOS:
--------------------------
Editar archivo index.html, busca:

    let inventario = {
        'M300': 50, 'M330': 100, ...
    };

Agrega: 'CODIGO': cantidad,


📞 SOPORTE:
-----------
- Cierra y abre navegador si hay errores
- Intenta en otro navegador (Chrome recomendado)
- Verifica que JavaScript esté activado


¡LISTO PARA USAR!
================

Creado: Julio 2026
Versión: 1.0
