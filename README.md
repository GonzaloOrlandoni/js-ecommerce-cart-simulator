# 🛒 Simulador Interactivo de Carrito de Compras (JS Puro)

## 🎯 OBJETIVO: Lógica de Aplicación y Persistencia de Datos

Este proyecto es un simulador de carrito de compras implementado con HTML, CSS, y JavaScript puro. Demuestra la capacidad de implementar la **lógica de negocio** fundamental para e-commerce, enfocándose en la manipulación dinámica del DOM y la persistencia del estado de la aplicación.

### Funcionalidades Clave:

- **Carga de Datos:** Los productos se cargan de forma asíncrona desde el archivo local `data.json` utilizando `fetch`.
- **Persistencia de Datos:** El estado del carrito (productos, cantidades y totales) se guarda y recupera utilizando la API **`localStorage`**, manteniendo el estado incluso al recargar la página.
- **Gestión de Eventos:** Manejo de eventos del DOM para añadir, eliminar y actualizar productos de forma dinámica.
- **Cálculo Dinámico:** Recálculo instantáneo del total de la compra, incluyendo la aplicación de cupones de descuento.
- **Interacción Mejorada:** Uso de librerías externas (SweetAlert2 y Toastify) para ofrecer notificaciones al usuario.

## 💻 STACK TÉCNICO

- **Tecnología Principal:** JavaScript (ES6+).
- **Persistencia:** `localStorage` API.
- **Estructura:** HTML5 Semántico.
- **Estilos:** CSS3 (Carpeta `CSS`).
- **Librerías:** SweetAlert2 y Toastify.js (CDN).

---

### Notas de Despliegue (Vercel)

1.  **Rutas Sensibles a Mayúsculas:** Las rutas como `./CSS/style.css` son sensibles a mayúsculas en servidores Linux (usados por Vercel). Esta versión ya tiene la corrección.
2.  **`data.json`:** El archivo `data.json` debe estar en la carpeta raíz (junto a `index.html`) para que el `fetch` funcione correctamente.

Para ejecutar, sube todos estos archivos a tu repositorio y despliega en Vercel.
