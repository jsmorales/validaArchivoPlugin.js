# validaArchivoPlugin.js
Plugin que valida los tipos de archivo y tamaño antes de subir al servidor para jsFramework.

<h2>Atributos</h2>

<b>nombre del tipo file</b> = Nombre del control de tipo "File", que es el que carga los binarios.

<b>nombre del modulo</b> = Nombre del modulo en singular que se carga para todos los controles.

<b>nombre del text</b> = Nombre del control de tipo text donde deja el nombre del archivo para insertarlo en la BD.

<h2>Set del Plugin</h2>

$("selector").validaArchivo('nombre del tipo file','nombre del modulo','nombre del text');
