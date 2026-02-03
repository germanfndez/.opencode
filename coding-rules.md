# Reglas de Codificación Globales

## Estilo de Código
- Usar 2 espacios para indentación
- Preferir comillas simples sobre dobles
- Lineas máximas de 80 caracteres cuando sea posible
- Usar camelCase para variables y funciones
- Usar PascalCase para clases y componentes

## Buenas Prácticas
- Siempre tipar variables en TypeScript
- Evitar variables globales
- Usar funciones puras cuando sea posible
- Manejar errores apropiadamente con try/catch
- Documentar funciones complejas con comentarios

## Estructura de Archivos
- Un export default por archivo
- Exportar tipos e interfaces al principio del archivo
- Colocar imports al inicio, agrupados por tipo
- Orden: librerías externas → módulos internos → relativos

## Convenciones de Nomenclatura
- Constantes en UPPER_SNAKE_CASE
- Prefijar variables booleanas con is/has/can
- Nombres descriptivos pero concisos
- Evitar abreviaciones no estándar

## Código Limpio
- Remover código comentado
- Evitar console.log en producción
- Usar nombres significativos para variables
- Una responsabilidad por función