# 📘 Git vs GitHub — Tutorial básico

## 🧠 Concepto general

Antes de usar GitHub correctamente, es fundamental entender que **Git y GitHub no son lo mismo**, aunque trabajan juntos.

| Herramienta | Qué es                                  | Dónde funciona         |
| ----------- | --------------------------------------- | ---------------------- |
| **Git**     | Sistema de control de versiones         | Local (tu computadora) |
| **GitHub**  | Plataforma para alojar repositorios Git | Nube (internet)        |

***

## 🔧 1. ¿Qué es Git?

**Git** es una herramienta que te permite:

* Guardar versiones del código
* Ver cambios a lo largo del tiempo
* Volver a versiones anteriores
* Trabajar sin conexión

### ✅ Ejemplo práctico

```bash
git init
```

👉 Crea un repositorio Git en tu carpeta local.

```bash
git add .
git commit -m "Primer commit"
```

👉 Guarda una versión de tu proyecto.

📌 Todo esto ocurre **en tu máquina**, sin necesidad de internet.

***

## ☁️ 2. ¿Qué es GitHub?

**GitHub** es una plataforma web que:

* Almacena repositorios Git en la nube
* Permite colaborar con otros desarrolladores
* Facilita revisar código (Pull Requests)
* Integra herramientas como CI/CD, issues, proyectos, etc.

***

## 🔗 3. Cómo se conectan Git y GitHub

Git y GitHub trabajan juntos mediante repositorios remotos.

### 🪜 Flujo típico

1. Creas proyecto local con Git
2. Creas repositorio en GitHub
3. Conectas ambos
4. Subes tu código

***

## ⚙️ 4. Ejemplo completo paso a paso

### ✅ Paso 1: Crear repositorio local

```bash
git init
```

***

### ✅ Paso 2: Agregar archivos

```bash
git add .
git commit -m "Inicial"
```

***

### ✅ Paso 3: Crear repositorio en GitHub

* Vas a: <https://github.com>
* Click en **New repository**
* Nombrarlo (ej: `mi-proyecto`)

***

### ✅ Paso 4: Conectar Git con GitHub

```bash
git remote add origin https://github.com/usuario/mi-proyecto.git
```

***

### ✅ Paso 5: Subir código

```bash
git push -u origin main
```

👉 Ahora tu código:

* Existe localmente (Git)
* Está respaldado en la nube (GitHub)

***

## 🧩 5. Analogía sencilla

Piensa así:

* **Git = tu historial de Word**
* **GitHub = Google Drive para compartir ese documento**

***

## ⚠️ Errores comunes

* ❌ Pensar que GitHub reemplaza Git
* ❌ Usar GitHub sin entender commits
* ❌ No usar Git localmente (perder control de versiones)

***

## ✅ Resumen

* **Git** gestiona versiones en tu computadora
* **GitHub** permite compartir y colaborar en línea
* Usas **Git para trabajar** y **GitHub para publicar**

***

## 🚀 Siguiente paso

Una vez que entiendes esto, el siguiente nivel es dominar:

* `commit`
* `branch`
* `pull request`
