# Proyecto React con TypeScript

Este proyecto es un ejemplo de una aplicación sencilla para la gestión de productos, que incluye funcionalidades para agregar productos y visualizarlos en un listado.

## Propietario
- Alumno: Juan Cruz Yanardi Ferrer
- Legajo: 50206
- Materia: Desarrollo de Software
- Curso: 3K09

## Tecnologías Utilizadas
- React
- TypeScript

## Estructura del Proyecto

La estructura principal del proyecto se organiza de la siguiente manera:

### Archivos Principales
- index.html: Archivo principal que contiene la estructura HTML de la aplicación.
- src/: Carpeta principal que almacena los archivos de código fuente.

### Subcarpetas y Componentes
- src/
  - main.tsx: Punto de entrada de la aplicación. Inicializa y renderiza el componente raíz.
  - App.tsx: Componente principal encargado de renderizar la aplicación.

- src/components/
  - AppProduct/: Carpeta principal de componentes relacionados con la funcionalidad de productos.
    - AppProduct.tsx: Componente que gestiona el estado de los productos y organiza el formulario y el listado.
    - FormProduct.tsx: Componente para el formulario de agregar productos.
    - Header.tsx: Componente del encabezado de la aplicación.
    - ListProduct.tsx: Componente para renderizar la lista de productos.
- src/hooks/
  - useForm.ts: Hook personalizado que facilita la gestión del estado y las validaciones del formulario.
