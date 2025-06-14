# Vite-Nitro-React

A modern full-stack TypeScript monorepo project featuring:
- React 19 frontend with Vite
- Nitro backend server
- Bun as the package manager and runtime

## Project Structure

```
vite-nitro-react/
├── app/               # React frontend using Vite
├── server/            # Nitro API server
├── index.ts           # Main entry point
└── package.json       # Workspace configuration
```

## Prerequisites

- [Bun](https://bun.sh) v1.2.16 or higher

## Getting Started

### Installation

Install all dependencies for both frontend and backend:

```bash
bun install
```

### Development

Start both the frontend and backend in development mode:

```bash
bun dev
```

This runs:
- Vite dev server for the React app
- Nitro dev server for the backend API

### Building for Production

Build both packages for production:

```bash
bun build
```

### Preview Production Build

Preview the production build locally:

```bash
bun preview
```

## Technologies

- **Frontend**: React 19, Vite 6, TypeScript
- **Backend**: Nitropack, TypeScript
- **Package Manager**: Bun

## License

[MIT](LICENSE)
