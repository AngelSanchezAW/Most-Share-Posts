<h1>Most Shared Posts</h1>

Most Shared Posts, es un plugin que nos muestra la popularidad de un artículo (URL), crea un conteo de todos los megusta de facebook que se han generado en esa URL, los Tweet y los Google +. El plugin tiene más de 2 años sin modificar, he cambiado algunas cosas para mejorar la presentación de la información al usuario.

Aqui puedes conseguir el Plugin origianl; http://www.tomanthony.co.uk/wordpress-plugins/most-shared-posts/comment-page-3/

Dentro de tu panel de administración podrás obtener los mejores 100 artículos de tu sitio web, los mejores del mes, los mejores del año y los mejores 10 de la semana. Estos datos se pueden utilizar para realizar análisis del contenido y replicar el tipo de artículos más populares. 

Cuenta con dos opciones para mostrar los datos del lado del cliente, podremos agregar un widget donde tendremos la opción de modificar el número de post a mostrar y el tiempo de antigüedad de los artículos (dias o meses). También podemos agregar un código corto para mostrar los mismos datos donde queramos:

[most-shared-posts num_posts="5" max_month_age="24" title="Most Shared Posts"]

<h2>23/10/2015</h2>
Del archivo msp-widget.php se se han cambiado las siguientes líneas;

.- Línea 71; se agrego una imagen despues del titulo del widget con el fin de darle más contexto a la información mostrada.

.- Línea 216; se agrego la imagen destacada del post, esta parte se modificara en un futuro ya que actualmente muestra la imagen original y con css se cambian las dimensiones, lo mas ideal seria llamara de wordpress una imagen más pequeña para no hacer más pesada la pagina. 

.- Línea 234; se agregó una imagen que se muestra en la parte inferior derecha de cada imagen destacada, la imagen muestra una gráfica ascendente, dando a entender que este artículo está creando tendencia en las redes sociales. 

.- Línea 255; se agregó la variable “$total_tendencia” para sumar el conteo de todos los números de las redes sociales para despues mostrarlo en la línea 260. 

<h4>Nota: En los link´s de los post se agregaron parámetros para obtener informacion de Goolge Analytics, la idea es saber que tantos clic se generan en cada post '?utm_source=interno&utm_medium=widgets&utm_campaign=mps'</h4>

<h2>Este es el resultado obtenido por las modificaciones:</h2>
<center><img src="http://www.azulweb.net/wp-content/uploads/2015/10/MSP.png"></center>
Pedes entrar a <a href="http://www.azulweb.net/">http://www.azulweb.net/</a> y ver el resultado.

<h2>Esta es la parte de administracion:</h2>
<center><img src="http://www.azulweb.net/wp-content/uploads/2015/10/MSP-ADMIN.png"></center>
<h3>El plugin original fue creado por @TomAnthonySEO</h3>
