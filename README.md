# 💊 POCMedicamento — Sistema de Gestión de Medicamentos

![Java](https://img.shields.io/badge/Java-17+-orange)
![Maven](https://img.shields.io/badge/Build-Maven-blue)
![Estado](https://img.shields.io/badge/Estado-Proyecto%20Académico-success)
![Licencia](https://img.shields.io/badge/Licencia-Educativa-lightgrey)

---

## 📖 Descripción General

**POCMedicamento** es una aplicación de escritorio desarrollada en **Java** que permite la **gestión de medicamentos** mediante operaciones CRUD utilizando almacenamiento persistente con **archivos de acceso aleatorio (`RandomAccessFile`)**.

El proyecto fue diseñado como una prueba de concepto académica para aplicar conocimientos fundamentales de:

* Programación Orientada a Objetos (POO)
* Manejo avanzado de archivos
* Desarrollo de interfaces gráficas
* Separación entre lógica de negocio y presentación
* Persistencia de datos sin bases de datos

---

## ✨ Funcionalidades

* ✅ Registro de medicamentos
* 🔍 Búsqueda de medicamentos por ID
* ✏️ Actualización de registros
* ❌ Eliminación de medicamentos
* 📋 Listado completo de registros
* 💾 Almacenamiento persistente en archivos
* 🧩 Arquitectura modular (Frontend / Backend)

---

## 🏗️ Arquitectura del Sistema

El proyecto sigue una estructura organizada por capas:

```id="p8b6zw"
POCMedicamento/
│
├── data/                     # Archivo de almacenamiento
│   └── registros.txt
│
├── backend/                  # Lógica del sistema
│   ├── Medicamento.java
│   └── FuncionesMedicamento.java
│
├── frontend/                 # Interfaces gráficas
│   ├── GUIPrincipal.java
│   ├── GUIBuscar.java
│   ├── GUIEliminar.java
│   ├── GUIModificar.java
│   └── GUIListar.java
│
└── main/
    └── POCMedicamento.java
```

### Principios aplicados

* Separación de responsabilidades
* Reutilización de código
* Mantenimiento sencillo
* Acceso directo a registros mediante posiciones en archivo

---

## 🛠️ Tecnologías Utilizadas

| Tecnología       | Uso                     |
| ---------------- | ----------------------- |
| Java 17+         | Lenguaje principal      |
| Java Swing       | Interfaz gráfica        |
| Maven            | Gestión de dependencias |
| RandomAccessFile | Persistencia de datos   |
| POO              | Diseño del sistema      |

---

## ⚙️ Requisitos

Antes de ejecutar el proyecto debes tener instalado:

* JDK 17 o superior
* Apache Maven
* IDE recomendado:

  * NetBeans
  * IntelliJ IDEA
  * Eclipse

---

## 🚀 Instalación y Ejecución

### 1️⃣ Clonar el repositorio

```bash id="6xw1o3"
git clone https://github.com/tu-usuario/POCMedicamento.git
cd POCMedicamento
```

---

### 2️⃣ Compilar el proyecto

```bash id="7ib3sj"
mvn clean install
```

---

### 3️⃣ Ejecutar la aplicación

```bash id="pqg4bx"
mvn exec:java
```

También puedes ejecutarlo directamente desde tu IDE favorito.

---

## 💾 Modelo de Almacenamiento

El sistema utiliza **archivos de acceso aleatorio**, lo que permite:

* Acceder directamente a un registro específico
* Modificar datos sin reescribir todo el archivo
* Mejor rendimiento frente a archivos secuenciales
* Implementar operaciones CRUD sin base de datos

Cada medicamento se almacena como un **registro de longitud fija**, facilitando su localización dentro del archivo.

---

## 🎯 Objetivo Académico

Este proyecto tiene como finalidad comprender y aplicar:

* Organización de archivos
* Acceso secuencial vs acceso aleatorio
* Persistencia de datos
* Diseño de aplicaciones de escritorio
* Arquitectura básica de software

---

## 📸 Módulos del Sistema

| Módulo         | Descripción              |
| -------------- | ------------------------ |
| Menú Principal | Navegación general       |
| Buscar         | Consulta por ID          |
| Modificar      | Actualización de datos   |
| Eliminar       | Eliminación de registros |
| Listar         | Visualización completa   |

---

## 👨‍💻 Autor

 ** Laura Ramirez,
Johan Soto,
Daniel Ayala **

** Universidad de ibagué año 2026 **

---

## 📄 Licencia

Proyecto desarrollado únicamente con fines **educativos y académicos**.
Libre para estudio, modificación y aprendizaje.



---
