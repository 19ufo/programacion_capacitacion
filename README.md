# 📅 Calendario Operativo & Disponibilidad Colombia

Aplicación web moderna, ligera y elegante para la gestión y visualización de disponibilidad de equipos, diseñada especialmente para ser desplegada en **GitHub Pages** y compartida mediante enlaces web.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![GitHub Pages Ready](https://img.shields.io/badge/GitHub%20Pages-Ready-brightgreen)

---

## ✨ Características Principales

- 🟢 **Días Habilitados**: Marca jornadas disponibles, operativas o con agenda abierta.
- 🔴 **Días Bloqueados**: Señala cierres, indisponibilidad, descansos o mantenimiento.
- 🟣 **Días de Capacitación**: Programa entrenamientos, cursos, inducciones y talleres (con asignación de tema específico).
- 🇨🇴 **Festivos Oficiales de Colombia**: Motor dinámico con los 18 festivos de ley (Ley Emiliani - Ley 51 de 1983) calculados automáticamente para cualquier año.
- 🔗 **Función "Compartir Calendario" (URL Hash)**: Permite copiar un enlace único que incluye toda tu programación codificada (`#data=...`). ¡Cualquier persona que abra ese link en su navegador verá exactamente tu calendario!
- 💾 **Persistencia Automática**: Los cambios se guardan en el navegador (`localStorage`) para que nunca pierdas tu trabajo.
- 📊 **Exportación a Excel**: Descarga reportes completos con desglose día a día vía SheetJS.
- 📱 **Diseño Responsivo & Moderno**: Tipografía Google Fonts (*Plus Jakarta Sans* & *Inter*), micro-badges luminosos y visualización impecable en móviles, tablets y computadores.

---

## 🚀 Cómo publicarlo en GitHub Pages (en 2 minutos)

Para que cualquier persona en el mundo pueda ver tu calendario en internet gratis:

1. **Crea un repositorio en GitHub**:
   - Entra a [github.com/new](https://github.com/new).
   - Nombra tu repositorio (por ejemplo: `calendario-operativo`).
   - Puedes dejarlo **Público**.

2. **Sube los archivos**:
   - Asegúrate de subir `index.html` en la raíz del repositorio:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Calendario Operativo Colombia"
   git branch -M main
   git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
   git push -u origin main
   ```

3. **Activa GitHub Pages**:
   - En tu repositorio de GitHub, ve a la pestaña **Settings** (Configuración).
   - En el menú izquierdo, haz clic en **Pages**.
   - En la sección **Build and deployment** -> **Branch**:
     - Selecciona la rama `main` (o `master`).
     - Carpeta: `/ (root)`.
     - Haz clic en **Save**.
   - En un minuto, GitHub te dará tu enlace público:  
     `https://TU-USUARIO.github.io/TU-REPOSITORIO/`

---

## 💡 Cómo usar la Aplicación

1. **Navegar en el tiempo**: Usa las flechas `‹` y `›` o los selectores de Mes y Año en la cabecera.
2. **Seleccionar modo de marcado**:
   - Haz clic en una de las pastillas: `🟢 Habilitado`, `🔴 Bloqueado`, `🟣 Capacitación` o `⚪ Borrar`.
3. **Marcar días**:
   - Haz clic sobre cualquier día en la grilla para aplicar el estado activo.
   - Si seleccionas `🟣 Capacitación`, se abrirá un recuadro para escribir el tema del taller o curso.
4. **Compartir**:
   - Presiona el botón negro **🔗 Compartir Calendario**.
   - Se copiará automáticamente el enlace web con todos tus datos al portapapeles. Pégalo en WhatsApp, Slack, Teams o correo.

---

## 📄 Licencia
Este proyecto es de libre uso para gestión de equipos y personal en Colombia.
