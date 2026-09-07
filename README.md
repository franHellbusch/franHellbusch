# Hi, I'm Francisco Hellbusch 👋

**Backend Developer · NestJS · TypeScript · Clean Architecture**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fhdeveloper/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fghellbusch@gmail.com)
[![Domit.app](https://img.shields.io/badge/Domit.app-0D7377?style=for-the-badge&logo=google-chrome&logoColor=white)](https://domit.app)

---

Desarrollador Backend con foco en **arquitectura de software** y construcción de sistemas end-to-end. Diseño y desarrollo aplicaciones completas — desde el modelo de dominio hasta el deploy — aplicando **Clean Architecture y DDD** de forma consistente.

Combino la práctica freelance con un rol activo como **Instructor Full Stack en Henry**, donde formo grupos de hasta 40 personas en el stack moderno.

---

### 🚀 Lo que hago

- **Arquitectura de software:** Diseño sistemas con Clean Architecture y DDD — domain en TypeScript puro, sin dependencias de framework. Tests del dominio sin infraestructura. Use cases que dependen de interfaces (Ports), no de implementaciones concretas.
- **Backend:** APIs REST con NestJS, Prisma y PostgreSQL. Auth con JWT, RBAC, transacciones atómicas, sistemas multi-tenant con isolation por tenant_id en repository layer.
- **Frontend:** Interfaces con Next.js 15 (ISR/SSR/SPA según el caso), React 19, TanStack Query, Zustand y Tailwind CSS.
- **Monorepos:** Turborepo con paquetes compartidos (domain, database, ui) consumidos por múltiples apps.
- **Documentación técnica:** ADRs con contexto y alternativas evaluadas — no solo "qué" sino "por qué".

---

### 🛠️ Stack

**Backend**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)

**Arquitectura & Tooling**

![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

#### [Domit](https://domit.app) — SaaS Inmobiliario Multi-tenant

Plataforma SaaS B2B para inmobiliarias, en producción con primer cliente (Urcola Inmobiliaria).
API NestJS con **dominio en TypeScript puro** (sin imports de NestJS, Prisma ni Express). Sistema de tenancy con Guard que valida tenant_id del JWT, Decorator que lo propaga al ExecutionContext, y filtrado por tenant_id en repository layer. RBAC multi-rol. **Provisioning atómico** de tenants (Tenant + Subscription + TenantConfig + User ADMIN + AuditLog) en una transacción Prisma, donde el use case del dominio define un `IProvisionTenantPort` que la infraestructura implementa (Ports & Adapters). Web pública ISR por tenant + backoffice SPA. CI/CD con Vercel preview environments. **244 tests** del dominio. **TypeScript beyond-strict** (`noUncheckedIndexedAccess` + `exactOptionalPropertyTypes`).

`NestJS` `Prisma` `PostgreSQL` `Next.js 15` `TypeScript strict` `Turborepo` `Vercel`

🔗 [Showcase público](https://github.com/franHellbusch/domit-showcase) (slice del módulo de provisioning extraído del repo de producción)

---

### 📬 Contacto

- 📧 **Email:** [fghellbusch@gmail.com](mailto:fghellbusch@gmail.com)
- 💼 **LinkedIn:** [linkedin.com/in/fhdeveloper](https://www.linkedin.com/in/fhdeveloper/)
- 📍 **Ubicación:** Córdoba, Argentina · Disponible para roles remotos
