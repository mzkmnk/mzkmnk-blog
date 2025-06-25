# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Next.js 15 blog application using the App Router, TypeScript, and Tailwind CSS v4. The project follows the standard Next.js project structure with all source code in the `src/` directory.

## Development Commands

- `npm run dev` - Start development server on http://localhost:3000
- `npm run build` - Build production version
- `npm run start` - Start production server
- `npm run lint` - Run ESLint with Next.js configuration

## Architecture

- **Framework**: Next.js 15 with App Router
- **Styling**: Tailwind CSS v4 with PostCSS
- **Fonts**: Geist Sans and Geist Mono from Google Fonts
- **TypeScript**: Strict mode enabled with path aliases (`@/*` maps to `./src/*`)

## Key Files

- `src/app/layout.tsx` - Root layout with font configuration and global styles
- `src/app/page.tsx` - Homepage component
- `src/app/globals.css` - Global styles and Tailwind directives
- `next.config.ts` - Next.js configuration (currently minimal)

## Code Conventions

- Uses TypeScript with strict mode
- Components use default exports
- Tailwind classes for styling with CSS custom properties for font families
- React 19 concurrent features available