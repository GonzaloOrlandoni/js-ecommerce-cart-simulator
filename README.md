# 🛒 Simulador Interactivo de Carrito de Compras (JS Puro)

## 🎯 OBJETIVO: Lógica de Aplicación y Persistencia de Datos

Este proyecto es un simulador de carrito de compras implementado con HTML, CSS, y JavaScript puro. Se ha refactorizado para eliminar dependencias externas (como `fetch` a `data.json`) y usar **módulos de JavaScript** para asegurar la estabilidad en entornos de despliegue como Vercel.

### Funcionalidades Clave:

- **Estructura Modular:** Los datos de los productos se separan en `js/productos.js` y se importan, resolviendo problemas de rutas 404 en el servidor.
- **Persistencia de Datos:** El estado del carrito se guarda y recupera utilizando la API **`localStorage`**.
- **Gestión de Eventos:** Manejo de eventos del DOM para añadir, eliminar y actualizar productos.
- **Cálculo Dinámico:** Recálculo instantáneo del total de la compra, incluyendo la aplicación de cupones de descuento.

## 💻 STACK TÉCNICO

- **Tecnología Principal:** JavaScript (ES6+) con estructura de Módulos (`import/export`).
- **Persistencia:** `localStorage` API.
- **Librerías:** SweetAlert2 y Toastify.js (CDN).

---

### Pasos para Ejecutar

1.  Asegúrate de que la estructura de carpetas coincida con la raíz del repositorio.
2.  Abre `index.html` en tu navegador o sube el proyecto completo a Vercel.
