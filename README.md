# 🎵 Ejercicio CRUD Simplificado - Gestión de Canciones

## 📝 Descripción del Ejercicio

Este es un ejercicio **súper simplificado** de CRUD (Create, Read, Update, Delete) diseñado especialmente para estudiantes que se enfrentan **por primera vez** a estos conceptos. Los estudiantes aprenderán los fundamentos del desarrollo web Full Stack de la forma más sencilla posible.

### 🎯 ¿Qué aprenderán los estudiantes?

- **CRUD básico**: Crear, Leer, Actualizar y Eliminar datos
- **Comunicación cliente-servidor**: Cómo el navegador habla con el servidor
- **API REST simple**: Entender qué son las APIs y cómo funcionan
- **JavaScript básico**: Manipulación del DOM y fetch API
- **JSON**: Formato de intercambio de datos
- **Express.js**: Crear un servidor web simple

## 🏗️ Estructura del Proyecto (Súper Simple)

```
2910ejercicio/
├── backend/
│   ├── server.js          # 🖥️ Servidor con comentarios didácticos
│   ├── canciones.json     # 📊 Base de datos simple (solo título, artista, año)
│   └── package.json       # 📦 Dependencias
└── frontend/
    ├── index.html         # 🌐 Interfaz con comentarios explicativos
    ├── script.js          # ⚡ Lógica explicada paso a paso
    └── styles.css         # 🎨 Estilos bonitos
```

## 🚀 Instrucciones para Ejecutar (3 pasos fáciles)

### Paso 1: Instalar Node.js
1. Ir a https://nodejs.org/ y descargar Node.js
2. Instalarlo siguiendo el asistente

### Paso 2: Instalar Dependencias
```bash
# Ir a la carpeta backend
cd backend

# Instalar Express
npm install
```

### Paso 3: ¡Ejecutar!
```bash
# Iniciar servidor
npm start

# Abrir navegador en: http://localhost:3000
```

## 📊 Datos Simplificados

Cada canción tiene solo **3 campos**:
- **Título**: Nombre de la canción
- **Artista**: Quien la canta
- **Año**: Cuándo se lanzó

### Ejemplos incluidos:
- La Llorona (Manu Chao, 2001)
- Mediterráneo (Joan Manuel Serrat, 1971)
- Con Altura (Rosalía, 2019)

## 🔧 Funcionalidades (Muy Claras)

### ✅ Backend (server.js)
- **GET /api/canciones** → "Dame todas las canciones"
- **POST /api/canciones** → "Guarda esta nueva canción"
- **PUT /api/canciones/:id** → "Actualiza esta canción"
- **DELETE /api/canciones/:id** → "Borra esta canción"

### ✅ Frontend (Interfaz súper simple)
- **Ver canciones** → Lista bonita de todas las canciones
- **Agregar canción** → Formulario de 3 campos
- **Editar canción** → Llenar formulario con datos existentes
- **Eliminar canción** → Botón con confirmación

## 📚 Comentarios Didácticos Incluidos

### �️ server.js
```javascript
/* 
 * Este archivo es el SERVIDOR de nuestra aplicación web.
 * Un servidor es como un "camarero digital" que:
 * 1. Escucha cuando alguien le pide algo
 * 2. Busca lo que le piden  
 * 3. Se lo devuelve
 */
```

### ⚡ script.js
```javascript
/* 
 * JavaScript es como el "cerebro" de la aplicación web:
 * - HTML es el esqueleto (estructura)
 * - CSS es la piel (apariencia)  
 * - JavaScript es el cerebro (comportamiento)
 */
```

### 🌐 index.html
```html
<!-- 
FORMULARIO: Donde el usuario escribe los datos de las canciones
==============================================================
-->
```

## 🎯 Conceptos Clave (Explicados Simple)

1. **CRUD**: Create, Read, Update, Delete - Las 4 operaciones básicas
2. **API**: Como un "menú de restaurante" de operaciones disponibles
3. **JSON**: Formato que usan las apps para intercambiar datos
4. **Fetch**: Forma de pedir datos al servidor desde JavaScript
5. **DOM**: El "mapa" de elementos HTML que JavaScript puede manipular
6. **Event Listeners**: "Oídos" que escuchan cuando el usuario hace algo

## 🎓 Para Profesores

### ✅ Ventajas del ejercicio simplificado:
- **Solo 3 campos** por canción (fácil de entender)
- **Comentarios abundantes** en cada archivo
- **Conceptos paso a paso** explicados didácticamente
- **Código limpio** y fácil de seguir
- **Console.log educativos** para depuración
- **Errores manejados** de forma comprensible

### 📖 Archivos como manuales:
- Cada archivo tiene comentarios que explican **qué** hace cada parte
- Comentarios que explican **por qué** se hace así
- Ejemplos prácticos en los comentarios
- Flujo de la aplicación documentado

### 🔧 Extensiones sugeridas:
1. **Validación**: Agregar más validaciones al formulario
2. **Búsqueda**: Filtrar canciones por artista
3. **Favoritos**: Marcar canciones como favoritas
4. **Ordenamiento**: Ordenar por año o artista
5. **Más campos**: Agregar género, duración, etc.

## 🐛 Solución de Problemas

### "No se conecta al servidor"
- Verificar que ejecutaste `npm start` en la carpeta backend
- Verificar que el puerto 3000 esté libre

### "No aparecen las canciones"
- Abrir consola del navegador (F12) y ver los mensajes
- Verificar que el archivo canciones.json existe

### "Error al guardar"
- Revisar que todos los campos estén llenos
- Verificar que el año sea un número válido

## � Filosofía del Ejercicio

Este ejercicio está diseñado para que estudiantes **sin experiencia previa** puedan:

1. **Entender** los conceptos básicos sin abrumarse
2. **Ver** cómo funcionan las cosas paso a paso
3. **Experimentar** sin miedo a romper algo
4. **Aprender** leyendo código comentado como un libro
5. **Construir** confianza para proyectos más complejos

## 📝 Licencia

Ejercicio educativo de uso libre para instituciones y estudiantes.