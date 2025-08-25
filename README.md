<div align="center">

# 📘 Comandos Básicos de Git

Bienvenido a esta guía visual e interactiva de los comandos más usados en **Git y GitHub**, ideal para quienes están iniciando o desean repasar su conocimiento del control de versiones.

<img width="300" alt="web" src="https://github.com/user-attachments/assets/894fc9aa-b670-41b6-ab68-3eafdde10d84" />

<br>

[![My Skills](https://skillicons.dev/icons?i=git,github,vscode,html,css)](https://skillicons.dev)

> 🎯 Aprende Git desde cero con ejemplos simples, claros y aplicables en proyectos reales.

</div>

---

## 🚀 ¿Qué es Git?

**Git** es un sistema de control de versiones que te permite gestionar los cambios en tu código fuente, trabajar en equipo, y mantener el historial de tu proyecto.  
Es ampliamente utilizado en desarrollo web, software, y proyectos colaborativos.

🔗 [Ver aplicación en vivo](https://lenercodelab.github.io/GuiaDeGit/)

---

## 📂 Contenido de la guía

1. 📦 Comenzar tu proyecto con Git
2. ⚙️ Comandos esenciales del día a día
3. 🌿 Manejo de ramas (versiones paralelas)
4. 🌐 Trabajo con GitHub (remoto)
5. 🧹 Revertir o limpiar cambios
6. ✨ Herramientas avanzadas (`stash`, `rebase`, etc.)

---

## ✅ Guía paso a paso para comenzar con Git

### 🔹 Paso 1: Inicializa tu repositorio

```bash
git init
```

🔎 Esto convierte tu carpeta actual en un repositorio Git.

---

### 🔹 Paso 2: Configura tu nombre y correo

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

🔎 Esto asocia tus commits con tu identidad.

---

### 🔹 Paso 3: Añade archivos y crea tu primer commit

```bash
git add .
git commit -m "Primer commit"
```

🔎 `add` guarda los cambios y `commit` los registra en el historial.

---

### 🔹 Paso 4: Crea y cambia de rama (versión alternativa del proyecto)

```bash
git branch nueva-rama
git switch nueva-rama
```

🔎 Esto es útil para desarrollar nuevas funciones sin afectar el código principal.

---

### 🔹 Paso 5: Conecta tu proyecto a GitHub

1. Crea un repositorio en GitHub
2. Copia su URL
3. Luego en tu terminal:

```bash
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
```

🔎 Ahora tu proyecto está en la nube (GitHub) y puedes colaborar.

---

### 🔹 Paso 6: Traer y fusionar cambios

```bash
git pull origin main
git merge otra-rama
```

🔎 `pull` descarga los cambios remotos, `merge` combina ramas.

---

## 💡 Ejemplo práctico completo

```bash
# 1. Crea tu carpeta de proyecto
mkdir mi-proyecto
cd mi-proyecto

# 2. Inicia Git
git init

# 3. Crea un archivo
echo "# Mi Proyecto" > README.md

# 4. Agrega todo
git add .

# 5. Crea el primer commit
git commit -m "Primer commit"

# 6. Conecta con tu repositorio en GitHub
git remote add origin https://github.com/tu-usuario/mi-proyecto.git

# 7. Sube tu proyecto a la rama principal (main)
git push -u origin main

```

---

## ✨ Comandos útiles adicionales

```bash
git log --oneline         # Ver historial resumido
git status                # Ver estado actual
git revert <commit>       # Deshacer un commit sin perder historial
git reset --hard HEAD~1   # ⚠️ Eliminar el último commit y sus cambios
git stash                 # Guardar cambios sin commitear
```

---

## 📎 ¿Dónde está la guía visual?

Puedes ver la guía de comandos completa aquí:

<img alt="web" src="https://github.com/user-attachments/assets/894fc9aa-b670-41b6-ab68-3eafdde10d84" />

---

## 📌 Recomendaciones finales

- 💬 Practica con proyectos pequeños.
- 🔁 Usa `git log` y `git status` constantemente.
- 🔒 Si no estás seguro, **no uses `reset --hard`**.
- 🧠 Aprende `revert`, `stash` y `branch` con calma.

---

## 👨‍💻 Autor

Hecho con ❤️ por **LenerCodeLab**
Si te gusto dale tu estrellita no lo olvides :)

🔗 [GitHub](https://github.com/LenerCodeLab)

🔗 [Linkedin](https://www.linkedin.com/in/lenerhuamanperales)

---

## 🪪 Licencia

MIT — Libre de usar, mejorar y compartir.
