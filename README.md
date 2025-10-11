# 🎨 Nekomponents

<div align="center">

**Una librería de componentes Vue 3 moderna y fácil de usar**

[![Vue 3](https://img.shields.io/badge/Vue-3.x-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)](https://vuejs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-7.x-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.x-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

[![npm](https://img.shields.io/badge/npm-@fer626/nekomponents-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/@fer626/nekomponents)
[![🚧 Coming Soon](https://img.shields.io/badge/🚧-Coming%20Soon-FF6B6B?style=for-the-badge)](https://github.com/fer626/nekomponents)

</div>

---

## 📖 Sobre el Proyecto / About the Project

### 🇪🇸 Español

**Nekomponents** es una librería de componentes Vue 3 desarrollada de forma pública y de código abierto, diseñada para ser simple y fácil de usar. Esta librería incluye una colección de componentes modernos construidos con las mejores tecnologías del ecosistema Vue.

#### ✨ Características Principales

- 🚀 **Vue 3** con Composition API y `<script setup>`
- 📦 **TypeScript** para tipado estático y mejor DX
- ⚡ **Vite** para desarrollo ultrarrápido
- 🎨 **Tailwind CSS 4** para estilos modernos y responsivos
- 🏗️ **Nx** para gestión de monorepo y escalabilidad
- 📋 **Husky** para hooks de Git y conventional commits
- 🔄 **GitHub Actions** para CI/CD automatizado
- 📚 **Storybook** para documentación interactiva de componentes
- 📦 **Próximamente en npm** como `@fer626/nekomponents`

#### 🛠️ Stack Tecnológico

| Tecnología | Versión | Propósito |
|------------|---------|-----------|
| Vue 3 | 3.5+ | Framework principal |
| TypeScript | 5.9+ | Tipado estático |
| Vite | 7.1+ | Build tool y dev server |
| Tailwind CSS | 4.x | Framework de CSS |
| Nx | 21.6+ | Monorepo management |
| pnpm | 10.17+ | Package manager |
| Husky | 9.1+ | Git hooks |
| Storybook | 9.1+ | Component documentation |

### 🇺🇸 English

**Nekomponents** is a Vue 3 component library developed publicly and open-source, designed to be simple and easy to use. This library includes a collection of modern components built with the best technologies from the Vue ecosystem.

#### ✨ Key Features

- 🚀 **Vue 3** with Composition API and `<script setup>`
- 📦 **TypeScript** for static typing and better DX
- ⚡ **Vite** for ultra-fast development
- 🎨 **Tailwind CSS 4** for modern and responsive styles
- 🏗️ **Nx** for monorepo management and scalability
- 📋 **Husky** for Git hooks and conventional commits
- 🔄 **GitHub Actions** for automated CI/CD
- 📚 **Storybook** for interactive component documentation
- 📦 **Coming soon to npm** as `@fer626/nekomponents`

#### 🛠️ Tech Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| Vue 3 | 3.5+ | Main framework |
| TypeScript | 5.9+ | Static typing |
| Vite | 7.1+ | Build tool and dev server |
| Tailwind CSS | 4.x | CSS framework |
| Nx | 21.6+ | Monorepo management |
| pnpm | 10.17+ | Package manager |
| Husky | 9.1+ | Git hooks |
| Storybook | 9.1+ | Component documentation |

---

## 🚀 Inicio Rápido / Quick Start

### 🇪🇸 Español

#### Prerrequisitos

- Node.js 18+ 
- pnpm 10.17+

#### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/tu-usuario/nekomponents.git
cd nekomponents

# Instalar dependencias
pnpm install

# Iniciar servidor de desarrollo
pnpm dev

# Iniciar Storybook
pnpm storybook:dev
```

#### Scripts Disponibles

```bash
# Desarrollo
pnpm dev                    # Servidor de desarrollo
pnpm build                  # Build de producción
pnpm preview                # Preview del build

# Storybook
pnpm storybook:dev          # Storybook en desarrollo
pnpm build-storybook        # Build de Storybook

# Utilidades
pnpm delete:packages        # Eliminar node_modules
pnpm reset:packages         # Reset completo de dependencias
```

### 🇺🇸 English

#### Prerequisites

- Node.js 18+
- pnpm 10.17+

#### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/nekomponents.git
cd nekomponents

# Install dependencies
pnpm install

# Start development server
pnpm dev

# Start Storybook
pnpm storybook:dev
```

#### Available Scripts

```bash
# Development
pnpm dev                    # Development server
pnpm build                   # Production build
pnpm preview                 # Preview build

# Storybook
pnpm storybook:dev           # Storybook in development
pnpm build-storybook         # Storybook build

# Utilities
pnpm delete:packages         # Remove node_modules
pnpm reset:packages          # Complete dependency reset
```

---

## 📦 Instalación / Installation

### 🇪🇸 Español

#### 🚧 Próximamente Disponible

**Nekomponents** estará disponible próximamente como paquete npm para instalación fácil:

```bash
# Instalación futura (próximamente)
npm install @fer626/nekomponents
# o
pnpm add @fer626/nekomponents
# o
yarn add @fer626/nekomponents
```

#### 📋 Uso Futuro

```javascript
// Importar componentes
import { Button, Header, Page } from '@fer626/nekomponents'

// Usar en tu aplicación Vue
export default {
  components: {
    Button,
    Header,
    Page
  }
}
```

### 🇺🇸 English

#### 🚧 Coming Soon

**Nekomponents** will be available soon as an npm package for easy installation:

```bash
# Future installation (coming soon)
npm install @fer626/nekomponents
# or
pnpm add @fer626/nekomponents
# or
yarn add @fer626/nekomponents
```

#### 📋 Future Usage

```javascript
// Import components
import { Button, Header, Page } from '@fer626/nekomponents'

// Use in your Vue application
export default {
  components: {
    Button,
    Header,
    Page
  }
}
```

---

## 📚 Documentación / Documentation

### 🇪🇸 Español

- 📖 **Storybook**: [http://localhost:6006](http://localhost:6006) - Documentación interactiva
- 🎨 **Componentes**: Explora todos los componentes disponibles
- 🧪 **Ejemplos**: Casos de uso y ejemplos prácticos
- 🔧 **API**: Documentación completa de props y eventos

### 🇺🇸 English

- 📖 **Storybook**: [http://localhost:6006](http://localhost:6006) - Interactive documentation
- 🎨 **Components**: Explore all available components
- 🧪 **Examples**: Use cases and practical examples
- 🔧 **API**: Complete props and events documentation

---

## 🤝 Contribuir / Contributing

### 🇪🇸 Español

¡Las contribuciones son bienvenidas! Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'feat(component): add AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

#### Convenciones de Commits

Este proyecto usa [Conventional Commits](https://conventionalcommits.org/):

```bash
feat(button): add new button variant
fix(header): resolve alignment issue
chore(deps): update dependencies
styles(button): improve button styling
```

### 🇺🇸 English

Contributions are welcome! Please:

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'feat(component): add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

#### Commit Conventions

This project uses [Conventional Commits](https://conventionalcommits.org/):

```bash
feat(button): add new button variant
fix(header): resolve alignment issue
chore(deps): update dependencies
styles(button): improve button styling
```

---

## 📄 Licencia / License

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Autor / Author

**Fernando A. León**

- GitHub: [@fer626](https://github.com/fer626)
- LinkedIn: [Fernando León](https://www.linkedin.com/in/ferleon92/)

---

<div align="center">

**Hecho con ❤️ usando Vue 3, TypeScript y las mejores prácticas**

**Made with ❤️ using Vue 3, TypeScript and best practices**

</div>
