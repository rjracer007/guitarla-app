# 🎸 GuitarLA - Tienda de Guitarras

GuitarLA es una aplicación de comercio electrónico diseñada para entusiastas de la música, donde los usuarios pueden explorar un catálogo de guitarras exclusivas, gestionar su carrito de compras y ver detalles específicos de cada producto.

![Preview GuitarLA](https://via.placeholder.com/800x400?text=GuitarLA+Store+Front)

## 🛒 Características del Proyecto

- **Catálogo Dinámico:** Visualización de una colección de guitarras con sus especificaciones y precios.
- **Carrito de Compras Completo:**
  - **Agregar Productos:** Sistema inteligente que detecta si un ítem ya existe para aumentar su cantidad.
  - **Gestión de Cantidades:** Incrementar o decrementar productos directamente desde el carrito.
  - **Eliminación:** Quitar productos individuales o vaciar el carrito por completo.
- **Cálculo de Total:** Actualización automática del monto total a pagar en tiempo real.
- **Persistencia de Datos:** Integración con `localStorage` para que los usuarios no pierdan su carrito al recargar la página.
- **Diseño Atractivo:** Interfaz moderna orientada a la conversión y experiencia de usuario.

## 🛠️ Tecnologías

- **React.js**: Framework principal para la interfaz.
- **TypeScript**: (Opcional, ajustar si aplica) Para un desarrollo con tipado seguro.
- **Custom Hooks**: Uso de un hook personalizado (`useCart`) para centralizar toda la lógica del carrito.
- **Tailwind CSS / CSS Modules**: Para un estilizado rápido y profesional.
- **JSON / API**: Consumo de datos de guitarras (pueden ser locales o mediante una API).

## 🚀 Instalación

1. **Clonar el proyecto:**
   ```bash
   git clone [https://github.com/rjracer007/guitarla-app.git](https://github.com/rjracer007/guitarla-app.git)
