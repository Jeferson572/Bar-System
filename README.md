# 🍺 Bar System

Sistema ERP / POS para gestión de bares y restaurantes.

Este proyecto está construido con una arquitectura **modular, escalable y profesional** utilizando tecnologías modernas como **Next.js, NestJS, Prisma y PostgreSQL**.

---

# 📌 Tecnologías

## Frontend

* Next.js 14+
* React 18+
* TypeScript
* Tailwind CSS
* Zustand (State Management)
* React Query
* Axios
* Zod

## Backend

* NestJS
* TypeScript
* Prisma ORM
* PostgreSQL
* JWT Authentication
* Class Validator

## Monorepo

* PNPM Workspaces
* Monorepo Architecture

## Base de Datos

* PostgreSQL
* Prisma ORM

## DevOps

* Docker (Opcional)
* GitHub
* ESLint
* Prettier

---

# 🧱 Arquitectura del Proyecto

```
bar-system/
│
├── apps/
│   ├── web/        → Frontend Next.js
│   └── api/        → Backend NestJS
│
├── packages/       → Código compartido
│   ├── ui/
│   ├── types/
│   ├── utils/
│   └── config/
│
├── prisma/         → Configuración base de datos
│
├── docker/         → Configuración contenedores
│
├── package.json
└── pnpm-workspace.yaml
```

---

# 🧠 Arquitectura General

El sistema sigue una arquitectura:

* Monorepo
* Modular Architecture
* Clean Architecture (Backend)
* Feature-Based Architecture (Frontend)

Flujo del sistema:

```
Frontend (Next.js)
        ↓
Backend (NestJS)
        ↓
Prisma ORM
        ↓
PostgreSQL
```

---

# 📦 Aplicaciones

## Web App

Ubicación:

```
apps/web
```

Tecnología:

* Next.js App Router
* TypeScript
* Tailwind

Estructura:

```
src/
├── app/
├── components/
├── hooks/
├── services/
├── store/
├── lib/
├── types/
├── validators/
└── config/
```

---

## API

Ubicación:

```
apps/api
```

Tecnología:

* NestJS
* Prisma
* PostgreSQL

Arquitectura modular:

```
modules/
├── auth/
├── usuarios/
├── ventas/
├── productos/
├── inventario/
├── compras/
├── clientes/
├── proveedores/
├── caja/
├── finanzas/
└── reportes/
```

---

# 🗄️ Base de Datos

ORM:

* Prisma

Ubicación:

```
prisma/schema.prisma
```

Base de datos:

* PostgreSQL

---

# 🚀 Instalación

Clonar repositorio:

```
git clone https://github.com/tu-repo/bar-system.git
```

Entrar al proyecto:

```
cd bar-system
```

Instalar dependencias:

```
pnpm install
```

---

# ⚙️ Configuración

Crear archivo `.env`

Ejemplo:

```
DATABASE_URL="postgresql://user:password@localhost:5432/bar"
```

---

# 🏃 Ejecutar Proyecto

## Ejecutar Frontend

```
cd apps/web
pnpm dev
```

## Ejecutar Backend

```
cd apps/api
pnpm start:dev
```

---

# 📦 Packages Compartidos

```
packages/
├── ui
├── types
├── utils
└── config
```

Estos paquetes serán compartidos entre:

* Frontend
* Backend

---

# 👥 Trabajo en Equipo

Flujo recomendado:

Crear rama:

```
git checkout -b feature/nombre-feature
```

Commit:

```
git commit -m "feat: nueva funcionalidad"
```

Push:

```
git push origin feature/nombre-feature
```

Pull Request:

* Crear PR
* Code Review
* Merge

---

# 🧪 Testing (Pendiente)

Se agregará:

* Jest
* Testing Library
* E2E Testing

---

# 🔐 Autenticación

Se implementará:

* JWT
* Refresh Token
* Roles
* Permisos

---

# 📊 Módulos del Sistema

El sistema incluirá:

* Auth
* Usuarios
* Negocios
* Sucursales
* Productos
* Inventario
* Ventas
* Compras
* Clientes
* Proveedores
* Caja
* Finanzas
* Reportes

---

# 📈 Escalabilidad

Este proyecto está diseñado para:

* Multi negocio
* Multi sucursal
* SaaS
* POS profesional

---

# 🧑‍💻 Equipo

Proyecto desarrollado por:

* Equipo Bar System

---

# 📄 Licencia

MIT

---

# 🚀 Estado del Proyecto

En desarrollo
