# Sistema de Inventarios - Fullstack (Angular + Spring Boot)

Este proyecto es un **sistema de inventarios** desarrollado con una arquitectura **Fullstack**, utilizando **Angular** en el frontend y **Spring Boot** en el backend.  
Permite la gestión eficiente de inventarios a través de una interfaz web moderna y un backend robusto.

---

## Tecnologías utilizadas

### Backend
- **Java** con **Spring Boot**
- **JPA** para la persistencia de datos
- IDE: **IntelliJ IDEA**

### Frontend
- **Angular**
- **HTML5**, **CSS3**
- IDE: **Visual Studio Code**

### Herramientas adicionales
- **Postman**: pruebas de peticiones y endpoints

---

## Instalación y uso

### 1. Clonar el repositorio
```bash
git clone https://github.com/ml-celiz/Java.git
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

### 3. Frontend - Angular
1. Abrir la carpeta del frontend en **Visual Studio Code**.  
2. Instalar dependencias:
   ```bash
   npm install
   ```
3. Iniciar el servidor de desarrollo:
   ```bash
   ng serve
   ```
4. El frontend estará disponible en:
   ```
   http://localhost:4200
   ```

---

## Pruebas con Postman
- Se incluye una colección de **endpoints** para realizar pruebas sobre el backend.  
- Endpoints principales:
  - `GET /api/productos` → listar productos
  - `POST /api/productos` → crear producto
  - `PUT /api/productos/{id}` → actualizar producto
  - `DELETE /api/productos/{id}` → eliminar producto

---
