# 🍽️ Proyecto de Gestión de Pedidos para Restaurantes

Una solución web para que los restaurantes gestionen pedidos de forma moderna, dinámica e interactiva con sus clientes. Desde pedidos por mesa hasta seguimiento en tiempo real.

---

## 🚀 Funcionalidades clave del MVP

- Gestión de restaurante, mesas y productos
- Visualización del menú mediante QR por parte del cliente
- Pedidos desde la mesa (sin mozos)
- Estado de pedido en tiempo real (pendiente, preparando, listo)
- Cierre de cuenta por parte del cliente
- Panel de administración para el restaurante

---

## 🧭 Roadmap y Sprints

### ✅ Sprint 0: Preparación del proyecto (1 semana)

- Configurar Laravel Breeze (React + Tailwind)
- Configurar Laravel Reverb (eventos en tiempo real)
- Crear migraciones iniciales
- Setup local (Docker/Sail)

---

### 🧾 Sprint 1: Gestión de restaurante y productos (2 semanas)

- CRUD restaurante
- CRUD mesas
- CRUD productos
- Roles de usuario (admin / cliente)

---

### 🧾 Sprint 2: Flujo básico del cliente (2 semanas)

- Escaneo de QR por mesa
- Página pública con menú
- Crear pedido desde el cliente
- Visualización del pedido

---

### 🧾 Sprint 3: Gestión de pedidos en cocina (2 semanas)

- Panel del restaurante con pedidos activos
- Actualización de estado del pedido
- Notificaciones al cliente en tiempo real

---

### 🧾 Sprint 4: Cierre y pago de cuenta (1 semana)

- Botón "Cerrar cuenta"
- Mostrar total
- Marcar cuenta como pagada

---

## 🧰 Requisitos no funcionales

- Bajo costo: herramientas gratuitas y open-source
- Seguridad básica por roles y middleware
- Estructura monolítica con Laravel + React

---

## 💡 Stack tecnológico

- Backend: Laravel 11
- Frontend: React (Laravel Breeze)
- Estilos: Tailwind CSS
- Eventos: Laravel Reverb
- Base de datos: MySQL o SQLite
- Hosting (futuro): Fly.io, Render o VPS (DigitalOcean)

---

## 🧱 Ideas futuras (Post-MVP)

- Múltiples restaurantes con multi-tenancy
- Pagos online
- Soporte para impresión de pedidos en cocina
- Dashboard con analíticas

---

## 🧑‍💻 Autor

Santiago Molano – [Portfolio](https://molxno.dev/)
