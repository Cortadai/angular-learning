# 🅰️ Proyectos de Aprendizaje Angular

13 proyectos progresivos cubriendo desde básicos de Angular hasta conceptos avanzados.

## 📚 Lista de Proyectos

### Principiante

- **[angular-basics](https://github.com/Cortadai/angular-basics)**  
  Contador, Heroes, Dragon Ball - Componentes básicos y servicios

- **[angular-directivas](https://github.com/Cortadai/angular-directivas)**  
  Directivas personalizadas - Patrones error-msg y customif

### Intermedio

- **[angular-formularios](https://github.com/Cortadai/angular-formularios)**  
  Formularios Template-driven y Reactivos - Validaciones, validación entre campos
  - *Requiere: [formularios-json-db](https://github.com/Cortadai/formularios-json-db)* (Datos JSON)

- **[angular-auth](https://github.com/Cortadai/angular-auth)**  
  Autenticación JWT - Guards, renovación de tokens, rutas protegidas
  - *Backend: [node-auth-backend](https://github.com/Cortadai/node-auth-backend)* (API Node.js)

- **[angular-pipes](https://github.com/Cortadai/angular-pipes)**  
  Pipes integrados y personalizados - Filtros de transformación de datos con PrimeNG

### Avanzado

- **[angular-selectores](https://github.com/Cortadai/angular-selectores)**  
  Selectores en cascada - Dropdowns dependientes con RxJS

- **[angular-graficas](https://github.com/Cortadai/angular-graficas)**  
  Visualización de datos - Chart.js y ng2-charts

- **[angular-mapas](https://github.com/Cortadai/angular-mapas)**  
  Integración Mapbox GL - Mapas interactivos, marcadores, drag & drop

- **[angular-paises](https://github.com/Cortadai/angular-paises)**  
  Consumo de API REST - Countries API con debounce y switchMap

- **[angular-gifs](https://github.com/Cortadai/angular-gifs)**  
  Integración API Giphy - Historial de búsqueda, persistencia localStorage

- **[angular-heroes](https://github.com/Cortadai/angular-heroes)**  
  Aplicación CRUD - Material Design, autenticación, guards
  - *Requiere: [heroes-json-db](https://github.com/Cortadai/heroes-json-db)* (Datos JSON)

- **[angular-hooks](https://github.com/Cortadai/angular-hooks)**  
  Hooks de ciclo de vida - Todos los hooks con logging en consola e interacción

### Utilidades y Soporte

- **[vscode-curse](https://github.com/Cortadai/vscode-curse)**  
  Tutorial VSCode - Atajos, multi-cursor, guía de extensiones

- **[ts-intro](https://github.com/Cortadai/ts-intro)**  
  Fundamentos TypeScript - Tipos, interfaces, genéricos, decoradores

- **[node-auth-backend](https://github.com/Cortadai/node-auth-backend)**  
  Backend Node.js/Express para testing de autenticación
  - Servicio backend para proyecto `angular-auth`

### Fuentes de Datos (Proyectos de Soporte)

- **[formularios-json-db](https://github.com/Cortadai/formularios-json-db)**  
  Base de datos JSON para testing de formularios

- **[heroes-json-db](https://github.com/Cortadai/heroes-json-db)**  
  Base de datos JSON con datos de héroes DC y Marvel

---

## 🛠️ Tecnologías Utilizadas

**Frontend:**
- Angular 14/16
- TypeScript
- RxJS
- Bootstrap 5
- Angular Material
- PrimeNG

**Visualización de Datos:**
- Chart.js / ng2-charts
- Mapbox GL

**Utilidades:**
- Animate.css
- JSON Server

**Backend (Soporte):**
- Node.js / Express
- Autenticación JWT

---

## 🎯 Ruta de Aprendizaje

### Fundamentos (Empezar aquí)
1. `ts-intro` - Básicos de TypeScript
2. `angular-basics` - Fundamentos de Angular
3. `angular-directivas` - Directivas personalizadas

### Conceptos Core
4. `angular-formularios` - Maestría en formularios (con json-db)
5. `angular-pipes` - Transformación de datos
6. `angular-hooks` - Ciclo de vida de componentes

### Patrones Avanzados
7. `angular-auth` - Autenticación y seguridad (con node-auth-backend)
8. `angular-selectores` - Programación reactiva con RxJS
9. `angular-paises` - Consumo de API y optimización
10. `angular-heroes` - CRUD completo (con json-db)

### Características del Mundo Real
11. `angular-graficas` - Visualización de datos
12. `angular-mapas` - Integración de mapas
13. `angular-gifs` - Integración de API externa

### Herramientas Profesionales
14. `vscode-curse` - Productividad del desarrollador

---

## 📦 Dependencias y Configuración

### Proyectos que requieren bases de datos JSON:
- `angular-formularios` → Usar [formularios-json-db](https://github.com/Cortadai/formularios-json-db)
- `angular-heroes` → Usar [heroes-json-db](https://github.com/Cortadai/heroes-json-db)

**Configurar JSON Server:**
```bash
npm install -g json-server
json-server --watch db.json --port 3000
```

### Proyectos que requieren API backend:
- `angular-auth` → Usar [node-auth-backend](https://github.com/Cortadai/node-auth-backend)

**Configurar backend Node:**
```bash
cd node-auth-backend
npm install
npm start  # Se ejecuta en puerto 3000 (o puerto configurado)
```

### APIs Externas:
- `angular-paises` - Usa [REST Countries API](https://restcountries.com/v2/)
- `angular-gifs` - Usa [Giphy API](https://giphy.com/) (requiere API key)

---

## 🚀 Inicio Rápido

### Clonar y explorar cualquier proyecto:
```bash
git clone https://github.com/Cortadai/angular-basics.git
cd angular-basics
npm install
ng serve  # o npm start
```

### Orden recomendado:
1. Empezar con `ts-intro` para revisar TypeScript
2. Seguir la sección Ruta de Aprendizaje arriba
3. Probar primero proyectos intermedios
4. Avanzar a patrones complejos

---

## 📊 Estadísticas del Proyecto

| Categoría | Cantidad | Topics |
|-----------|----------|--------|
| **Angular Core** | 13 | #angular #aprendizaje #educacion #tutorial |
| **Soporte** | 2 | #nodejs #aprendizaje #educacion |
| **Utilidades** | 2 | #typescript #vscode #aprendizaje |
| **Fuentes de Datos** | 2 | #json-db #aprendizaje |
| **TOTAL** | 19 | - |

---

## 🔗 Colecciones Relacionadas

Explora otras colecciones de aprendizaje:
- [Proyectos de Aprendizaje Spring Boot](https://github.com/Cortadai/spring-boot-basics)
- [Web Services & SOAP]([https://github.com/Cortadai](https://github.com/Cortadai/web-services-soap))
- [Arquitectura de Microservicios](https://github.com/Cortadai/microservices-architecture)

---

## 💡 Conceptos Clave por Proyecto

| Concepto | Proyecto |
|----------|----------|
| Componentes | angular-basics |
| Directivas | angular-directivas |
| Inyección de Dependencias | Todos los proyectos |
| Formularios (Template) | angular-formularios |
| Formularios (Reactivos) | angular-formularios |
| Validación | angular-formularios |
| Pipes | angular-pipes |
| Servicios | Todos los proyectos |
| HTTP Client | angular-paises, angular-gifs, angular-heroes |
| RxJS | angular-selectores, angular-paises |
| Routing y Guards | angular-auth, angular-heroes |
| Material Design | angular-heroes, angular-graficas |
| Autenticación | angular-auth |
| localStorage | angular-gifs, angular-mapas |
| APIs de Terceros | angular-paises, angular-gifs |
| Integración de Mapas | angular-mapas |
| Charts y Visualización | angular-graficas |
| Hooks de Ciclo de Vida | angular-hooks |

---

## 🎓 Resultados de Aprendizaje

Después de completar esta colección, dominarás:
- ✅ Fundamentos de Angular y patrones avanzados
- ✅ TypeScript para desarrollo web
- ✅ Programación reactiva con RxJS
- ✅ Manejo de formularios (template-driven y reactivos)
- ✅ Comunicación HTTP con APIs REST
- ✅ Autenticación y seguridad
- ✅ Gestión del ciclo de vida de componentes
- ✅ Directivas y pipes personalizados
- ✅ Visualización de datos
- ✅ Integración de mapas
- ✅ Consumo de APIs de terceros
- ✅ Almacenamiento y persistencia
- ✅ Implementación de Material Design

---

## 📝 Topics Aplicados

Cada proyecto está etiquetado con:
- `#angular` - Framework Angular
- `#aprendizaje` - Proyecto de aprendizaje
- `#educacion` - Contenido educativo
- `#tutorial` - Estilo tutorial

Proyectos de soporte etiquetados con:
- `#nodejs` - Runtime Node.js
- `#typescript` - Lenguaje TypeScript
- `#json-db` - Base de datos JSON
- `#vscode` - Editor VS Code

---

## 📬 ¿Preguntas o Mejoras?

Estos proyectos fueron creados como parte de un viaje continuo de aprendizaje en desarrollo Angular.

*Última actualización: Noviembre 2025*
