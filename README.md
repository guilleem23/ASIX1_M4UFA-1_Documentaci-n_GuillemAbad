# ASIX1_M4UFA-1_Documentaci-n_GuillemAbad
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Documentación (Guillem Abad ASIX1)</title>
</head>
<body>
 <center><h1><u><strong>DOCUMENTACIÓN APUNTES:</strong></u></h1> <align=”middle”>    </center>
<H2>GIT HUB:</H2>
Primero de todo, para poder empezar a trabajar con GitHub y Visual Code tenemos que tener creada en internet una cuenta de GitHub. Seguidamente, vamos a nuestro perfil y le damos a crear un repositorio nuevo. En este, lo ponemos en público o privado dependiendo si queremos que lo vea la gente de internet o solamente la gente que nosotros queramos y <strong>MUY IMPORTANTE</strong> darle a "add a read me file" ya que ahí es donde puede escribir una descripción larga del proyecto que vamos a crear.
<br>
<br>
Una vez creado el repositorio, como nosotros queremos trabajar en local (es decir desde nuestro pc y no directamente desde GitHub), tendremos que hacer una copia para subirla a nuestro local. Para hacerlo, vamos a seguir los siguientes pasos:
<br>

<li>Abrimos el CMD</li>
<li>Escribimos "cd" y le damos a enter</li>
<li>Escribimos "cd" y en donde quieres que se quede guardado y le damos a enter. Ejemplo: cd C:\repositorios GIT</li>
<li>Una vez hecho esto, escribimos "git clone" y el link de la página anteriormente creada de nuestro repositorio de GitHub (para encontrarlo, vamos a nuestro repositorio de GitHub, pulsamos en code y copiamos la URL que sale) y le damos a enter. Ejemplo: git clone https://github.com/guilleem23/-ejemplo123.git</li>
<br>
Después de haber seguido estos pasos, ya podremos seleccionar desde local la carpeta del local donde está ubicado nuestro repositorio. 
<br>
Una vez hecho esto, abriremos la carpeta y crearemos dos cosas.
<li>1. Una carpeta llamada img donde guardaremos todas las imágenes que necesitaremos posteriormente</li>
<li>2. Un archivo llamado index.html para así ir viendo el trabajo que estamos realizando. Este posteriormente será nuestro resultado final de nuestra página web.</li>
<br>
<br>
Después de haber acabado ya todo lo que necesitamos para crear la página con todo lo necesario, para subir desde local al GitHub nuestra carpeta del repositorio tendremos que hacer lo siguiente:
<li>1o tendremos que abrir CMD</li>
<li>2o escribimos cd y le damos a enter</li>
<li>3o escribimos cd y la ubicación del nuestra carpeta del repositorio. Ejemplo: cd C:\repositorios GIT\ASIX1_M4UF1A4_primer_HTML_GuillemAbad</li>
<li>4o escribimos "git init" y le damos a enter</li>
<li>5o escribimos "git add" y le damos a enter</li>
<li>6o escribimos 'git commit -m "(el cambio que le queremos dar)'. Ejemplo: git commit -m "cambio del error del HTML" </li>
<LI>7o escribimos "git push origin main" para acabar ya y le damos a enter</LI>
<br>
Una vez hecho esto, iremos a nuestro repositorio de GitHub en la nube y veremos que nos salen 3 cosas, el index.html creado, la read me file creada al principio y la carpeta img donde hemos guardado todas las imágenes necesarias para hacer este proyecto.
<br> Para ver el resultado final de la página y poderlo compartir, nos iremos a "settings" del repositorio, "pages", y desplegamos donde pone "none" con el título de "branch" y seleccionamos "main". A continuación nos esperamos y vamos recargando hasta que salga ya nuestra página web HTML. 
<br> Finalmente, ya tendremos el link de nuestra página web y para poder compartirla solamente tendremos que darle este link a quién queramos para hacerlo ya público. En mi caso, como también quiero que mi profesor vea lo demás, es decir, a parte del archivo index.html, que vea también la carpeta llamada img y el archivo read me file, nos vamos a code y copiamos al portapapeles lo que nos sale en HTTPS y ya estaría.
<br>
<H2>MARKDOWN:</H2>
<h4>Etiquetas básicas de Markdown:</h4>
<li>Para hacer los encabezados, estos ya vienen asociados ya un estilo por defecto a cada uno. Sería de la siguiente forma:
    <br># H1
    <br>## H2
    <br>### H3
    <br>#### H4
    <br>##### H5
    <br>###### H6</li>
    <br>
<li>Estilos de letra:

    <br>Itálica o cursiva: *texto* o _texto_
    <br>Negrita: **texto** o __texto__
    <br>: ~~palabra~~ (ALT+126)
   <br> Anidar estilos: **palabra1  _palabra2_** (itálicas pero la segunda además negrita)
    </li>
    <br>
 <li>Listas:
  <strong>ORDENADAS</strong> 
  <BR>  1. Primer elemento de lista
   <br> 2. Segundo elemento de lista
      <br>  (El número de orden no ha de ser necesariamente consecutivo)
    <br>Tabulación→ 1. Elemento de sublista ordenado
    
   <strong>DESORDENADAS</strong>
   <br> *  Elemento de lista desordenada
   <br> -  Otro elemento de lista desordenada
    <br>+ Otro elemento de lista desordenada
   <br>     (Se puede elegir cualquiera de los tres símbolos para crear una lista desordenada)
    <br>Tabulación→ * Elemento de sublista desordenado</li>   
  <br>  <li><strong>Párrafos</strong>
    <br>Para crear un bloque de texto nuevo (etiqueta), se introduce una línea en blanco.
    </li>
    <br>
    <li><strong>Código</strong>
    <br>El código se ha de incluir entre acentos graves (`). Si en el código aparece un acento grave, se ha de introducir el carácter dos veces al principio de la sección del código.

    <br>``Todo esto es `código`.``
    
    <br>También se puede marcar el área correspondiente al código insertando tres acentos graves al principio y al final. Junto a los tres iniciales se puede indicar el lenguaje (HTML, JavaScript) para que incluso se muestre con los colores adecuados:
    
    <br>```html
    <br><'html'>
     <br> <'head'>
     <br> <'/head'>
    <br><'/html'>
  <br><li><strong>Enlaces</strong>
<br>[Link](https://ejemplo.com/ "Título opcional del enlace")

<br>a) Primero se incluye el texto del link entre corchetes y posteriormente el link entre paréntesis).    
<br>b) El “título opcional del enlace” es el texto alternativo al pasar el ratón por encima.

<br><li><strong>Imágenes</strong>
<br> Inline-style: 
<br>![alt text](https://github.com/img/icon48.png "Título opcional de la imagen")

<br>Reference-style: 
<br>![alt text][logo]
<br>[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

</li>
<br><li><strong>Tablas</strong>
<br> | Tables        | Are           | Cool  |
<br>| ------------- |:-------------:| -----:|
<br>| col 3 is      | right-aligned | $1600 |
<br>| col 2 is      | centered      |   $12 |
<br>| zebra stripes | are neat      |    $1 |

<br>Los dos puntos se usan para alinear las columnas (izquierda, centrado, derecha).
<br>No es necesario que estén alineadas verticalmente. Solo a nivel visual para claridad del código.
<br>Se han de poner al menos tres guiones para separar cada encabezado
<br>
<li><strong>Notas al pie de página</strong>

 <br>   Texto con enlace a nota de pie de página [^1]
    
  <br>  [^1]: Aquí encuentras el texto de la nota al pie de página.
    
<li><strong>Listas de verificación</strong>
<br>- [ ] A
<br>- [x] B
<br>- [ ] C
 <br> (Dejar un espacio en blanco entre los dos corchetes en las que aparezcan vacías)



</li>

<h2>HTML:</h2>
Visual Studio Code, se utiliza y/o lo hemos utilizado con HTML. Para empezar a trabajar con este de manera fácil, tendremos que escribir "html:5" y nos desplegará un texto para poder empezar a darle forma a nuestro proyecto. 
Por ejemplo, podemos ponerle título a este, donde pone <"title">. A continuación, hay unas cosas básicas que debes de saber:
<br><li>El <'br'> sirve para dejar un espació. Aunque nosotros le demos a enter desde el Visual Studio Code, si no escribimos <"'br'> sin las comillas no dejará un espacio.
 </li>
<li>El <'li'>Sirve para hacer una lista mediante puntos como estás viendo ahora mismo leyendo estos puntos.</li>
<li>Los H1,H2,H3,H4,H5... sirven para hacer títulos, el número más pequeño (1) para títulos más grandes y a medida que incrementas el número se van haciendo más pequeños</li>
<li>Cuando nosotros utilizamos la 'hr', esta se utiliza para hacer una línea/barra horizontal que ocupa toda la línea de página. 
    <HR>ESTO ES UN EJEMPLO<HR>
  <LI>Y lo siguiente sirve para poder darle un destino a un texto. Ejemplo:  <'a href=”destinodeltexto”>texto a escribir <'/a></LI>  

</li>
<li>Para introducir una imagen, tendremos que escribir lo siguiente:<'img src="/ubicacióndelaimagen"'> </li>
<li>Para hacer listas mediante números, tendremos que utilizar la herramiente <'ol'> y la herramienta anteriormente utilizada <'li'></li>
<h2>FONT AWESOME</h2>
<li>Para nosotros poder poner distintos iconos y demás en nuestra página HTML, utilizamos la siguiente web: <a href="https://fontawesome.com/"> Font Awesome.</a></li>
<li>Entramos y nos registramos y seguimos los siguientes pasos:</li>
<ol><li>Después de registrarnos, nos vamos donde pone "icons" y buscamos el icono que más nos guste. Si no queréis pagar, darle a filtrar por "free" para seleccionar los iconos gratuitos. Una vez seleccionado el icono, copiamos al portapapeles lo que pone donde lo de HTML.</li>
<li>Seguidamente, dentro de nuestro visual studio, introducimos lo anteriormente copiado exactamente donde queramos que se vea. (tiene que ser donde tú quieras pero donde pone "body" y no "head"</li>
<li>Finalmente, para que se vea, vamos a nuestro perfil, le damos a "kits" y si tenemos un kit lo copiamos al portapapeles toda la url y sino, creamos un kit y hacemos el paso anterior.</li>
<li>Entonces, lo anteriormente copiado al portapapeles, el cuál es el kit code de nuestro proyecto, lo pegamos en el Visual Studio pero <strong>DONDE PONE <'head'></strong>, si no no funcionará. El script este que hemos utilizado siempre es el mismo, por lo cual siempre lo podremos utilizar en nuestros futuros proyectos.</li></ol>








</body>

</html>