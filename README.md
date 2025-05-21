# NestJS DDD Scaffolding CLI

Generador de módulos NestJS con estructura basada en Domain-Driven Design (DDD). Este proyecto tiene como objetivo agilizar la creación de nuevos módulos mediante comandos CLI personalizados.

> 🚧 Proyecto en fase inicial de construcción

---

## ✨ Características esperadas

- Generación automática de:
  - Carpetas de dominio, aplicación, infraestructura y presentación
  - Entidades, agregados, repositorios y casos de uso base
  - Archivos `module.ts`, `controller.ts`, `service.ts` y pruebas básicas
- Soporte para nombres personalizados de módulo
- Estructura limpia basada en DDD
- Comandos intuitivos estilo CLI

---

## 📦 Instalación (futura)

```bash
npm install -g @tu-org/ddd-scaffold
```

---

## 🚀 Comandos esperados

```bash
# Genera un módulo DDD llamado "usuario"
ddd-cli generate usuario

# Opcionalmente con prefijo de contexto
ddd-cli generate usuario --context=auth
```

Esto creará una estructura como:

```
src/
└── usuario/
    ├── domain/
    │   ├── entities/
    │   └── repositories/
    ├── application/
    │   └── use-cases/
    ├── infrastructure/
    │   └── persistence/
    └── presentation/
        └── controllers/
```

---

## 🔧 Tecnologías

- [NestJS](https://nestjs.com/)
- [Commander.js](https://github.com/tj/commander.js) (CLI)
- [Plop.js](https://plopjs.com/) o código personalizado para scaffolding
- Node.js

---

## 📍 Estado actual

- [x] Definición de estructura base
- [ ] Implementación del primer comando CLI
- [ ] Configuración de plantillas de generación
- [ ] Publicación como paquete npm

---

## 🤝 Contribuciones

¿Ideas o sugerencias? ¡Bienvenido! Puedes abrir un issue o hacer un PR.

---

## 📄 Licencia

MIT
