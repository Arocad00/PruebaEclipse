Creo un nuevo proyecto en eclipse con Botón drch + New project
Luego voy al wrokspace de mi proyecto y creo una carpeta llamada lib donde tengo que meter los jar de la otra práctica que se indica.
Una vez creada la carpeta, me vuelvo a Eclipse, botón drch sobre el proyecto + Refesh para que me aparezca la nueva carpeta que he creado.
Luego, con botón drch + Import, importo los jar previamente descargados, y desde la carpeta descargas (dónde lo tengo guardado) a la carpeta lib.
Lo mismo hago con el fichero  log4j2.xml. Creo una carpeta etc e importo ese fichero siguiendo los mismos pasos que con los jar.
Después tengo que indicarle al proyecto que use las librerias que hemos importado, para ello hago botón drch + Build Path -> Configure Build Path.
Se nos abre una ventana, en la que selecionaremos la pestaña "libreries".
Como importamos antes los jar, le damos a la opción "Add JARs", si no las hubieramos importado daríamos a "Add External JARs".
Damos a esa opción, se nos abre otra ventana donde seleccionaremos nuestro proyecto y todos los jar que queremos añadir.
Después seguimos paso a paso el punto 6: Informar al compilador que tiene que utilizar el fichero de configuración
disponible en etc: Run As> run configurations> pestaña classpath>
Seleccionar User Entries > Advanced > Add folder > seleccionar la
carpeta <etc>

