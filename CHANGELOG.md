# 📜 Changelog — Gestor de Payloads

## [v1.0.0] - 2025-10-03
### 🎉 Lanzamiento inicial
- Primera versión estable del **Repositorio de Payloads**.
- Tool **100% offline** en el navegador (HTML/JS, persistencia en localStorage).
- Interfaz visual oscura con estilo glassmorphism.

### 🚀 Funcionalidades principales
- **Categorías dinámicas**
  - Crear, renombrar y eliminar categorías personalizadas (XSS, IDOR, RCE, …).
  - Contador de payloads en cada categoría.
  - Filtros propios: todos, sin etiqueta, muy bueno, bueno, medio, débil.

- **Gestión de payloads (renglones)**
  - Agregar, editar y borrar renglones.
  - Título editable ("Nuevo payload" por defecto).
  - Campo de texto para payload + botón copiar.
  - Píldora de estado configurable.
  - Notas con tooltip (última edición + preview + indicador rojo si existe).

- **Funciones por categoría**
  - Agregar renglón rápido.
  - Copiar TODOS los payloads (respeta filtros).
  - Eliminar categoría completa.

- **Buscador global**
  - Lateral derecho fijo.
  - Búsqueda en payloads, títulos, notas y categorías.
  - Scroll suave hasta el resultado + resaltado.

- **Botonera de control (fija en pantalla)**
  - + Agregar categoría.
  - Exportar JSON (clipboard).
  - Importar JSON (desde clipboard).
  - Borrar todo (reset total).

### 💾 Persistencia
- Todo guardado en **localStorage** automáticamente.
- Exportar/Importar JSON para respaldo.

---
