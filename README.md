
# 📚 Requisitos Previos
Antes de comenzar, asegúrate de tener instalados los siguientes requisitos:

- [Node.js](https://nodejs.org/) (versión recomendada: LTS)
- [Git](https://git-scm.com/)
- [Shopify CLI](https://shopify.dev/docs/themes/tools/cli/installation)

---

## ⚙️ Instalación

### Clonar el repositorio
Debes abrir una terminal en tu local y clonar el repositorio donde prefieras:
```bash
git clone https://github.com/asuajeivan/unow.git
cd unow
```

---

## 🔐 Login
Cuando estén dentro del proyecto deben autenticarse, esto se hace mediante el comando:
```bash
shopify theme dev --store wpjcqw-kp
```
> **Nota:** Debes tener acceso a la tienda y el nombre de la tienda (`wpjcqw-kp`) puede cambiar.

---

## 📝 Estructura del Proyecto
\`\`\`bash
.
├── assets/              # Archivos CSS, JS, imágenes
├── config/              # Configuración del tema
├── layout/              # Plantillas de disposición principal
├── locales/             # Archivos de traducción
├── sections/            # Componentes reutilizables del tema
├── snippets/            # Pequeñas partes de código Liquid
├── templates/           # Plantillas para diferentes páginas
└── README.md            # Guía de despliegue y desarrollo
\`\`\`

---

## 🎯 Buenas Prácticas
✅ Usa **Liquid** siguiendo [la documentación oficial de Shopify](https://shopify.dev/docs/api)✅ Implementa **CSS siguiendo BEM** para mantener el código modular y fácil de mantener.✅ Para funcionalidades avanzadas usa **JavaScript como Web Components** para encapsular y reutilizar componentes.✅ Verifica siempre con **Theme Check** para evitar errores de sintaxis y seguir estándares.

---

## 🛠️ Comandos Útiles

| Comando                | Descripción                          |
|------------------------|--------------------------------------|
| \`shopify login\`         | Autentica y conecta tu cuenta       |
| \`shopify store login\`   | Conecta tu tienda Shopify           |
| \`shopify theme dev\`     | Inicia el modo desarrollo           |
| \`shopify theme push\`    | Sube el tema a Shopify              |
| \`shopify theme publish\` | Publica el tema como activo         |
| \`theme-check\`           | Valida el tema para mejores prácticas |
