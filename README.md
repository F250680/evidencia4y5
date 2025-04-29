# 🚀 CONFIGURACIÓN DE HERRAMIENTAS DE VERSIONAMIENTO 🚀

![Versioning Banner](https://via.placeholder.com/800x200?text=Control+de+Versiones)

## 📋 Descripción

Este proyecto documenta la instalación y configuración de herramientas de versionamiento para el control de código, como parte del programa de formación en **Análisis y desarrollo de software**. Esta actividad corresponde a la fase de ejecución del proyecto formativo "Construcción de software integrador de tecnologías orientadas a servicios".

## 🎯 Objetivos

- ✅ Instalar correctamente herramientas de versionamiento
- ✅ Configurar herramientas de versionamiento local sin errores
- ✅ Implementar herramientas de versionamiento remoto
- ✅ Aplicar control de cambios en el código de manera efectiva

## 💻 Herramientas utilizadas

### Versionamiento Local
- **Git** 📂 - Sistema de control de versiones distribuido
  - Instalación
  - Configuración inicial
  - Comandos básicos

### Versionamiento Remoto
- **GitHub** ☁️ - Plataforma de alojamiento de código
  - Creación de cuenta
  - Configuración de SSH
  - Vinculación con repositorio local
- **GitLab** 🦊 (Alternativa)
  - Características principales
  - Diferencias con GitHub

## 🛠️ Proceso de instalación

### 1. Instalación de Git (Local)

```bash
# Para sistemas basados en Debian/Ubuntu
sudo apt-get update
sudo apt-get install git

# Para sistemas basados en Red Hat/Fedora
sudo dnf install git

# Para macOS (usando Homebrew)
brew install git

# Para Windows
# Descargar el instalador desde https://git-scm.com/download/win
```

### 2. Configuración básica de Git

```bash
# Configurar nombre de usuario
git config --global user.name "Tu Nombre"

# Configurar correo electrónico
git config --global user.email "tucorreo@ejemplo.com"

# Configurar editor predeterminado
git config --global core.editor "tu-editor-preferido"
```

### 3. Configuración de GitHub (Remoto)

1. 📝 Crear una cuenta en [GitHub](https://github.com/)
2. 🔑 Generar claves SSH:
   ```bash
   ssh-keygen -t rsa -b 4096 -C "tucorreo@ejemplo.com"
   ```
3. 🔄 Agregar la clave SSH a tu cuenta de GitHub
4. 🔗 Verificar la conexión:
   ```bash
   ssh -T git@github.com
   ```

## 📊 Flujo de trabajo básico

1. **Inicializar repositorio** ⚡
   ```bash
   git init
   ```

2. **Clonar repositorio existente** 📥
   ```bash
   git clone url_del_repositorio
   ```

3. **Verificar estado del repositorio** 🔍
   ```bash
   git status
   ```

4. **Agregar cambios** ➕
   ```bash
   git add .
   ```

5. **Confirmar cambios** ✅
   ```bash
   git commit -m "Mensaje descriptivo"
   ```

6. **Enviar cambios al repositorio remoto** 📤
   ```bash
   git push origin main
   ```

7. **Obtener cambios del repositorio remoto** 📥
   ```bash
   git pull origin main
   ```

## 🌟 Mejores prácticas

- 📝 Escribir mensajes de commit descriptivos
- 🔄 Actualizar tu repositorio local antes de empezar a trabajar
- 🌿 Utilizar ramas para desarrollar nuevas funcionalidades
- 🔍 Revisar los cambios antes de hacer commit
- 🤝 Resolver conflictos de fusión de manera adecuada

## 📚 Recursos adicionales

- [Documentación oficial de Git](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [Pro Git Book](https://git-scm.com/book/es/v2)

## 📞 Contacto

Para más información o soporte, contactar a:
- Email: tutor@ejemplo.com
- Plataforma educativa: [Enlace a la plataforma]

---
⭐ **Proyecto realizado por Franco Fernando Ojeda** ⭐
⭐ **Presentado al profesor Julián Andrés Loaiza López** ⭐
⭐ **Programa de formación en Análisis Y Desarrollo De Software - Ficha 2885501** ⭐
