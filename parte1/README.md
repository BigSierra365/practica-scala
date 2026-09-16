# Práctica 1 - Parte 1: Entornos de Scala

![Scala](https://img.shields.io/badge/Scala-2.12.21-DC322F?style=for-the-badge&logo=scala&logoColor=white)
![Java](https://img.shields.io/badge/JDK-17-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![OS](https://img.shields.io/badge/Windows-11-0078D6?style=for-the-badge&logo=windows11&logoColor=white)
![sbt](https://img.shields.io/badge/sbt-build_tool-EE0000?style=for-the-badge&logo=sbt&logoColor=white)

---

## 🟠 Entorno 1 — JupyterLab + Almond Kernel + Scala 2.12.21

### 1. Instalación y arranque de JupyterLab.
#### 1.1. Requerimientos previos
- **Actualizar version de `pip`**

#### 1.2. Descarga de JupyterLab
- **Método de instalación:** Gestor de paquetes de Python `pip`
##### Abrimos la consola de comandos **cmd** y escribimos el siguiente comando:
```cmd
pip install jupyterlab
```

#### Inicio del servicio

- **Metodo de acceso:** Interfaz web utilizando el URL generado en el levantamiento del servicio (`http://localhost:8888/lab`).
- **Navegador utilizado:** `Google Chrome`.

![JupyterLab en ejecución](images/02_jupyterServerLaunch.png)





### 3. Instalación de Almond Kernel

`[Explica cómo instalaste Almond: coursier, comando utilizado, versión de Scala especificada, etc.]`

```powershell
[comando de instalación de Almond]
```

Tras la instalación, al crear un nuevo Notebook aparece la opción de kernel correspondiente a Scala.

![Almond disponible como kernel](images/jupyter-almond.png)

### 4️⃣ Verificación de la versión de Scala

Se creó un nuevo Notebook con Almond y se ejecutó una celda para comprobar la versión utilizada:

```scala
[código utilizado para comprobar la versión de Scala]
```

![Versión de Scala utilizada](images/jupyter-scala-version.png)

### 5️⃣ Ejecución de código Scala

**Prueba 1 — Concatenación de cadenas**

```scala
val nombre = "Scala"
val version = "2.12.21"

println(s"Hola desde $nombre $version")
```

![Ejecución prueba 1](images/[nombre-de-tu-captura-1].png)

**Prueba 2 — Operación numérica**

```scala
val a = 10
val b = 20
val resultado = a + b

println(resultado)
```

![Ejecución prueba 2](images/[nombre-de-tu-captura-2].png)

**Prueba 3 — Colección sencilla**

```scala
val lenguajes = List("Scala", "Java", "Python")

println(lenguajes)
```

![Ejecución prueba 3](images/[nombre-de-tu-captura-3].png)

### ✅ Checklist de evidencias — Entorno 1

- [ ] JupyterLab ejecutándose
- [ ] Almond disponible como kernel
- [ ] Notebook utilizando Scala
- [ ] Versión de Scala utilizada
- [ ] Ejecución correcta de las tres pruebas

---
