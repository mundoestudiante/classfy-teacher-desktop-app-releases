# Classfy Teacher Desktop App <img src="assets/icon.png" alt="Classfy Logo" width="15">

**Classfy Teacher Desktop App** es una aplicación de escritorio desarrollada con Electron para facilitar la experiencia de los docentes en la plataforma [Classfy Teacher](https://teacher.classfy.online).

Este repositorio está destinado exclusivamente a la distribución de _releases_ oficiales de la aplicación para Windows, macOS y Linux. Aquí encontrarás las versiones más recientes y estables para descargar e instalar en tu sistema operativo preferido.

---

## 📥 Descarga

Dirígete a la sección de [Releases](https://github.com/mundoestudiante/classfy-teacher-desktop-releases/releases) para descargar la última versión disponible para tu sistema operativo.

---

## 🖥️ Instalación

Sigue las instrucciones según tu sistema operativo para instalar la aplicación:

### **Windows**

1. Descarga el archivo `.exe` de la última [release](https://github.com/mundoestudiante/classfy-teacher-desktop-releases/releases).
2. Haz doble clic en el archivo descargado.
3. Sigue el asistente de instalación (NSIS) y completa el proceso. (Tal vez tengas que hacer clic en **_"Más información"_** para poder aceptar la instalación)
4. Una vez instalado, encontrarás **Classfy Teacher Desktop App** en tu menú de inicio.

### **macOS**

1. Descarga el archivo `.dmg` desde la última [release](https://github.com/mundoestudiante/classfy-teacher-desktop-releases/releases).
2. Abre el archivo `.dmg` y arrastra la aplicación a la carpeta **Aplicaciones**.
3. Abre la aplicación desde **Aplicaciones** (puede que necesites permitir su ejecución en **Preferencias del Sistema > Seguridad y Privacidad**).

### **Linux**

1. Descarga el archivo `.AppImage` o `.deb` desde la última [release](https://github.com/mundoestudiante/classfy-teacher-desktop-releases/releases).

   **Para `.AppImage`:**

   - Haz el archivo ejecutable:
     ```bash
     chmod +x Classfy-Teacher-Desktop-App.AppImage
     ```
   - Ejecuta la aplicación:
     ```bash
     ./Classfy-Teacher-Desktop-App.AppImage
     ```

   **Para `.deb`:**

   - Instala el paquete:
     ```bash
     sudo dpkg -i classfy-teacher-desktop-app.deb
     sudo apt-get install -f  # Para resolver dependencias si es necesario
     ```
   - Encuentra la aplicación en tu lanzador o ejecuta:
     ```bash
     classfy-teacher-desktop-app
     ```

---

## 🔄 Actualizaciones Automáticas

La aplicación incluye un sistema de actualizaciones automáticas. Cuando una nueva versión esté disponible, recibirás una notificación para actualizarla directamente desde la aplicación.
