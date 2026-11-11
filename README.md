# Conversor de texto a voz y voz a texto

Proyecto de práctica hecho con React y Vite. Es una aplicación web con dos
herramientas: leer en voz alta un texto escrito y transcribir lo que se dice
por el micrófono.

## Funcionalidades
- **Texto a voz:** escribes un texto, tocas *Convertir* y el navegador lo lee
  en voz alta con la API `speechSynthesis` (Web Speech API).
- **Voz a texto:** botón *Grabar* para transcribir la voz. Esta parte está
  en desarrollo y todavía no funciona de forma estable.
- **Inicio de sesión de prueba:** pantalla de acceso con validación simulada.

## Tecnologías
React, Vite, JavaScript, Pico.css, Web Speech API (`speechSynthesis`)

## Cómo ejecutarlo
1. Instala Node.js (https://nodejs.org) (versión LTS).
2. Clona o descarga este repositorio.
3. En la carpeta del proyecto, ejecuta:

   ```bash
   npm install
   npm run dev
   ```

4. Abre en el navegador el enlace que muestra la terminal
   (normalmente `http://localhost:5173/`).

## Acceso de prueba
- Usuario: `admin`
- Clave: `admin`

La validación está escrita en el código y no hay base de datos ni seguridad
real. Es solo una demostración.

## Compatibilidad
La función de voz depende del navegador. Se recomienda usar Chrome o Edge.
El reconocimiento de voz requiere permitir el acceso al micrófono.

## Estado
Proyecto de práctica. El texto a voz funciona; el reconocimiento de voz
está pendiente de corregir.

## Autora
Geraldine Perea
