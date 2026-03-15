# Práctica: Gestión de Entornos de Desarrollo (Git & GitHub)

Este repositorio contiene la resolución de la tarea **UD04-A2**, enfocada en el control de versiones distribuido utilizando **Git**, el IDE **NetBeans** y la plataforma **GitHub**.

## 🚀 Objetivo de la Práctica
El objetivo principal es implementar un flujo de trabajo profesional (Git Flow simplificado), gestionando diferentes ramas de desarrollo, resolviendo conflictos de sincronización y realizando integraciones mediante Pull Requests.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Java ☕
* **IDE:** NetBeans 19+
* **Control de Versiones:** Git (Bash)
* **Repositorio Remoto:** GitHub

## 📂 Estructura del Repositorio
El proyecto incluye un conjunto de clases Java que representan figuras geométricas:
* `Figura.java`: Clase abstracta base.
* `Cuadrado.java`, `Triangulo.java`, `Rectangulo.java`: Clases derivadas con lógica específica.
* `PruebaFigura.java`: Clase principal para tests de ejecución.

## 🔄 Flujo de Trabajo Realizado

### 1. Gestión de Ramas
Se han utilizado dos ramas principales para mantener la integridad del código:
* **`master`**: Rama principal que contiene el código estable y finalizado.
* **`develop`**: Rama de desarrollo donde se han realizado las modificaciones y refactorizaciones de las clases.

### 2. Ciclo de Desarrollo
1. **Clonación:** Réplica del repositorio remoto al entorno local mediante `git clone`.
2. **Desarrollo en `develop`:** Implementación de cambios y comentarios en las clases Java.
3. **Sincronización IDE:** Configuración del proyecto en NetBeans mediante el uso de "Existing Sources" y autenticación por **Personal Access Token (PAT)**.
4. **Pull Request (PR):** Una vez finalizado el desarrollo, se solicitó la integración de `develop` hacia `master` desde GitHub, resolviendo los commits pendientes y confirmando el *Merge*.

## ⚠️ Incidencias Resueltas
Durante el desarrollo se gestionaron y documentaron los siguientes desafíos técnicos:
- **Autenticación:** Resolución de errores 403 mediante el uso de tokens.
- **Sincronización:** Uso de `git pull` y `merge commit` para resolver divergencias entre el repositorio local y el remoto.
- **Configuración IDE:** Ajuste de las rutas de proyecto en NetBeans para evitar conflictos con la carpeta `.git`.

---
*Realizado por Alejandro San Emeterio - Estudiante de 1º Grado Superior DAM.*
