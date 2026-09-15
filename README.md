# Actividad 1 - Proyecto de Software - UNLP

Este repositorio contiene la resolución de la "Actividad 1" implementada utilizando dos Inteligencias Artificiales diferentes. El objetivo es comparar las estructuras, diseños y soluciones generadas por cada modelo.

Las dos versiones se encuentran divididas en las siguientes carpetas:
- `Respuesta_Claude_Opus_4.6/`: Resolución generada por Claude Opus 4.6.
- `Respuesta_Gemini_3.1_Pro_High/`: Resolución generada por Gemini 3.1 Pro (High), refinada con altos estándares de accesibilidad (WCAG AA/AAA) e interacción completa por teclado.

Ambas implementaciones comparten los recursos gráficos, los cuales están centralizados en la carpeta `imagenes/`.

## 🚀 Instrucciones para ejecutar el proyecto

Dado que se trata de sitios web estáticos creados puramente con HTML y CSS (sin frameworks pesados ni bases de datos), existen varias formas muy sencillas de levantarlos en tu entorno local.

### Opción 1: Apertura directa (Recomendado para pruebas rápidas)
No necesitas instalar nada, simplemente usa tu explorador de archivos.

1. Clona el repositorio en tu máquina:
   ```bash
   git clone https://github.com/nicoadiaz/Actividad-1---Proyecto-de-Software---UNLP.git
   ```
2. Entra a la carpeta recién clonada:
   ```bash
   cd Actividad-1---Proyecto-de-Software---UNLP
   ```
3. Navega hacia la versión que deseas probar. Por ejemplo:
   ```bash
   cd Respuesta_Gemini_3.1_Pro_High
   ```
4. Abre el archivo `index.html` directamente en tu navegador web de preferencia (haciendo doble clic desde tu explorador de archivos, o arrastrando el archivo hacia el navegador).

---

### Opción 2: Usar un servidor local con Python
Si tienes Python instalado, puedes levantar un servidor web local. Es una excelente práctica para emular un entorno web real.

1. Abre tu terminal.
2. Posiciónate en la carpeta raíz del proyecto:
   ```bash
   cd Actividad-1---Proyecto-de-Software---UNLP
   ```
3. Inicia el servidor web nativo de Python:
   ```bash
   python -m http.server 8000
   ```
   *(Si usas macOS/Linux, el comando podría ser `python3 -m http.server 8000`)*
4. Abre tu navegador y dirígete a: [http://localhost:8000](http://localhost:8000)
5. Desde allí verás el listado de carpetas. Haz clic en `Respuesta_Claude_Opus_4.6` o `Respuesta_Gemini_3.1_Pro_High` para visualizar sus páginas.

---

### Opción 3: Usar Node.js (http-server)
Ideal si estás en el ecosistema de JavaScript y cuentas con npm/npx instalado.

1. Abre tu terminal en la carpeta raíz del proyecto.
2. Levanta el servidor ejecutando:
   ```bash
   npx http-server ./ -p 3000
   ```
3. Abre tu navegador en [http://localhost:3000](http://localhost:3000) y selecciona la carpeta de la versión que quieras testear.

## ♿ Notas de Accesibilidad (Gemini 3.1 Pro High)
La versión dentro de la carpeta `Respuesta_Gemini_3.1_Pro_High` ha sido especialmente acondicionada para cumplir con normativas de accesibilidad:
- Navegación completa por teclado (puedes usar `TAB`, `Shift + TAB` para moverte, y `Enter` o `Espacio` para desplegar las pestañas de imágenes).
- Enlace "Skip to content" oculto, visible al recibir el foco del teclado.
- Semántica HTML mejorada con ARIA roles.
