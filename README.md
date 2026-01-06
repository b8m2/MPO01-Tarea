<!-- esto es un comentario y NO aparece en la versión web -->

# **TAREA UD 1: Herramientas de gestión de desarrollo colaborativo**
=======================================================
<!-- La negrita empieza y acaba con 2* -->
<!-- 1# indica que es un título de nivel 1 (el más importante); conforme se suman # aumentan los niveles de título (descienden su importancia); sirven para ordenar por apartados y subapartados--> 

Esta página web es un archivo Markdonw creado para documentar la tarea evaluable de la unidad didáctica 1 “Herramientas de gestión de desarrollo colaborativo”, con motivo del ejercicio 3. Dicha tarea trata sobre la creación de un proyecto web con HTML para aplicar los conocimientos adquiridos sobre Git y GitHub. Pertenece al módulo profesional optativo (Desarrollo y despliegue en entornos colaborativos - Computación en la nube) del Ciclo Formativo de Grado Superior en Administración de Sistemas Informáticos en Red (ASIR).

## **Tabla de contenido** 
<!-- título de nivel 2 -->
- [Descripción](#descripción) <!-- enlace al apartado descripción; en el apartado correspondiente con poner descripción sobra, pues Markdown reconoce solo la palabra (da igual mayúsculas que minúsculas) no el nivel del título -->
- [Estructura del proyecto](#estructura-del-proyecto)
- [Mejoras implementadas](#mejoras-implementadas)
- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Autor](#autor)

## Descripción

Proyecto web desarrollado con HTML para practicar el uso de Git, como sistema de control de versiones, y GitHub, como plataforma de repositorio remoto. Se ha trabajado con ramas (branches), commits descriptivos y Pull Requests para integrar mejoras de forma organizada. Todo ello con el objetivo principal de aprender las buenas prácticas del desarrollo colaborativo.

## Estructura del proyecto
``` <!-- ``` este apóstrofe invertido sirve para escribir código; si solo queremos escribir 1 línea de código ponemos solo 1` -->
*MPO01-Tarea/* 
- .vscode/          (Configuración del editor Visual Studio Code)
- .gitignore        (Archivos excluidos del repositorio)
- index.html        (Página principal del proyecto)
- README.md         (Documentación del proyecto - este archivo)
```

## Mejoras implementadas

### 1. Menú de navegación
- Implementación de un menú de navegación con enlaces internos
- Permite navegar a diferentes secciones de la página: `#inicio`, `#sobre-mi`, `#proyectos`, `#contacto`
- Utiliza la etiqueta semántica `<nav>` de HTML5
- Desarrollado en la rama: `feature/menu`

### 2. Footer con redes sociales
- Añadido pie de página con enlaces a redes sociales
- Incluye enlaces a GitHub, LinkedIn y Twitter con `target="_blank"` para abrir en nueva pestaña
- Información de copyright con entidad HTML `&copy;`
- Utiliza la etiqueta semántica `<footer>` de HTML5
- Desarrollado en la rama: `feature/footer`

## Tecnologías utilizadas

| Tecnología | Descripción |
|------------|-------------|
| **HTML5** | Estructura y contenido de la página web |
| **Git** | Sistema de control de versiones distribuido |
| **GitHub** | Plataforma de repositorio remoto y colaboración |
| **Markdown** | Lenguaje de marcado para documentación |

## Instalación

Para visualizar este proyecto en tu máquina local:

1. Clona el repositorio:
```
git clone https://github.com/b8m2/MPO01-Tarea.git
```

2. Navega al directorio del proyecto:
```bash
cd MPO01-Tarea
```

3. Abre el archivo `index.html` en tu navegador:
```bash
firefox index.html
```
O simplemente haz doble clic en el archivo `index.html`.

## Autor

** b8m2 **  
Estudiante de Desarrollo y despliegue en entornos colaborativos (ASIR)
[Mi perfil de GitHub](https://github.com/b8m2)  <!-- este es un enlace a web --> 
Curso 2025-2026

---


