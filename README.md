# Transforma tu Windows Terminal
Esta es una pequeña guía para configurar Powershell a mi gusto y tener una terminal en Windows (10 o 11) casi tan bonita como una
terminal de Linux.

<p align="center"><img width="auto" height="auto" src="/img/before.png" alt="After Terminal Result"></p>

## Paso 1: Instalar Windows Terminal
Actualmente Windows ha mejorado mucho su terminal propia, siendo que ahora el antiguo **Símbolo del Sistema** o **CMD**, ha sido casi sustituido tanto por **Windows Terminal** como por **Powershell**, uno para el gestor de terminal y el otro como Shell. Instalar Windwos Terminal es tan sencillo como abrir la **Microsoft Store** y buscar Terminal e instalar el siguiente:

<p align="center"><img width="auto" height="auto" src="/img/winTerminal.png" alt="Store Windows Terminal Search"></p>

## Paso 2: Instalar Powershell 7
Las versiones recientes de Windows 10 y Windows 11, ya traen por instaladas por defecto una versión de Powershell, sin embargo es recomendable instalar la última versión (Powershell 7), para ello solo debes abrir Windows Terminal, asegurándote de que se abra el perfil de **Powershell** y ejecutar lo siguiente:    


```powershell
#Esto para instalar Powershell 7 estable
winget install --id Microsoft.Powershell --source winget
```    


Si quieres instalar la versión preliminar o beta (Powershell Preview), ejecuta el siguiente comando en lugar del anterior: 


```powershell
#Esto para instalar Powershell 7 preview o beta
winget install --id Microsoft.Powershell.Preview --source winget
```   
> **NOTA**: Si en la terminal te aparece un mensaje para preguntar sí estas de acuerdo con instalar los paquetes solicitados, solo escribe "Y" (yes) o "A" (todo), y luego pulsa **enter**


<p align="center"><img width="auto" height="auto" src="/img/posh7-install.png" alt="Installing POSH 7"></p>  


## Paso 3: Instalar una fuente que soporte íconos
Nuestra terminal debe tener soporte para ícono dentro de la misma, para ello es necesario instalar una fuente que pueda soportarlo, siempre me he decantado por usar [NerdFonts]: https://www.nerdfonts.com/font-downloads para instalar mis fuentes en mis diferentes sistemas como Linux o Windows, para este caso yo recomiendo mucho descargar **Hack Nerd Font**, ya que se ve muy bien en la terminal y soporta una gran variedad de íconos:  


<p align="center"><img width="auto" height="auto" src="/img/nerdfont.png" alt="Installing Hack Nerd Font"></p>  

Una vez descargada solo hay que abrirla en el **explorador de archivos** de Windows y descomprimir la carpeta **.zip** que se descargo:

<p align="center"><img width="auto" height="auto" src="/img/descomprimir.zip" alt="Uncompressing Hack.zip"></p>  

Una vez descomprimida solo hay que instalar todos los archivos **.ttf** evitando seleccionar los archivos **README.md** y **License**:  

<p align="center"><img width="auto" height="auto" src="/img/install-fonts.png" alt="Installing all fonts"></p>  

