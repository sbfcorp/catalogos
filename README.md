# Catálogos Estándar

Este repositorio contiene un conjunto de catálogos estandarizados en formato JSON, organizados por tipo y país. Su propósito es centralizar los catálogos utilizados a lo largo de diferentes proyectos, asegurando consistencia y facilitando su acceso.

## Estructura del Repositorio

Cada subcarpeta dentro del repositorio contiene archivos JSON relacionados con un tipo específico de catálogo, como países, departamentos, etc.

### Ejemplos de archivos:
- **departamentos/costa_rica.json**: Contiene información sobre los departamentos de Costa Rica.
- **departamentos/guatemala.json**: Contiene información sobre los departamentos de Guatemala.
- **paises/paises.json**: Contiene información sobre los países.

Este repositorio está diseñado para facilitar la gestión y estandarización de catálogos a través de distintos proyectos, garantizando que todos usen la misma estructura y formato de datos.

## Formateo Automático con Prettier

Este repositorio incluye una acción de GitHub para formatear automáticamente los archivos con Prettier cada vez que se haga un "push". Esto garantiza que todos los archivos JSON sigan un formato consistente.

### Configuración Local de Prettier

Si deseas configurar Prettier en tu máquina local para formatear los archivos JSON antes de hacer un commit, sigue estos pasos:

- 1. Clona este repositorio en tu máquina:
   ```bash
   git clone https://github.com/sbfcorp/catalogos.git
   cd catalogos
   ```
- 2. Instala las dependencias de Prettier:

`npm install --legacy-peer-deps`

- 3. Formatea los archivos utilizando Prettier:

`npx prettier --write .`