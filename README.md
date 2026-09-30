# Carrito de Compras 🚲

Tienda en línea de bicicletas desarrollada como proyecto de práctica, donde el usuario puede ver un catálogo de productos y agregarlos a un carrito de compras.

## Descripción

Este proyecto consiste en un **frontend** que consume una API propia (Node.js + MySQL) para mostrar un catálogo de bicicletas, con funcionalidad de carrito de compras: agregar productos, ver el total y gestionar las unidades.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- Fetch API para consumo de datos
- LocalStorage para persistencia del carrito

## Funcionalidades

- 🛍️ Catálogo de productos cargado dinámicamente desde una API
- 🛒 Carrito de compras: agregar, ver unidades y calcular totales
- 💾 Persistencia del carrito usando LocalStorage
- 📱 Interfaz responsive

## Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/felipe-094/bicicletas-frontend.git
   ```
2. Abre la carpeta del proyecto en VS Code.
3. Asegúrate de tener corriendo el [backend](https://github.com/felipe-094/bicicletas-backend) en el puerto 4000.
4. Usa la extensión **Live Server** para abrir `index.html` (o cualquier servidor local).

## Estructura del proyecto

```
front/
├── img/
│   ├── iconos/
│   └── logo.png
├── js/
│   ├── cart.js
│   ├── cartService.js
│   ├── index.js
│   └── productosService.js
├── cart.html
├── cart.css
├── index.html
├── index.css
└── style.css
```

## Autor

**Luis Felipe Balanta Quintero**
Desarrollador Fullstack (React, Node.js)

- GitHub: [@felipe-094](https://github.com/felipe-094)
- LinkedIn: [Felipe Quintero](https://www.linkedin.com/in/felipe-quintero-8b99812a1/)

## Proyecto relacionado

- [Backend del carrito de compras](https://github.com/felipe-094/bicicletas-backend) — API con Node.js y MySQL
