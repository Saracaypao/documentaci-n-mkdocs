# 🐾 Bienvenida a Adoptame

> *"Salvar a un animal no cambia el mundo entero — pero sí cambia el mundo de ese animal."*

**Adoptame** es un refugio virtual dedicado a conectar mascotas rescatadas con familias que puedan darles una segunda oportunidad. Aquí encontrarás perritos y gatitos esperando su hogar soñado, junto con toda la información que necesitas para adoptar de forma responsable. 🌷

---

![Mascotas esperando ser adoptadas](img/imagen.jpg)

---

## 🌸 ¿Qué encontrarás aquí?

Esta wiki está organizada en tres secciones para guiarte fácilmente:

| Sección | Contenido |
|---|---|
| 🐾 [Mascotas en Adopción](mascotas.md) | Perfiles de peluditos disponibles, razas, edades y personalidades |
| 📋 [Proceso de Adopción](proceso.md) | Requisitos, pasos, costos y cómo iniciar tu solicitud |

---

## 🛠️ Información técnica del sitio

Este sitio fue construido con **MkDocs** y el tema **Material for MkDocs**. A continuación encontrarás los comandos esenciales para trabajar con él localmente.

### ⚙️ Instalación del entorno

=== "🪟 Windows"

    ```powershell
    # 1. Verifica que Python esté instalado
    python --version

    # 2. Actualiza pip
    python -m pip install --upgrade pip

    # 3. Instala Material for MkDocs y extensiones
    pip install mkdocs-material pymdown-extensions
    ```

=== "🍎 macOS"

    ```bash
    # 1. Instala Python con Homebrew (si no lo tienes)
    brew install python

    # 2. Actualiza pip
    pip3 install --upgrade pip

    # 3. Instala Material for MkDocs y extensiones
    pip3 install mkdocs-material pymdown-extensions
    ```

=== "🐧 Linux (Ubuntu/Debian)"

    ```bash
    # 1. Actualiza el sistema e instala Python
    sudo apt update && sudo apt install python3 python3-pip

    # 2. Instala Material for MkDocs y extensiones
    pip3 install mkdocs-material pymdown-extensions

    # 3. Verifica la instalación
    mkdocs --version
    ```

---

### 🚀 Cómo correr el proyecto

=== "▶️ Servidor local"

    ```bash
    # Levanta el servidor de desarrollo
    # El sitio se actualiza en tiempo real al guardar
    mkdocs serve
    ```

    El sitio estará disponible en:

    ```
    http://127.0.0.1:8000
    ```

=== "📦 Generar sitio estático"

    ```bash
    # Genera todos los archivos HTML en la carpeta site/
    mkdocs build
    ```

    Estructura generada:

    ```
    site/
    ├── index.html
    ├── mascotas/
    ├── proceso/
    └── assets/
    ```

=== "🌐 Publicar en GitHub Pages"

    ```bash
    # Sube el sitio directo a la rama gh-pages
    mkdocs gh-deploy
    ```

    Luego en GitHub ve a:
    **Settings → Pages → Branch: gh-pages → Save**

---

!!! tip "Consejo de desarrollo"
    Mantén `mkdocs serve` corriendo mientras editas tus archivos `.md`. El navegador se actualizará automáticamente con cada cambio que guardes. 🔄

!!! note "Proyecto académico"
    Este sitio fue creado como proyecto académico utilizando **MkDocs** y el tema **Material for MkDocs**. El contenido es ilustrativo e inspirado en refugios de animales reales.

---

¿Lista para conocer a los peluditos? 🐕 Visita **[Mascotas en Adopción](mascotas.md)** o aprende sobre el **[Proceso de Adopción](proceso.md)**. 💜
