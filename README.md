# Prueba-pr# Proyecto Playwright

Este proyecto utiliza **Playwright** para la automatización de pruebas en navegadores. A continuación se detallan los comandos principales, configuraciones y ejemplos utilizados en el proyecto.

## Requisitos

- Node.js (se recomienda la versión 16 o superior)
- npm (gestor de paquetes de Node.js)
- Playwright (se instala mediante npm)

## Instalación

### 1. Clonar el repositorio

Clona el repositorio en tu máquina local:

```bash
git clone https://github.com/usuario/nombre-del-repo.git
cd nombre-del-repo

#### 2. Instalar las dependencias
npm install playwright

### 3. Ejecutar pruebas
npx playwright test

### 4. Ejecutar pruebas en un navegador específico
npx playwright test --project=firefox

### 5. Ejecutar pruebas en modo headed (con interfaz gráfica)
npx playwright test --headed

### 6. Ejecutar pruebas con un archivo de configuración
npx playwright test --config=playwright.config.js

### 7. Permite grabar las interacciones con el navegador y generar código Playwright a partir de esas acciones.
npx playwright codegen

