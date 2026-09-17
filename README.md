# Práctica de programación básica con Scala

![Scala](https://img.shields.io/badge/Scala-2.12.21-DC322F?style=for-the-badge&logo=scala&logoColor=white)
![Java](https://img.shields.io/badge/JDK-17-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![OS](https://img.shields.io/badge/Windows-11-0078D6?style=for-the-badge&logo=windows11&logoColor=white)
![sbt](https://img.shields.io/badge/sbt-build_tool-EE0000?style=for-the-badge&logo=sbt&logoColor=white)
![Jupyter](https://img.shields.io/badge/JupyterLab-Almond-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## Autor

| Campo | Valor |
|---|---|
| **Nombre y apellidos** | Emmanuel Grande Sierra |
| **Repositorio** | `[https://github.com/usuario/practica-scala]` |

---

## Entorno

- **Sistema operativo:** Windows 11
- **Scala:** 2.12.21
- **Java:** JDK 17

---

## Estructura del repositorio

```
practica-scala/
│
├── README.md
│
├── parte1/
│   ├── README.md
│   ├── notebook/
│   │   └── entorno-scala.ipynb
│   ├── vscode/
│   │   └── scala-vscode/
│   └── intellij/
│       └── scala-intellij/
│
├── parte2/
│   ├── README.md
│   ├── parte2-scala.ipynb
│   └── images/
│
└── parte3/
    ├── README.md
    ├── parte3-1-vscode/
    │   ├── README.md
    │   └── torneo-twenty-one/
    └── parte3-2-intellij/
        ├── README.md
        └── analizador-notas/
```

---

## Parte 1 — Entornos de trabajo

> Preparación de tres entornos independientes capaces de ejecutar código Scala 2.12.21 en Windows 11.

### Entorno 1 — JupyterLab + Almond Kernel

Entorno interactivo basado en notebooks para ejecutar Scala de forma inmediata mediante el kernel Almond.

**Herramientas:** JupyterLab · Almond Kernel · Scala 2.12.21

[Ver documentación completa](parte1/README.md#entorno-1--jupyterlab--almond-kernel--scala-21221)

---

### Entorno 2 — Visual Studio Code + Metals + sbt

Entorno orientado al desarrollo de proyectos Scala estructurados y compilables mediante sbt, con soporte de Metals para autocompletado y navegación de código.

**Herramientas:** Visual Studio Code · Scala (Metals) · JDK 17 · sbt · Scala 2.12.21

[Ver documentación completa](parte1/README.md#entorno-2--visual-studio-code--metals--scala-21221--jdk-17--sbt)

---

### Entorno 3 — IntelliJ IDEA Community + sbt

Entorno basado en un IDE completo, especialmente útil para proyectos con múltiples archivos, con plugin oficial de Scala y gestión de proyectos mediante sbt.

**Herramientas:** IntelliJ IDEA Community · Plugin Scala · JDK 17 · sbt · Scala 2.12.21

[Ver documentación completa](parte1/README.md#entorno-3--intellij-idea-community--scala-21221--sbt)

---

## Parte 2 — Programación con Scala en JupyterLab

> 15 ejercicios de programación en Scala desarrollados en JupyterLab con Almond Kernel, cubriendo los contenidos de los capítulos 1, 2 y 3 del curso.

**Entorno utilizado:** JupyterLab · Almond Kernel · Scala 2.12.21

**Contenidos trabajados:**

- `val` y `var` · Tipos básicos · Inferencia de tipos
- Funciones · `Array` · `List` · `Nil` · `::` · `:::`
- `if / else if / else` · Operadores relacionales y lógicos
- `while` · `foreach` · Mutabilidad e inmutabilidad
- Estilo imperativo y estilo funcional

**Ejercicios incluidos:**

| # | Título |
|---|---|
| 1 | Variables, tipos e inferencia |
| 2 | `val`, `var` y reasignación |
| 3 | Tipos numéricos y precisión |
| 4 | Función `bust` — mano pasada de 21 |
| 5 | Comparación de dos manos (`maxHand`) |
| 6 | Decidir el ganador de una partida |
| 7 | Arrays y mutabilidad |
| 8 | Creación e inicialización de Arrays |
| 9 | Recorrer un Array con `while` |
| 10 | Listas e inmutabilidad |
| 11 | Construcción y concatenación de listas |
| 12 | Operadores relacionales y lógicos |
| 13 | `foreach` y funciones como valores |
| 14 | Efectos secundarios y estilo de programación |
| 15 | Programa integrado: torneo de Twenty-One |

[Ver documentación y Notebook](parte2/README.md)

---

## Parte 3 — Mini proyectos en entornos de desarrollo

> Dos mini proyectos Scala desarrollados en entornos IDE, aplicando de forma integrada los conceptos de los capítulos 1, 2 y 3 del curso.

### Parte 3.1 — Torneo de Twenty-One (VS Code + Metals + sbt)

Clasificador de resultados de un torneo de Twenty-One. El programa analiza las puntuaciones de varios jugadores a lo largo de dos rondas, determina quién se ha pasado de 21, calcula estadísticas y compara el resultado entre rondas.

**Herramientas:** Visual Studio Code · Metals · Scala 2.12.21 · JDK 17 · sbt

**Funciones implementadas:** `bust` · `estadoMano` · `mejorMano`

**Conceptos aplicados:** `List` · `Array` · `while` · `foreach` · `if/else` · funciones · operadores

[Ver documentación](parte3/parte3-1-vscode/README.md)

---

### Parte 3.2 — Analizador de calificaciones (IntelliJ IDEA + sbt)

Aplicación que analiza las calificaciones de un grupo de estudiantes en dos evaluaciones. Determina aprobados y suspensos, clasifica las notas, calcula estadísticas y compara el rendimiento entre evaluaciones.

**Herramientas:** IntelliJ IDEA Community · Plugin Scala · Scala 2.12.21 · JDK 17 · sbt

**Funciones implementadas:** `aprobado` · `estadoNota` · `maxNota` · `clasificacion`

**Conceptos aplicados:** `List` · `Array` · `::` · `while` · `if/else if/else` · funciones · operadores

[Ver documentación](parte3/parte3-2-intellij/README.md)

---
