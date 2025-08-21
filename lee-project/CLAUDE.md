# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a React + TypeScript + Vite application using the standard Vite React template. The project uses modern React 19 with TypeScript for type safety and Vite for fast development and building.

## Common Commands

- `npm run dev` - Start the development server with hot module replacement
- `npm run build` - Build for production (runs TypeScript compilation then Vite build)
- `npm run lint` - Run ESLint to check code quality
- `npm run preview` - Preview the production build locally

## Architecture

- **Entry Point**: `src/main.tsx` - Application entry point using React 19's `createRoot`
- **Main Component**: `src/App.tsx` - Root application component
- **Styling**: CSS modules with `src/App.css` and `src/index.css`
- **Assets**: Stored in `src/assets/` and `public/` directories
- **TypeScript Config**: Split into `tsconfig.app.json` (app code) and `tsconfig.node.json` (build tools)

## Development Setup

The project uses:
- **React 19**: Latest React version with StrictMode enabled
- **TypeScript**: Strict type checking enabled
- **Vite**: For fast development and optimized builds
- **ESLint**: Configured with React hooks and React refresh plugins
- **Module Type**: ES modules (`"type": "module"` in package.json)

## Code Style

- ESLint configuration includes React hooks rules and React refresh for HMR
- TypeScript strict mode is enabled
- Uses functional components with hooks (no class components)
- CSS is handled through separate CSS files imported into components