# Alabama Store — Sistema de gestión de ventas, stock y caja

Trabajo Final Integrador — Tecnicatura Universitaria en Programación a Distancia — UTN

## Descripción

Sistema de gestión para Alabama Store, un local de indumentaria que hoy administra ventas, stock y caja mediante planillas de Excel y etiquetado manual. El proyecto digitaliza y ordena ese flujo, con foco en:

- Control de stock por variante (talle y color)
- Registro de ventas con descuento automático de stock
- Roles diferenciados: dueña (acceso completo) y empleada (acceso operativo)

## Integrantes

- Santiago Bongiorno
- Valeria Arellano

## Tutora

- Maria Candela Grosso

## Alcance del proyecto

### MVP (funcionalidades mínimas y prioritarias)

**Gestión de Stock**
- Alta de productos
- Registro de variantes por talle y color
- Consulta de stock disponible
- Actualización manual de cantidades

**Gestión de Ventas**
- Carrito de productos
- Registro de venta
- Descuento automático de stock al confirmar la venta

**Roles y autenticación**
- Login diferenciado entre dueña y empleada
- Visibilidad restringida de costos y ganancias para el rol empleada

### Funcionalidades secundarias (no forman parte del MVP)

- **Señas:** apartar un producto, reforzar seña, retirar con saldo pendiente
- **Cambios:** registrar devolución o cambio de un producto ya vendido
- **Caja:** apertura y cierre de caja, arqueo diario, registro de movimientos por tipo de pago
- **Reposición:** aviso cuando se vende un producto exhibido y hay stock en otra ubicación del local
- **Reportes:** ranking de productos, ganancias por período

### Fuera de alcance

- Venta online al público / e-commerce con pago online
- Facturación electrónica / integración con AFIP
- Gestión multi-sucursal (el negocio opera actualmente en un solo local)

## Tecnologías

| Capa | Tecnología |
|---|---|
| Frontend | TypeScript + Vite |
| Backend | Spring Boot + JPA |
| Base de datos | PostgreSQL |
| Deploy | Vercel (frontend) · Render (backend) · Supabase (base de datos) |

## Estructura del repositorio

```
/frontend    → aplicación TypeScript + Vite
/backend     → API Spring Boot + JPA
/docs        → informes, esquemas de avance y entregas
```

## Instalación y ejecución local

### Requisitos previos
- Node.js 18+
- Java 17+
- PostgreSQL

## Estado del proyecto

🚧 En desarrollo — Trabajo Final Integrador, UTN.
