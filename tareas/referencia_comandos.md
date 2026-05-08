# Comandos de referencia rápida Git

Este archivo es solo para que recuerdes los comandos básicos durante el certamen.

## Configuración inicial
```bash
git config --global user.name "Tu Nombre"
git config --global user.email "correo@ejemplo.com"
```

## Flujo básico de trabajo
```bash
git status          # Ver estado actual
git add archivo     # Preparar archivo
git add .           # Preparar todos los cambios
git commit -m "mensaje descriptivo"   # Confirmar cambios
git push origin main                  # Subir a GitHub
git pull origin main                  # Bajar cambios de GitHub
```

## Ver historial
```bash
git log             # Historial completo
git log --oneline   # Historial resumido (una línea por commit)
```
