# Configuración Vscode 

Hola, te comparto mi configuración y las extensiones básicas que uso para desarrollo frontend en [Visual Studio Code](https://code.visualstudio.com/).

Como desarrollador, he estado utilizando [Visual Studio Code](https://code.visualstudio.com/) (VS Code) como mi editor de código de elección durante mucho tiempo. Durante este tiempo, he descubierto varias formas de personalizar mi entorno de trabajo para aumentar mi productividad y mejorar mi flujo de trabajo.





## Mi configuración personalizada de VS Code <img src="https://media.giphy.com/media/IdyAQJVN2kVPNUrojM/giphy.gif" alt="Texto alternativo de la imagen" width="20">

```Json
{
  // Establece el nivel de zoom predeterminado de la ventana.
  "window.zoomLevel": 2,
  // Habilita el ajuste de línea automático en el editor.
  "editor.wordWrap": "on",
  // Guarda automáticamente los archivos al cambiar el foco del editor.
  "files.autoSave": "onFocusChange",
  // No restaura automáticamente las ventanas abiertas al reiniciar el editor.
  "window.restoreWindows": "none",
  // Abre automáticamente archivos no confiables en un entorno seguro.
  "security.workspace.trust.untrustedFiles": "open",
   // Oculta las pestañas de los editores para maximizar el espacio de trabajo.
  "workbench.editor.showTabs": false,
   // Deshabilita la minimap que muestra una vista previa del archivo completo.
  "editor.minimap.enabled": false,
   // Deshabilita la detección automática de la sangría.
  "editor.detectIndentation": false,
  // Establece el tamaño de tabulación predeterminado del editor en 2 espacios.
  "editor.tabSize": 2,
  // Oculta la barra de desplazamiento vertical del editor.
  "editor.scrollbar.vertical": "hidden",
  // Oculta el borde de la regla de vista previa en el lateral derecho del editor.
  "editor.overviewRulerBorder": false,
  // Oculta el cursor en la regla de vista previa del editor.
  "editor.hideCursorInOverviewRuler": true,
  // Deshabilita las líneas guía de sangría en el editor.
  "editor.guides.indentation": false,
  // Establece el ancho del indicador de sangría en el editor.
  "indenticator.width": 0.5,
  // Establece el color del indicador de sangría en el editor.
  "indenticator.color.dark": "rgba(255,255,255,0.5)",
  // Oculta la ubicación actual del archivo en el encabezado del editor.
  "breadcrumbs.enabled": false,
  // Oculta el margen de glifo en el editor (donde se muestran los números de línea).
  "editor.glyphMargin": false,
   // Oculta la barra de estado en la parte inferior de la ventana.
  "workbench.statusBar.visible": false,
   // Oculta la barra de actividad en la parte izquierda de la ventana.
  "workbench.activityBar.visible": false,
  // Habilita la coloración de los pares de corchetes.
  "editor.bracketPairColorization.enabled": true,    // Habilita la coloración de los pares de corchetes.
   // Muestra las líneas guía para los pares de corchetes.
  "editor.guides.bracketPairs": true,
  // Muestra todos los espacios en blanco en el editor (incluso los espacios en blanco).
  "editor.renderWhitespace": "all",
  // Establece el terminal predeterminado en el editor como Git Bash.
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  // Habilita la expansión de Emmet en el lenguaje JavaScript.
  "emmet.includeLanguages": {
    "javascript": "html"
  },
  // Omite la verificación de etiquetas al usar Live Server en HTML.
  "liveServer.settings.donotVerifyTags": true,
  // Establece el formateador de código predeterminado para Prettier
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  // Habilita el formateo automático del código cuando se pega algo en el editor
  "editor.formatOnPaste": true,
  // Habilita el formateo automático del código cuando se guarda el archivo
  "editor.formatOnSave": true,
  // Habilita el formateo automático del código mientras se escribe
  "editor.formatOnType": true,
  // Cambia la ubicación de la barra lateral del editor a la derecha
  "workbench.sideBar.location": "right",
  // Establece el tema de iconos predeterminado para el editor
  "workbench.iconTheme": "material-icon-theme",
  // Habilita el centro de comandos en la ventana del editor
  "window.commandCenter": true,
  // Establece el tema de color predeterminado para el editor
  "workbench.colorTheme": "Outrun Electric",
  // Habilita la función experimental de importaciones automáticas para la extensión de Tabnine
  "tabnine.experimentalAutoImports": true,
  // Proporciona una configuración vacía para personalizar los colores del editor
  "workbench.colorCustomizations": {},
  // Establece el color de los comentarios en verde brillante
  "editor.tokenColorCustomizations": {
    "comments": "#00ff00"
  },
  // Deshabilita la confirmación de eliminación de archivos/directorios en el explorador de archivos del editor
  "explorer.confirmDelete": false,
  // Deshabilita la función de resaltado de coincidencia de paréntesis y corchetes en el editor
  "editor.matchBrackets": "never"
}
```
### Para copiar la configuración en el archivo settings.json de tu VSCode, sólo debes:

1. Ir al Menú File (Archivo).
2. Luego a Preferences (Preferencias).
3. Selecciona Settings (Configuraciones).
4. Sólo da clic en el botón Open Settings (JSON) que está en la esquina superior derecha.
5. Listo, copía la configuración que te sirva.

<br>

![Configuración](https://user-images.githubusercontent.com/131729985/235440277-f6e131ec-c7bb-4573-a794-f8e17c5db7f5.png)

## Extensiones

### Extensiones básicas para Visual Studio Code:

1. [Spanish Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-es): para usar la interfaz de VS Code en español.

2. [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer): levanta un servidor local de desarrollo con función de recarga en vivo para páginas estáticas y dinámicas desde Visual Studio Code.

3. [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode): formatea mi código frontend (HTML, CSS y JavaScript).

4. [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint): para integrar ESLint a Visual Studio Code.

[_Emilio Rodriguez_](https://github.com/Devemiliorb)
