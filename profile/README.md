# 🦔 SliceSoft - Desarrollo Modular y Ágil

Bienvenido al repositorio `.github` de **SliceSoft**, donde centralizamos la documentación, plantillas y procesos para la organización. Aquí encontrarás información sobre nuestra visión, contribuciones, código de conducta y otros recursos clave.

---

## 🚀 ¿Qué es SliceSoft?

**SliceSoft** es una fábrica de software enfocada en el desarrollo **ágil y modular** de aplicaciones, utilizando **componentes reutilizables** como módulos de Lego. Nos especializamos en arquitecturas modernas como **microservicios, microfrontends y web components**, empleando tecnologías como:

- **Backend:** Golang (Fiber), NestJS (Node.js), FastAPI (Python).
- **Frontend:** Angular, React, Stencil.
- **Infraestructura:** Docker, Kubernetes, Terraform, CloudFront (AWS).
- **Automatización y DevOps:** CI/CD, GitHub Actions, IaC.

Nuestro objetivo es ofrecer soluciones altamente escalables y personalizables, optimizando la experiencia de desarrollo para nuestros clientes y partners.

---

## 📌 Contenido del Repositorio

Este repositorio contiene archivos y configuraciones globales utilizadas en la organización, incluyendo:

- **Plantillas de Issues y Pull Requests**: Para mantener estándares en la gestión de proyectos.
- **Guías de Contribución**: Reglas y mejores prácticas para colaborar en nuestros proyectos.
- **Código de Conducta**: Normas para fomentar un ambiente de respeto y colaboración.
- **Acciones de GitHub**: Workflows predefinidos para mejorar la eficiencia del desarrollo.

---

## 🏗 Arquitectura de la Plataforma

SliceSoft adopta un enfoque basado en **microservicios**, organizando nuestras aplicaciones en diferentes dominios. A continuación, un resumen de nuestros servicios clave:

| Microservicio   | Tecnología | Función |
|----------------|------------|----------------|
| **Auth**  | NestJS | Manejo de autenticación y roles |
| **Users**  | Go + Fiber | Gestión de perfiles de usuario |
| **Orders**  | Go + Fiber | Creación y seguimiento de órdenes |
| **Payments**  | NestJS | Integración con pasarelas de pago |
| **Subscriptions**  | Go + Fiber | Administración de suscripciones |
| **Workshops**  | Go + Fiber | Coordinación de talleres aliados |
| **Notifications**  | NestJS + Nodemailer | Envío de correos y SMS |
| **Reports/Analytics**  | Python + FastAPI | Generación de reportes y métricas |

Cada microservicio es independiente y se comunica a través de **RabbitMQ** en un modelo **event-driven**. Para exponer APIs a clientes, utilizamos un **API Gateway** basado en NestJS o Kong.

---

## 🛠 Contribuyendo

Si deseas contribuir a nuestros proyectos, revisa nuestra [Guía de Contribución](CONTRIBUTING.md). Algunas formas de ayudar incluyen:

- Reportar bugs o sugerencias en **Issues**.
- Contribuir con código en nuestros repositorios.
- Proponer mejoras en nuestras **documentaciones**.

---

## ⚖️ Código de Conducta

Fomentamos un ambiente inclusivo y respetuoso para todos. Consulta nuestro [Código de Conducta](CODE_OF_CONDUCT.md) para más detalles.

---

## 🌐 Contacto y Comunidad

🔗 **Website:** [slicesoft.dev](https://slicesoft.dev)  
🐙 **GitHub:** [github.com/slicesoft](https://github.com/slicesoft)  
✉️ **Correo:** contact@slicesoft.dev  

---

📢 **Construimos, ensamblamos, innovamos.** ¡Únete a nosotros para desarrollar el futuro del software modular! 🚀