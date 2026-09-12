# 🍕 Miche Pizza - Web App de Pedidos

Aplicación web interactiva para la personalización y pedido de pizzas en línea para **Miche Pizza**, optimizada para dispositivos móviles y computadoras de escritorio. Permite armar pedidos paso a paso y enviarlos directamente a la línea de atención de WhatsApp con todos los detalles calculados.

🌐 **Sitio en vivo:** [https://michepizza.github.io/miche-pizza-web/](https://michepizza.github.io/miche-pizza-web/)

---

## 📋 Características Principales

* **Flujo guiado paso a paso:**
  * Selección de tamaño (Personal, Mediana, Grande, Extragrande).
  * Modalidad de preparación (Un solo sabor o Mitad y Mitad / Combinada).
  * Catálogo visual interactivo con ingredientes y estado de inventario (soporte para productos agotados).
  * Selección de bordes adicionales con cálculo dinámico de precio según el tamaño seleccionado.
* **Carrito de compras lateral:**
  * Modificación de cantidades y eliminación de ítems en tiempo real.
  * Resumen dinámico de precios, adiciones y costos de envío.
* **Formulario de entrega y validaciones:**
  * Modalidades: Domicilio o Recoger en tienda.
  * Cobertura de domicilios por barrios y cálculo de recargo según zona.
  * Medios de pago: Transferencia bancaria o Efectivo (con validación de monto mínimo para cálculo de cambio).
* **Integración con WhatsApp:** Generación automática de un mensaje formateado y estructurado con el resumen completo del pedido listo para despachar.
* **Información y contacto:** Pie de página persistente con ubicación del local y enlace directo a WhatsApp.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica accesible con soporte para imágenes optimizadas.
* **CSS3:** Diseño responsivo (Mobile First), variables nativas CSS, animaciones sutiles y maquetación con Flexbox/Grid.
* **JavaScript (ES6+):** Lógica de negocio en el cliente, manipulación del DOM y validaciones en tiempo real sin dependencias externas.
* **Font Awesome:** Iconografía de interfaz, contacto y redes.
* **GitHub Pages:** Despliegue continuo y hosting estático.

---

## 📁 Estructura del Repositorio

```text
Miche-Pizza/
├── assets/             # Imágenes de productos, banners y logos
├── css/
│   └── style.css       # Estilos globales y reglas de adaptabilidad móvil
├── font/               # Tipografías personalizadas
├── js/
│   ├── app.js          # Lógica de la app, estado del carrito y eventos
│   └── products.js     # Datos del menú (precios, sabores, adiciones)
├── index.html          # Vista principal de la aplicación
└── README.md           # Documentación del proyecto
