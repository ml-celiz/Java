# Sistema de Recursos Humanos - Fullstack (React.js + Spring Boot)

Este proyecto es un **sistema de recursos humanos (empleados)** desarrollado con una arquitectura **Fullstack**, utilizando **React.js** en el frontend y **Spring Boot** en el backend.  
Permite la gestión eficiente de recursos humanos (empleados) a través de una interfaz web moderna y un backend robusto.

---

## Tecnologías utilizadas

### Backend
- **Java** con **Spring Boot**
- **JPA** para la persistencia de datos
- IDE: **IntelliJ IDEA**

### Frontend
- **React.js**
- **HTML5**, **CSS3**
- IDE: **Visual Studio Code / cualquier IDE compatible**

### Herramientas adicionales
- **Postman**: pruebas de peticiones y endpoints

---

## Instalación y uso

### 1. Clonar el repositorio
```bash
git clone https://github.com/usuario/sistema-recursos humanos (empleados).git
```

### 2. Backend - Spring Boot
1. Abrir el proyecto en **IntelliJ IDEA**.  
2. Configurar la base de datos (en `application.properties` o `application.yml`).  
3. Ejecutar la aplicación:
   ```bash
   mvn spring-boot:run
   ```
4. El backend se levantará en:
   ```
   http://localhost:8080
   ```

### 3. Frontend - React.js
1. Abrir la carpeta del frontend en **Visual Studio Code / cualquier IDE compatible**.  
2. Instalar dependencias:
   ```bash
   npm install
   ```
3. Iniciar el servidor de desarrollo:
   ```bash
   npm start
   ```
4. El frontend estará disponible en:
   ```
   http://localhost:3000
   ```

---

## Pruebas con Postman
- Se incluye una colección de **endpoints** para realizar pruebas sobre el backend.  
- Endpoints principales:
  - `GET /api/empleados` → Listar empleados
  - `POST /api/empleados` → Crear empleado
  - `PUT /api/empleados/{id}` → Actualizar empleado
  - `DELETE /api/empleados/{id}` → Eliminar empleado
