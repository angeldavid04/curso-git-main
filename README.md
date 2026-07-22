# Repositorio nuevo con rama main

## 🤔 ¿Por qué cambiar a la rama main?

Hacer el cambio es usar un lenguaje más inclusivo y seguir los estándares modernos de plataformas como GitHub.

## 🌿 Cómo cambiar y configurar main

- **Cambiar nombre local**: Usa `git branch -m main` para renombrar tu rama actual.
- **Actualizar repositorio**: Sube los cambios con `git push -u origin main`.
- **Predeterminado global**: Configura Git para usarlo siempre con `git config --global init.defaultBranch main`.

El flujo básico se define de esta forma:

### Para repositorios nuevos

```bash
git init
git add .
git commit -m "Primer commit"
git branch -M main
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
```

### Para repositorios existentes

```bash
git branch -M main
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
```

---

Este repositorio es una práctica en forma de apunte del [curso de Git y Github](https://jonmircha.com/git) de JonMircha. Las secciones de código fueron extraidas del árticulo del curso.

[Repositorio principal de los apuntes del curso](https://github.com/angeldavid04/curso-git-main)
