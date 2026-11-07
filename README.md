# Webpack Starter Template

A reusable Webpack development environment for vanilla JavaScript projects.

## Features

- Webpack 5
- Webpack Dev Server
- HTML generation using HtmlWebpackPlugin
- CSS and asset handling
- Development and production configurations

## Getting Started

### 1. Clone the repository

### 2. Install dependencies

npm install

### 3. Start development server

npm run dev

### 4. Build for production

npm run build

## Project Structure

src/
├── assets/
├── scripts/
├── styles/
└── template.html

dist/

webpack.common.js
webpack.dev.js
webpack.prod.js
package.json

## Available Scripts

| Command | Description |
|---|---|
| npm run dev | Start development server |
| npm run build | Build for production |

## Notes

- Do not commit node_modules or dist.
- Update package.json with your project name.
- Initialize a new Git repository for each project.