# 🚀 Backend Task Manager - Proyecto Integrador

Este es el servidor central para la gestión de tareas y usuarios, construido con un enfoque modular y escalable.

---

## 🎯 Propósito del Proyecto
El sistema permite la administración centralizada de tareas vinculadas a usuarios específicos, facilitando las siguientes operaciones:

* **🔍 Consulta por ID:** Validación inmediata de la existencia de usuarios en la base de datos.
* **📋 Visualización de Tareas:** Carga automática de títulos, estados y descripciones asociadas a cada perfil.
* **⚡ Formularios Dinámicos:** Interfaz de carga en tiempo real para el registro de nuevos pendientes tras la validación.

---

## 👥 Participantes
| Nombre | Rol / Responsabilidad |
| :--- | :--- |
| **Josué Chaparro Oviedo** | Desarrollador frontend |
| **Carol Dayana Lizarazo** | Desarrollador frontend |
| **Luis Carlos Villamizar Sánchez** | Desarrollador Backend |
| **Julian Andres Diaz Chaparro** | Desarrollador Backend |

---

## 📂 Estructura del Proyecto
La arquitectura sigue un patrón modular para separar las rutas de la lógica principal:

```text
backend-task-manager/
├── node_modules/       # Dependencias del proyecto
├── src/
│   ├── routes/         # Definición de endpoints
│   │   ├── tasks.routes.js
│   │   └── users.routes.js
│   └── app.js          # Configuración principal de Express
├── .env                # Variables de entorno (puertos, DB)
├── .gitignore          # Archivos excluidos de Git
├── package.json        # Scripts y metadatos
└── package-lock.json   # Árbol de dependencias exacto
```

---

## 🚀 Cómo ejecutar el servidor (Paso a Paso)

Sigue estas instrucciones para levantar el servicio en tu máquina local:

### 1️⃣ Instalar las dependencias
Abre una terminal en la carpeta raíz del proyecto y ejecuta el siguiente comando para descargar los módulos necesarios:
```bash
npm install
```

### 2️⃣ Configurar variables de entorno
Crea un archivo llamado `.env` en la raíz del proyecto (al mismo nivel que el archivo `package.json`) y define el puerto:
```env
PORT=3000
```

### 3️⃣ Iniciar el servidor
Para poner en marcha el servicio utilizando **Node.js**, ejecuta:
```bash
node src/app.js
```

### 4️⃣ Acceso y Pruebas
Una vez iniciado, el servidor estará escuchando peticiones. Puedes probarlo en tu navegador o en Postman ingresando a la siguiente dirección:
👉 `http://localhost:3000`

---
✨ *Proyecto Integrador - Universidad 2026*