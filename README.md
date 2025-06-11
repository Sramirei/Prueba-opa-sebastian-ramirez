# Optimizador de Equipo para Escalada

Aplicación web para determinar la combinación óptima de elementos para escalar un risco basado en propiedades calóricas y peso.

## Características Principales

- Calcula la combinación óptima de elementos que cumple con:
  - Mínimo de calorías requeridas
  - Peso máximo permitido
- Gestión completa de elementos:
  - Agregar nuevos elementos con ID automático
  - Editar elementos existentes
  - Eliminar elementos
- Persistencia de datos:
  - localStorage para la lista de elementos
  - sessionStorage para datos de sesión
  - Cookies para preferencias de búsqueda
- Interfaz responsive compatible con móviles y desktop
- Diseño moderno con Bootstrap 5

## Tecnologías Utilizadas

- HTML5, CSS3, JavaScript ES6
- Bootstrap 5 para la interfaz de usuario
- Almacenamiento web (localStorage, sessionStorage, cookies)

## Instalación y Uso

1. Clonar el repositorio o descargar los archivos
2. Abrir `index.html` en cualquier navegador moderno
3. No se requieren dependencias adicionales

## Funcionalidades Futuras (Escalabilidad)

1. **Backend y Base de Datos**:
   - Implementar API REST para los cálculos
   - Conexión a base de datos para persistencia avanzada
   - Autenticación de usuarios

2. **Mejoras de Algoritmos**:
   - Implementar el problema de la mochila con programación dinámica
   - Paralelizar cálculos con Web Workers

3. **Funcionalidades Adicionales**:
   - Categorías de elementos
   - Restricciones adicionales (volumen, fragilidad)
   - Sistema de recomendaciones
   - Compartir combinaciones

4. **Interoperabilidad**:
   - Versión como PWA (Progressive Web App)
   - Aplicación móvil con Capacitor/React Native
   - Exportar/importar datos en JSON/CSV

5. **Internacionalización**:
   - Soporte para múltiples idiomas
   - Conversión automática de unidades

## Estructura del Código

- `StorageManager`: Maneja la persistencia de datos
- `CombinationFinder`: Implementa el algoritmo de optimización
- `ClimbingOptimizerApp`: Clase principal que coordina la aplicación

## Ejecución de Pruebas

La aplicación incluye pruebas manuales de:
1. Agregar/editar/eliminar elementos
2. Calcular combinaciones con diferentes parámetros
3. Persistencia de datos entre sesiones
