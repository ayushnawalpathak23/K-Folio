# K-Folio Frontend

Modern portfolio website frontend built with React, TypeScript, and Tailwind CSS.

## Tech Stack

- **React** - UI library
- **TypeScript** - Type-safe JavaScript
- **Vite** - Next-generation frontend build tool
- **Tailwind CSS** - Utility-first CSS framework

## Prerequisites

- Node.js (v18 or higher)
- pnpm package manager (recommended) or npm

## Getting Started

### Installation

Install dependencies:
```bash
pnpm install
# or
npm install
```

### Development

Start the development server:
```bash
pnpm dev
# or
npm run dev
```

The application will be available at [http://localhost:5173](http://localhost:5173)

### Build

Create a production build:
```bash
pnpm build
# or
npm run build
```


## Project Structure

```
frontend/
├── public/          # Static assets
├── src/
│   ├── assets/      # Images, fonts, etc.
│   ├── App.tsx      # Main application component
│   ├── main.tsx     # Application entry point
│   └── index.css    # Global styles
├── index.html       # HTML entry point
├── vite.config.ts   # Vite configuration
└── tailwind.config.js # Tailwind CSS configuration
```

## Available Scripts

| Command | Description |
|---------|-------------|
| `pnpm dev` | Start development server with hot reload |
| `pnpm build` | Build for production |
| `pnpm preview` | Preview production build locally |
| `pnpm lint` | Run ESLint for code quality checks |

## Learn More

- [React Documentation](https://react.dev/)
- [Vite Documentation](https://vitejs.dev/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)