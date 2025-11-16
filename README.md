# 🅰️ Angular Learning Projects

13 progressive projects covering Angular basics to advanced concepts.

## 📚 Projects List

### Beginner
- **[angular-basics](https://github.com/Cortadai/angular-basics)**
  Counter, Heroes, Dragon Ball - Basic components and services

- **[angular-directivas](https://github.com/Cortadai/angular-directivas)**
  Custom directives - error-msg and customif patterns

### Intermediate  
- **[angular-formularios](https://github.com/Cortadai/angular-formularios)**
  Template-driven and Reactive Forms - Validations, cross-field validation
  - *Requires: [formularios-json-db](https://github.com/Cortadai/formularios-json-db)* (JSON data)

- **[angular-auth](https://github.com/Cortadai/angular-auth)**
  JWT authentication - Guards, token renewal, protected routes
  - *Backend: [node-auth-backend](https://github.com/Cortadai/node-auth-backend)* (Node.js API)

- **[angular-pipes](https://github.com/Cortadai/angular-pipes)**
  Built-in and custom pipes - Data transformation filters with PrimeNG

### Advanced
- **[angular-selectores](https://github.com/Cortadai/angular-selectores)**
  Cascading selectors - Dependent dropdowns with RxJS

- **[angular-graficas](https://github.com/Cortadai/angular-graficas)**
  Data visualization - Chart.js and ng2-charts

- **[angular-mapas](https://github.com/Cortadai/angular-mapas)**
  Mapbox GL integration - Interactive maps, markers, drag & drop

- **[angular-paises](https://github.com/Cortadai/angular-paises)**
  REST API consumption - Countries API with debounce and switchMap

- **[angular-gifs](https://github.com/Cortadai/angular-gifs)**
  Giphy API integration - Search history, localStorage persistence

- **[angular-heroes](https://github.com/Cortadai/angular-heroes)**
  CRUD application - Material Design, authentication, guards
  - *Requires: [heroes-json-db](https://github.com/Cortadai/heroes-json-db)* (JSON data)

- **[angular-hooks](https://github.com/Cortadai/angular-hooks)**
  Lifecycle hooks - All hooks with console logging and interaction

### Utilities & Support
- **[vscode-curse](https://github.com/Cortadai/vscode-curse)**
  VSCode tutorial - Shortcuts, multi-cursor, extensions guide

- **[ts-intro](https://github.com/Cortadai/ts-intro)**
  TypeScript fundamentals - Types, interfaces, generics, decorators

- **[node-auth-backend](https://github.com/Cortadai/node-auth-backend)**
  Node.js/Express backend for authentication testing
  - Backend service for `angular-auth` project

### Data Sources (Supporting Projects)
- **[formularios-json-db](https://github.com/Cortadai/formularios-json-db)**
  JSON database for form testing

- **[heroes-json-db](https://github.com/Cortadai/heroes-json-db)**
  JSON database with DC & Marvel heroes data

---

## 🛠️ Technologies Used

**Frontend:**
- Angular 14/16
- TypeScript
- RxJS
- Bootstrap 5
- Angular Material
- PrimeNG

**Data Visualization:**
- Chart.js / ng2-charts
- Mapbox GL

**Utilities:**
- Animate.css
- JSON Server

**Backend (Supporting):**
- Node.js / Express
- JWT Authentication

---

## 🎯 Learning Path

### Foundation (Start here)
1. `ts-intro` - TypeScript basics
2. `angular-basics` - Angular fundamentals
3. `angular-directivas` - Custom directives

### Core Concepts
4. `angular-formularios` - Forms mastery (with json-db)
5. `angular-pipes` - Data transformation
6. `angular-hooks` - Component lifecycle

### Advanced Patterns
7. `angular-auth` - Authentication & security (with node-auth-backend)
8. `angular-selectores` - Reactive programming with RxJS
9. `angular-paises` - API consumption & optimization
10. `angular-heroes` - Complete CRUD (with json-db)

### Real-World Features
11. `angular-graficas` - Data visualization
12. `angular-mapas` - Map integration
13. `angular-gifs` - External API integration

### Professional Tools
14. `vscode-curse` - Developer productivity

---

## 📦 Dependencies & Setup

### Projects requiring JSON databases:
- `angular-formularios` → Use [formularios-json-db](https://github.com/Cortadai/formularios-json-db)
- `angular-heroes` → Use [heroes-json-db](https://github.com/Cortadai/heroes-json-db)

**Setup JSON Server:**
```bash
npm install -g json-server
json-server --watch db.json --port 3000
```

### Projects requiring backend API:
- `angular-auth` → Use [node-auth-backend](https://github.com/Cortadai/node-auth-backend)

**Setup Node backend:**
```bash
cd node-auth-backend
npm install
npm start  # Runs on port 3000 (or configured port)
```

### External APIs:
- `angular-paises` - Uses [REST Countries API](https://restcountries.com/v2/)
- `angular-gifs` - Uses [Giphy API](https://giphy.com/) (requires API key)

---

## 🚀 Quick Start

### Clone and explore any project:
```bash
git clone https://github.com/Cortadai/angular-basics.git
cd angular-basics
npm install
ng serve  # or npm start
```

### Recommended order:
1. Start with `ts-intro` for TypeScript review
2. Follow the Learning Path section above
3. Try intermediate projects first
4. Advance to complex patterns

---

## 📊 Project Stats

| Category | Count | Topics |
|----------|-------|--------|
| **Angular Core** | 13 | #angular #learning #education #tutorial |
| **Supporting** | 2 | #nodejs #learning #education |
| **Utilities** | 2 | #typescript #vscode #learning |
| **Data Sources** | 2 | #json-db #learning |
| **TOTAL** | 19 | - |

---

## 🔗 Related Collections

Explore other learning collections:
- [Spring Boot Learning Projects](https://github.com/Cortadai)
- [Web Services & SOAP](https://github.com/Cortadai)
- [Microservices Architecture](https://github.com/Cortadai)

---

## 💡 Key Concepts by Project

| Concept | Project |
|---------|---------|
| Components | angular-basics |
| Directives | angular-directivas |
| Dependency Injection | All projects |
| Forms (Template) | angular-formularios |
| Forms (Reactive) | angular-formularios |
| Validation | angular-formularios |
| Pipes | angular-pipes |
| Services | All projects |
| HTTP Client | angular-paises, angular-gifs, angular-heroes |
| RxJS | angular-selectores, angular-paises |
| Routing & Guards | angular-auth, angular-heroes |
| Material Design | angular-heroes, angular-graficas |
| Authentication | angular-auth |
| localStorage | angular-gifs, angular-mapas |
| Third-party APIs | angular-paises, angular-gifs |
| Maps Integration | angular-mapas |
| Charts & Visualization | angular-graficas |
| Lifecycle Hooks | angular-hooks |

---

## 🎓 Learning Outcomes

After completing this collection, you'll master:
- ✅ Angular fundamentals and advanced patterns
- ✅ TypeScript for web development
- ✅ Reactive programming with RxJS
- ✅ Form handling (template-driven & reactive)
- ✅ HTTP communication with REST APIs
- ✅ Authentication and security
- ✅ Component lifecycle management
- ✅ Custom directives and pipes
- ✅ Data visualization
- ✅ Map integration
- ✅ Third-party API consumption
- ✅ Storage and persistence
- ✅ Material Design implementation

---

## 📝 Topics Applied

Each project is tagged with:
- `#angular` - Angular framework
- `#learning` - Learning project
- `#education` - Educational content
- `#tutorial` - Tutorial style

Supporting projects tagged with:
- `#nodejs` - Node.js runtime
- `#typescript` - TypeScript language
- `#json-db` - JSON database
- `#vscode` - VS Code editor

---

## 📬 Questions or Improvements?

These projects were created as part of a continuous learning journey in Angular development.

*Last updated: November 2025*
