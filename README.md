# Gestor de Pedidos PROCOVAR

Aplicación web para gestionar pedidos, inventario y envío por WhatsApp. Interfaz móvil optimizada y datos persistentes en localStorage.

## ✨ Características

- 📝 **Gestión de Pedidos**: Crear, confirmar y enviar pedidos
- 📦 **Control de Inventario**: Agregar, editar y eliminar productos
- 💬 **Integración WhatsApp**: Enviar pedidos directamente a clientes
- 📤 **Exportación Masiva**: Enviar múltiples pedidos en un mensaje formateado
- 👤 **Perfil del Gestor**: Configurar nombre y datos del vendedor
- 📱 **UI Responsiva**: Optimizada para móvil y escritorio
- 💾 **Persistencia**: Todos los datos se guardan en localStorage

## 🚀 Cómo Usar

### Abrir la Aplicación
1. Descargar o clonar el repositorio
2. Doble clic en `index.html` o abrir en navegador
3. No requiere servidor ni instalación

### Primer Uso
1. Configurar nombre del gestor en panel superior
2. Agregar o editar productos en inventario
3. Crear pedidos con cliente, teléfono y productos
4. Enviar por WhatsApp o exportar todos

## 📋 Funcionalidades

### Panel de Pedidos
- Input cliente con autocomplete
- Seleccionar teléfono y tipo de entrega
- Agregar múltiples productos por pedido
- Validación automática de stock
- Tabla con todos los pedidos del día

### Inventario
- Vista de stock en tiempo real
- Agregar nuevos productos (`CODIGO, CANTIDAD`)
- Editar código y cantidad
- Eliminar productos
- Alertas de stock crítico

### Exportación
- Botón "Enviar Todos" con selección de pedidos
- Formato automático agrupado por entrega tipo
- Abre WhatsApp Web con mensaje listo
- Incluye nombre del gestor y fecha

## 🔧 Tecnología

- **HTML5** - Estructura y semántica
- **CSS3** - Estilos con Dark Mode y responsive
- **Vanilla JavaScript** - Sin dependencias
- **localStorage API** - Persistencia local

## 📱 Compatibilidad

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Funciona en móviles y tablets

## 💾 Datos

Todos los datos se guardan localmente en el navegador:
- Inventario
- Pedidos del día
- Nombre del gestor
- Historial de clientes

**Nota**: Limpiar caché del navegador elimina los datos.

## 🎨 Interfaz

- Dark mode por defecto
- Colores accesibles
- Touch-friendly en móvil
- Botones grandes (44-48px)
- Inputs con tamaño optimizado

## 📝 Notas

- No requiere conexión a internet para guardar
- WhatsApp debe estar disponible en el dispositivo
- Compatible con WhatsApp Web o WhatsApp Desktop
- Los datos persisten entre sesiones

## 📄 Licencia

Uso libre para PROCOVAR

---

Creado: Julio 2026 | Versión: 2.0
