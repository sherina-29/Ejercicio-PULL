# 📘 Guía rápida de Git (Fork, ramas y PR)

## 🚀 Conceptos clave (rápido)

- **Fork:** tu copia del repositorio principal en tu cuenta. Ideal para colaborar sin permisos directos.
- **Remotos:**
  - `origin` → tu Fork (o el repo principal si eres colaborador).
  - `upstream` → el repositorio principal (solo en flujo por Fork).
- **PR (Pull Request):** solicitud para integrar tus cambios a otra rama (normalmente `main` del repo principal).
- **Ramas (branches):** siempre debes trabajar en una rama distinta a `main`.

> 💡 **Regla #1:** Nunca trabajes directamente en `main`. Crea una rama por cada feature o fix.

---

## ✅ Checklist previo (ambos flujos)

Antes de empezar, asegúrate de lo siguiente:

- [ ] Tener Git instalado y configurado:
  ```bash
  git --version
  git config user.name "Tu Nombre"
  git config user.email "tu@email.com"

  
##### Hola, solo estoy de paso
