# **Git Hooks: Ejemplo de Hook Pre-Commit**

Este proyecto demuestra cómo configurar un **hook pre-commit** en Git para validar el formato de archivos antes de realizar un commit. Este ejemplo verifica el formato de **JavaScript**, **Python**, y **Shell Scripts** utilizando herramientas como Prettier, Flake8 y ShellCheck.

---

## 📚 **Descripción**

Los **Git Hooks** son scripts que se ejecutan automáticamente en determinados eventos de Git, como `commit`, `push`, o `merge`.  
El hook pre-commit en este proyecto:
- Revisa los archivos preparados (`staged`) antes de un commit.
- Bloquea el commit si los archivos no cumplen con las reglas de formato.

---

## 📂 **Estructura del Proyecto**

```plaintext
githooks-example/
├── scripts/
│   └── pre-commit   # Script del hook pre-commit
├── src/
│   ├── example.js   # Archivo JavaScript de ejemplo
│   ├── example.py   # Archivo Python de ejemplo
│   ├── example.sh   # Script Bash de ejemplo
├── README.md        # Documentación del proyecto
