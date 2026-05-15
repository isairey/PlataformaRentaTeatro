<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/1048/1048941.png" />

# 🎭 AdamRMS

### Plataforma avanzada de gestión de renta para teatro, broadcast y producción audiovisual 🚀

<p align="center">
  <b>AdamRMS</b> es un sistema avanzado de Rental Management diseñado para empresas de producción, teatro, broadcast y renta de equipos audiovisuales, ofreciendo control centralizado de activos, proyectos, clientes y facturación.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Rental-Management-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/PHP-8.3-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/OpenSource-AGPL-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a> •
  <a href="#-arquitectura">Arquitectura</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**AdamRMS** es una plataforma web avanzada de administración de renta profesional enfocada en empresas de:

- 🎭 Teatro
- 📺 Broadcast
- 🎬 Producción audiovisual
- 🎤 Eventos
- 🎧 Audio profesional
- 🎥 Producción multimedia

La plataforma permite administrar:

- 📦 Equipos y activos
- 📊 Proyectos de producción
- 👥 Clientes
- 🧾 Facturación
- 👨‍🔧 Crew técnico
- 🏢 Multi-tenancy
- ☁️ Archivos cloud
- 🔐 Control administrativo

El sistema fue desarrollado bajo una arquitectura moderna enfocada en:

- ⚡ Escalabilidad
- 🔒 Seguridad
- 🌐 Gestión multiempresa
- 🧠 Modularidad
- 🚀 Alto rendimiento

---

# ✨ Características

## 📦 Gestión de activos

- 🏷️ Inventario de equipos
- 🔍 Escaneo QR y códigos de barras
- 🛠️ Programación de mantenimiento
- 📍 Control de ubicaciones
- 📊 Seguimiento de disponibilidad

---

## 🎬 Gestión de proyectos

- 📋 Organización de proyectos
- 🚚 Seguimiento de despacho
- 🎭 Gestión de producciones
- 📦 Asignación de equipos
- 📈 Control operativo

---

## 👥 Gestión de clientes

- 📇 Administración de clientes
- 📄 Historial de proyectos
- 📞 Información de contacto
- 📊 Relación cliente-producción
- 🧾 Gestión administrativa

---

## 👨‍🔧 Crew y entrenamiento

- 👷 Gestión de personal
- 📚 Registros de capacitación
- 🛠️ Asignación de crew
- 📋 Historial de entrenamiento
- 🔐 Roles y permisos

---

## 🏢 Multi-tenancy

- 🌐 Soporte multiempresa
- 🔒 Separación de instancias
- 👥 Usuarios compartidos
- 🧠 Permisos independientes
- 📊 Administración centralizada

---

## ☁️ Integraciones y cloud

- ☁️ AWS S3
- 📧 SendGrid / Mailgun / SMTP
- 💳 Stripe Billing
- 📡 API REST JSON
- 📂 Gestión documental

---

# 🛠️ Tecnologías utilizadas

## 🌐 Backend

<p>
  <img src="https://skillicons.dev/icons?i=php" />
</p>

- PHP 8.3
- Apache
- Arquitectura modular
- API RESTful

---

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,js" />
</p>

- Twig v3.7
- React
- Docusaurus
- Componentes reutilizables

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL 8
- Phinx Migrations
- Soft Deletes
- Persistencia relacional

---

## 🐳 DevOps

<p>
  <img src="https://skillicons.dev/icons?i=docker,github,git" />
</p>

- Docker Multi-Arch
- GitHub Actions
- CI/CD
- Git
- GitHub Packages

---

## ☁️ Servicios externos

- AWS S3
- Stripe
- SendGrid
- Mailgun
- Postmark
- Sentry

---

# 📂 Estructura del proyecto

```bash
adam-rms/
│
├── src/
│   ├── api/
│   ├── common/
│   ├── assets/
│   ├── project/
│   ├── clients/
│   ├── maintenance/
│   ├── instances/
│   ├── login/
│   └── server/
│
├── db/
│   ├── migrations/
│   └── seeds/
│
├── website/
│   ├── docs/
│   └── src/
│
├── .devcontainer/
├── Dockerfile
├── composer.json
│
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- Docker
- PHP 8.3
- MySQL 8
- Composer
- Git

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/adam-rms/adam-rms.git
```

---

## 2️⃣ Entrar al proyecto

```bash
cd adam-rms
```

---

## 3️⃣ Configurar entorno

Instalar dependencias:

```bash
composer install
```

---

## 4️⃣ Ejecutar Docker

```bash
docker compose up
```

---

## 5️⃣ Acceder al sistema

Aplicación disponible en:

```bash
http://localhost:8080
```

---

# 🐳 Desarrollo con DevContainer

## 🧠 Entorno listo para desarrollo

El proyecto incluye un entorno preconfigurado compatible con:

- GitHub Codespaces
- VS Code Dev Containers

---

## ⚙️ Servicios disponibles

| Servicio | Puerto | Descripción |
|---|---|---|
| PHP / Apache | 8080 | Aplicación |
| MySQL | 3306 | Base de datos |
| S3 Mock | 8081 | Simulación cloud |
| phpMyAdmin | 8082 | Administración DB |
| Mailpit | 8083 | Testing emails |

---

# 🧠 Arquitectura

## 🏗️ Arquitectura del sistema

AdamRMS utiliza una arquitectura server-rendered moderna:

### 🌐 Web Pages

- PHP Controllers
- Twig Rendering
- Bootstrap seguro

---

### 📡 API Layer

- API REST JSON
- OpenAPI Documentation
- Endpoints protegidos

---

### 🏢 Multi-tenancy

- Instancias independientes
- Permisos por empresa
- Usuarios multiempresa

---

### 🔐 Seguridad

- Sistema de autenticación
- Roles administrativos
- Soft deletes
- Gestión segura de sesiones

---

# 📸 Vista previa

<div align="center">

<img width="1000" src="https://images.unsplash.com/photo-1492691527719-9d1e07e534b4?q=80&w=1200&auto=format&fit=crop" />

</div>

---

# 📡 API REST

## 🔗 Integración OpenAPI

La plataforma incluye:

- 📄 API RESTful JSON
- 🔐 Endpoints protegidos
- 📊 Integración externa
- 🧠 Arquitectura modular

---

# ☁️ Self Hosting

## 🐳 Docker Ready

AdamRMS puede ejecutarse mediante:

- Docker
- Docker Compose
- GitHub Packages
- Infraestructura cloud

Compatible con:

- linux/amd64
- linux/arm64

---

# 🧠 Objetivos del proyecto

## 🎯 Aprender y practicar

- Arquitectura empresarial
- PHP avanzado
- Gestión audiovisual
- Multi-tenancy
- APIs REST
- Dockerización
- DevOps moderno

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- 🤖 Automatización inteligente
- 📊 Dashboard analítico
- 🔔 Notificaciones en tiempo real
- ☁️ Infraestructura cloud avanzada
- 🎥 Integración multimedia
- 📡 WebSockets

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por la creación de plataformas modernas, sistemas administrativos y aplicaciones empresariales escalables 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source bajo licencia GNU Affero General Public License v3.0 (AGPLv3).

---

<div align="center">

### 🎭 AdamRMS — gestión avanzada de renta audiovisual y producción 🚀

</div>
