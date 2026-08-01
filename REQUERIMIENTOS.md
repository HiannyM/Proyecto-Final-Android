# Proyecto-Final-Android
Proyecto final del curso de Android Studio 2026 con Kotlin basada en una app de recetas de cocina.

# Cocina Fácil -- App de recetas de cocina

## 1. Descripción
Cocina Fácil es una aplicación móvil desarrollada en Android con Jetpack Compose que permite a los usuarios explorar distintas recetas de cocina, 
marcar los ingredientes y pasos realizados mediante una checklist interactiva, y agregar sus propias recetas personalizadas.

## 2. Problema que resuelve
Cocinar una receta requiere seguir pasos ordenados y controlar los ingredientes disponibles. Esta app elimina la confusión al cocinar permitiendo tachar en tiempo 
real los ingredientes ya utilizados y los pasos completados, además de servir como un recetario personal organizado.

## 3. Pantallas
| # | Nombre de pantalla | Descripción breve              | 
|---|-------------------|-------------------------------| 
| 1 | PantallaInicio    | Pantalla de bienvenida y menú | 
| 2 | PantallaLista     | Lista scrollable de items     | 
| 3 | PantallaDetalle   | Detalle de un item específico | 

## 4. Tecnologías usadas 
- Kotlin 2.x
- Jetpack Compose + Material 3
- Navigation Compose
- Estado con `remember` / `rememberSaveable` / State Hoisting
- Listas optimizadas con `LazyColumn` y `LazyRow`

## 5. Diagrama de navegación
- **InicioScreen** ──► [Click en una Receta] ──────────────► **DetalleScreen** (`detalle/{recetaId}`)
- **InicioScreen** ──► [Botón Flotante '+'] ──────────────► **CrearRecetaScreen**
- **DetalleScreen** ──► [Botón 'Regresar'] ────────────────► **InicioScreen**
- **CrearRecetaScreen** ──► [Guardar / Cancelar] ──────────► **InicioScreen**

## 6. Capturas de pantalla
[Se agregarán al finalizar el desarrollo] 
