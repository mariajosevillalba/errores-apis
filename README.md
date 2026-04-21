# 🚀 CLASE 2: Construcción de rutas completas con ayuda de IA

## 📘 Descripción

En esta clase se desarrolla un CRUD completo utilizando FastAPI, enfocado en la correcta construcción de endpoints, validación de datos y uso de inteligencia artificial como apoyo para mejorar y depurar el código.

---

## 🎯 Objetivos

* Consolidar el uso de endpoints (GET, POST, PUT, DELETE)
* Construir rutas correctamente estructuradas
* Validar datos con Pydantic
* Identificar y corregir errores comunes (422, rutas mal definidas, etc.)
* Utilizar IA para mejorar código y detectar fallos

---

## 🧠 Temas abordados

* Creación de APIs con FastAPI
* Modelos de datos con Pydantic
* Validación automática de datos
* Manejo de errores con HTTPException
* Documentación automática con Swagger
* Uso de IA para depuración y mejora de código

---

## 🛠️ Tecnologías utilizadas

* Python 3.10+
* FastAPI
* Uvicorn
* Pydantic

---

## 📂 Estructura del proyecto

```
main.py
```

---

## ⚙️ Instalación y ejecución

### 1. Clonar el repositorio

### Instalar dependencias

```bash
pip install fastapi uvicorn
```

### Ejecutar el servidor

```bash
uvicorn main:app --reload
```

---

## 🌐 Acceso a la API

* API: http://127.0.0.1:8000
* Documentación interactiva (Swagger): http://127.0.0.1:8000/docs

---

## 🎥 Diapositivas de la clase

Puedes ver la presentación aquí:
👉 https://gamma.app/docs/Clase-2-Construccion-de-rutas-completas-con-ayuda-de-IA-8o8rbxqdgtylqqk

---

## 🧪 Endpoints principales

| Método | Ruta                | Descripción            |
| ------ | ------------------- | ---------------------- |
| GET    | /tareas             | Listar tareas          |
| POST   | /tareas             | Crear tarea            |
| PUT    | /tareas/{id}        | Actualizar tarea       |
| DELETE | /tareas/{id}        | Eliminar tarea         |
| GET    | /tareas/completadas | Ver tareas completadas |
| GET    | /tareas/pendientes  | Ver tareas pendientes  |

---

## ⚠️ Errores comunes trabajados

* Error 422 (datos inválidos)
* Rutas mal definidas
* Uso incorrecto de parámetros
* Manejo incorrecto de índices
* Problemas de validación

---

## 🤖 Uso de IA en la clase

Durante la clase se utilizó IA para:

* Detectar errores en el código
* Proponer soluciones
* Optimizar endpoints
* Mejorar validaciones

---

## 🎯 Conclusión

Esta clase permite comprender cómo construir APIs de manera profesional, aplicando buenas prácticas, validaciones y herramientas modernas como la inteligencia artificial para mejorar el desarrollo.

---

## 👩‍💻 Autor

María José Villalba Lozano
