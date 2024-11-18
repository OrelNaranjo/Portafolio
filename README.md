# 👨‍💻 Portafolio de Orel Rolando Naranjo Domínguez

¡Bienvenido a mi portafolio! Soy un **Desarrollador FullStack** con una sólida experiencia en la creación de interfaces interactivas de alto rendimiento. Especializado en **Angular**, **TypeScript**, **NestJS**, **Postgres**. Me apasiona mejorar la interacción de los usuarios con las aplicaciones y siempre busco proyectos desafiantes para seguir perfeccionando mis habilidades.

---

## 🛠️ Habilidades Técnicas

- **Frontend**: JavaScript, TypeScript, Angular, Ngxs Store, Bootstrap, HTML, CSS
- **Backend**: NestJS, Express, SQL, REST APIs
- **Bases de Datos**: Sql, PostgreSQL, Mysql, Mongo
- **Otros**: Desarrollo Fullstack, Control de Versiones (Git), Desarrollo Ágil (Kanban), Optimización de rendimiento, Diseño de interfaces, Desarrollo de componentes, Integración de API, Pruebas unitarias.
  
---

## 📈 Experiencia Profesional

### **Desarrollador Fullstack Jr. | RampHR**  
_2024 - Actualmente_

- Optimización de componentes Angular para mejorar la experiencia de usuario, logrando una reducción del tiempo de carga en un 25%.
- Mantenimiento y mejora de APIs en NestJS, garantizando un rendimiento en tiempo real.
- Desarrollo e integración de páginas utilizando **Signals** y **Ngx Store** como gestor de estado, mejorando la capacidad de respuesta de la interfaz.
- Implementación de pruebas unitarias con **Jest** para asegurar la calidad del código y evitar regresiones.

### **Fundador y Desarrollador | Akira Software**  
_2022 - Actualmente_

- Fundé y gestiono una empresa de desarrollo de software dedicada a mejorar la eficiencia operativa de las empresas mediante soluciones personalizadas.
- Desarrollo de aplicaciones web completas utilizando **Angular**, **NestJS** y **PostgreSQL**.
- Implementación de soluciones automatizadas que mejoran la gestión empresarial, aumentando la productividad de los clientes.

### **Desarrollador | Bondu SpA**  
_2018 - Actualmente_

- Desarrollo de soluciones personalizadas para integrar sistemas ERP con plataformas de E-Commerce utilizando **NestJS** y **Angular**.
- Optimización de interfaces para mejorar la interacción en sistemas de compras online, logrando un incremento del 15% en la tasa de conversión.
- Mantenimiento y optimización de bases de datos **PostgreSQL** para mejorar el rendimiento.

---

## 🎓 Cursos y Certificaciones

- **Typescript** - Nicolas Schurmann (Udemy)
- **Mastering Angular 18** - Nirmal Joshi (Udemy)
- **Programación Web con Django** - Udemy
- **Python Essentials 1** - Cisco
- **Certificación Azure Fundamentals AZ-900** - Microsoft
- **Database Design Learner** - Oracle
- **Scratch** - Biblioredes
- **Introducción a Java** - Universidad Autónoma de México

---

## 🌍 Idiomas

- **Español**: Nativo
- **Inglés**: Básico, con experiencia trabajando en documentación técnica en inglés.

---

## 🔗 Enlaces de Interés

- 📧 **Correo electrónico**: [orelnaranjo@gmail.com](mailto:orelnaranjo@gmail.com)
- 🌐 **LinkedIn**: [linkedin.com/in/orelnaranjo](https://linkedin.com/in/orelnaranjo)
- 🐙 **GitHub**: [github.com/OrelNaranjo](https://github.com/OrelNaranjo)
- 📱 **Teléfono**: +569 9289 1711
- 📍 **Localidad**: Santiago, Chile
---

## 🚀 Proyectos Destacados

# 🚀 Control de Inventario Avanzado

Un sistema de **control de inventario avanzado** que permite gestionar productos, cantidades, ubicaciones y movimientos dentro de una tienda o empresa. Este proyecto está estructurado dentro de un **monorepo gestionado con Nx**, lo que permite gestionar de manera eficiente tanto el **frontend en Angular** como el **backend en NestJS**, compartiendo código y optimizando el flujo de trabajo.

## 🌍 Estructura del Proyecto

Este proyecto está dividido en tres aplicaciones principales:
- **Frontend**: Una aplicación en **Angular** que gestiona la interfaz de usuario.
- **Backend**: Una API REST en **NestJS** que maneja la lógica de negocio y la base de datos.
- **Shared**: Una librería común de TypeScript que contiene interfaces, utilidades y funciones compartidas entre el frontend y el backend.

---

## 💻 **Frontend (Angular)**

- **Tecnologías**: Angular, TypeScript, Bootstrap
- **Descripción**: La interfaz de usuario permite a los administradores ver y gestionar inventarios, realizar búsquedas avanzadas y realizar movimientos de productos entre diferentes ubicaciones.
- **Características**:
  - Gestión visual del inventario.
  - Interfaz dinámica para la actualización en tiempo real de productos y cantidades.
  - Implementación de filtros y búsquedas avanzadas para facilitar la administración.
  - Seguridad en el acceso y en la gestión de productos mediante autenticación de usuarios.

---

## 🖥️ **Backend (NestJS)**

- **Tecnologías**: NestJS, PostgreSQL, REST API
- **Descripción**: El backend gestiona la base de datos del inventario, procesa las solicitudes del frontend y realiza las operaciones de gestión de productos y movimientos.
- **Características**:
  - API REST para la comunicación entre el frontend y el backend.
  - Integración con **PostgreSQL** para el almacenamiento de productos, movimientos y transacciones.
  - Control de acceso y roles de usuario (administrador, operador) para gestionar permisos.
  - Lógica de negocio para la actualización automática de inventarios y alertas en caso de escasez de productos.

---

## 🛠️ **Tecnologías y Herramientas Utilizadas**

- **Nx**: Gestión del monorepo que contiene tanto el frontend como el backend, y facilita la reutilización de código compartido entre ambos.
- **Angular**: Framework para construir el frontend.
- **NestJS**: Framework para construir el backend y la API REST.
- **PostgreSQL**: Base de datos para almacenar el inventario y las transacciones.
- **Bootstrap**: Framework CSS para la creación de una interfaz de usuario responsiva.
- **TypeScript**: Lenguaje utilizado para el desarrollo tanto del frontend como del backend.

---

## 🚀 **Logros**

- **Optimización del rendimiento**: Implementación de caché en el backend para acelerar las consultas de inventario.
- **Escalabilidad**: Diseño modular del backend, permitiendo la expansión fácil con nuevas funcionalidades (reportes, integraciones con otros sistemas, etc.).
- **Mejora en la experiencia de usuario**: Interfaz limpia y fácil de usar, mejorando la gestión y reduciendo los errores humanos en el control del inventario.

---

## 🔧 **Instalación y Ejecución del Proyecto**

### 1. **Clonar el repositorio**

```bash
git clone https://github.com/OrelNaranjo/Portafolio.git
cd Portafolio
```
### 2. **Instalar dependencias con Nx**
Nx maneja las dependencias del monorepo. Para instalarlas, ejecuta:
```bash
yarn install
```
### 3. **Ejecutar el Frontend (Angular)**
Para ejecutar el frontend en modo desarrollo:
```bash
nx serve frontend
```
Esto iniciará el servidor de desarrollo de Angular y podrás acceder a la aplicación en http://localhost:4200.

### 4. **Ejecutar el Backend (NestJS)**
Para ejecutar el backend en modo desarrollo:
```bash
nx serve backend
```
Esto iniciará el servidor de desarrollo de NestJS y podrás acceder a la API en http://localhost:3000.

## 🔗 Enlaces de Interés
- **Frontend (Angular):** http://localhost:4200
- **Backend (NestJS):** http://localhost:3000
- **Repositorio del Proyecto:** GitHub - Portafolio

## 🚧 Demo
Actualmente en desarrollo, pronto estará disponible una demostración en vivo del sistema de control de inventario.

## 📝 Licencia

Este proyecto está bajo **Todos los derechos reservados**. No se permite el uso, la distribución ni la modificación sin el consentimiento expreso del autor.

---

> "El éxito de un programador no depende de su habilidad para escribir código, sino de su habilidad para entender el problema."  
— **Shigeru Miyamoto**

