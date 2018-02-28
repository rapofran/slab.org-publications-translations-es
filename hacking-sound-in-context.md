# Hacking Sound in Context
###### (español traducido por: rapo)


##### Alex McLean
##### alex@state51.co.uk, state51 Rhoda Street, Londres, E2 7EF


Sin software, una computadora es como una piedra. Si consideramos un programa que genera sonidos organizados ¿que podría ser sino una banda sonora compuesta por humanos? Sugiero que, en última instancia, el software no puede ser otra cosa que la expresión humana.

El presente trabajo es una exploración de la relación entre el programador, el entorno de programación y aplicaciones de música para computadoras.



### Significado de "Hack"

> "La gente no técnica parece desconocer en gran medida que la palabra 'técnico' es un insulto. Al igual que el término 'clase baja', se refiere generalmente a otra persona. Lo que 'técnico' generalmente significa es alguien cuyo trabajo es menos creativo que el tuyo".
Ted Nelson, 1974

El término "hacker" no es tan incomprendido como si excesivamente apropiado. Los primeros hackers eran miembros de una cultura tonta (dorky), en particular entusiastas de los trenes modelo y phreakers telefónicos en el MIT (Massachusetts Institute of Technology). Más tarde estos jóvenes geeks encontraron una computadora, e hicieron historia divirtiéndose con ella, pasando muchas horas explorando las posibilidades computacionales. A partir de entonces, la etiqueta "hacker" se utilizó con aquellos que se deleitaban en los nuevos y salvajes dominios de la creatividad tecnológica.

Desafortunadamente los periodistas han ignorado, en general, todos los matices alrededor de la palabra, y en su lugar, la usan para describir a un delincuente informático. Pero aún así, dentro de muchos sectores de la cultura geek, un "hacker" simplemente significa un programador muy talentoso. Ese es el significado que uso, junto con "hacking" en el sentido de programación creativa e individualista, y "hack" en el sentido de un programa creativo (o extraño).



### Sensación de Lenguajes

> "Recomendaría que todos los estudiantes de música salgan a bailar por lo menos una vez a la semana. Y bailen. Por favor, bailen de verdad: tres o cuatro horas a la semana."
Karlheinz Stockhausen, 1989

En su libro "La estética de la Computación" David Gelernter se entusiasma con el algoritmo "quicksort” (ordenación rápida), una manera rápida y elegante de la clasificar datos. Termina su largo y bastante intenso análisis con una línea de lujo, en cursiva:

_"quicksort es poderoso y simple: un hermoso algoritmo."_

Me pregunto cómo se hubiera sentido si hubiera tropezado con el pub "Perl Mongers" en una oscura noche de Londres. La escena, ambientada por programadores ebrios alimentados con cerveza de verdad, tropezando con la idea loca de representar una burbuja de aire humana y sonificada. El personal del bar solo podía pararse y mirar mientras hombres y mujeres crecían en un semicírculo ingobernable, cantando las instrucciones "¡Compare!", "¡Cambie!" o "¡Quédate!" el uno al otro, eligiendo un tono musical que refleje sus alturas comparativas.

Bueno, sería una vista extraña, y un sonido mas extraño aun. Pero quizás no debería sorprender ver a los programadores bailando con algoritmos. Consideremos esta publicación de la lista de correo, parte de una discusión sobre la "sensación" de los lenguajes de computadora.

> "Siempre me he imaginado la programación como una especie de danza, muy lenta y donde cada gesto recibe una gran atención, de modo que un miembro o un paso no se desvían de un camino en particular. Los loops son como piruetas para mí, I/O se siente como gestos delicados con las manos, no, solo las yemas de los dedos dibujan patrones en el aire. Los if y los case son caídas y saltos (en el aire, eso si). La aritmética es una especie de tobogán brumoso y controlado sin tracción (pensemos en movimientos resbaladizos), cosas que se empujan y se descartan".

Un programa en ejecución es un programa en movimiento. El control fluye alrededor del programa, tomando datos de él. Los datos fluyen hacia el programa y vuelven a soplar afuera. Un hacker que mira fijamente a su pantalla probablemente esté dando volteretas en su mente.



### Software Libre

> "La computadoras están generando una situación que es como la invención de la armonía. Las sub-rutinas son como acordes. Nadie pensaría en mantener un acorde para sí mismo. Se lo darías a cualquiera que lo quiera. Le agradecerías que lo alterara. Las sub-rutinas son alteradas por un único golpe. Estamos obteniendo música hecha por el hombre mismo: no sólo un hombre".
John Cage, 1969

Como programador que escribe código para componer música, me sentí alentado al encontrar esta cita. En aquel entonces, Cage vió a los lenguajes de programación como una herramienta expresiva, y estaba entusiasmado con las posibilidades que el código podría aportar a la música. Pero hay una implicación que no estoy de acuerdo: que programar es perder el sentido de la individualidad.

Todos los programadores que conozco tienen un estilo de programación muy diferente. Esto es especialmente cierto en los lenguajes muy expresivos como Perl, donde a menudo los programadores tienen enfoques tan diferentes que serían incapaces de entender el código del otro.

> "Muchos científicos de la computación han caído en la trampa de intentar definir lenguajes como la neolengua de George Orwell, en la que es imposible pensar malos pensamientos. Lo que terminan haciendo es matar la creatividad de programación".
Larry Wall (el creador del lenguaje de programación Perl), 1997

La programación ha cambiado desde 1969. Gracias a la amplia variedad de lenguajes e interfaces, los programadores ahora establecen todas las reglas y toman muchas más decisiones sobre el estilo y la estructura. Escribir código se ha convertido en un pasatiempo individualista.

En un sentido diferente, durante las últimas dos décadas, muchas personas se han guardado sub-rutinas. Si esto es bueno o malo es subjetivo. El acto de liberar el código fuente puede ser muy gratificante en muchos sentidos, pero si el código se escribe para hacer arte, entonces debemos respetar la decisión del artista de mantener sus métodos en secreto. El jurado está muy interesado en si el opensource es bueno para el comercio, pero en lo que respecta al artista individual, la decisión siempre será personal.



### Colaboración Silenciosa

El software de computadora opera en muchos niveles. Miles de personas han hecho el trabajo de su vida con la programación de bajo nivel. Es posible que nunca veamos el código fuente del microcódigo, kernel, controladores de dispositivo o bibliotecas que funcionan continuamente dentro de nuestra computadora, porque no es necesario. Pero estos sistemas y estructuras están ahí, el árbol de procesos que silenciosamente existe ante nosotros es el resultado de muchas decenas de miles de años-hombre.

Un programa de computadora nunca se crea de manera aislada; el programador siempre está en deuda con los colaboradores silenciosos y en ocasiones anónimos. Los creadores de los sistemas operativos y los lenguajes de programación proporcionan el entorno para que se ejecute el trabajo del programador. Usar código de terceros ahorra al programador días, o quizás años de trabajo.

Si ves a un programador como un individuo creativo en lugar de técnico, la computadora deja de ser una caja gris y sin vida, y pasa a ser un entorno formado por la expresión humana. Empezas a ver por qué los programadores se vuelven tan absortos en este medio... En un entorno formado por la expresión humana, las posibilidades son interminables.



### El nacimiento de una lista de correo.

Se inicia una lista de correo para discutir la filosofía de la programación. Las personas afines se encuentran, hacen amigos y comparten pensamientos. La lista de correo crece en tamaño e intensidad. Por alguna razón, algunos miembros entusiastas discuten cómo el archivo de la lista de correo podría convertirse en música. Algún tiempo después, alguien escribe un código para hacerlo.

Los sonidos comienzan con calma y lentamente, con ocasionales ráfagas de actividad. Las líneas de asunto se desplazan lentamente hacia arriba en la pantalla, con los autores parpadeando hacia abajo. A medida que pasa el tiempo, la música aumenta en intensidad, con sonidos más diversos que reflejan la mayor cantidad de subprocesos que se ejecutan al mismo tiempo. Las pausas nocturnas para dormir gradualmente se vuelven menos pronunciadas a medida que los suscriptores cubren partes más amplias del planeta. La música se vuelve maníaca a medida que aumenta el tráfico, hasta que es imposible leer los nombres del autor cuando pasan rápidamente. Y luego, justo cuando el implacable furioso se está volviendo demasiado, todo se detiene. No hay más publicaciones: hemos llegado al día de hoy.

La música se realiza en una fiesta, y el efecto en los miembros de la lista de correo es extremo. Este fragmento de código ha acercado a una comunidad a su historia. El hacker sonríe.



### Audibilidad del Código

Cuando escuchamos música electrónica, a veces podemos identificar el software que se usó para crearla: "escuchamos" el código original del programador. ¿Tal vez esto es evidencia de la fuerza creativa que tiene un programador en cada pieza musical que produce con su propio software?.

Esta "audibilidad del código" es particularmente evidente en lo que se denomina software generativo, como koan pro. La naturaleza basada en el proceso de composición pone un gran control en manos de los programadores originales. Entonces, usar koan podría verse como un dúo con los creadores del programa.



### Flor

> "Cuando empecé a trabajar con computadoras, tuve que aprender a visualizar lo que sucedía en ellas... Los curadores y críticos que observan el net art tienen que pasar por este proceso también, pero pueden no darse cuenta."
Mark Napier, 2000

Cuando creo un programa, es casi de la misma manera que podría crear una pieza de música en un secuenciador. Tengo una idea abstracta, me concentro en la parte más tangible y la traduzco en la computadora como código. Luego, formo más partes a su alrededor hasta que parezca un todo coherente. Algunas partes pueden eliminarse, pero han dejado marcas en las partes que se formaron a su alrededor.

Después de escuchar "Speedy J" tocar un poco de techno, me encontré pensando en el movimiento dentro de la música. Pensando en abstracto, imaginé una red de loops, con cosas alrededor que se movían haciendo sonidos. Después de unas horas, descubrí lo que ahora llamo insectos moviéndose alrededor de una flor, con varios disparadores de sonido en cada pétalo. Esta fue una descripción arbitraria ya que no tenía visualización o, de hecho, ninguna interfaz más allá de tres entradas: intensidad, complejidad y desorden.

Comienza con un círculo. Aumenta la intensidad y los insectos comienzan a moverse a su alrededor, disminuye y mueren uno por uno. Aumenta la complejidad y los pétalos se agregan a la flor en posiciones aleatorias, disminuye y se despluman. Los insectos pueden elegir viajar alrededor de los pétalos también. Cada pétalo tiene ciertos sonidos que los insectos tocan al pasar. Si la independencia está activada, los insectos se ignoran mutuamente, de lo contrario, interactúan. Aumenta el desorden y eligen qué pétalos visitar de forma más aleatoria, si disminuye caen en ritmo.

Luego inicio otra flor, o dos con diferentes bancos de samples, y se sincronizan a través de un servidor central, haciendo buenos contrapuntos de tiempo.

Solo tenía una vaga idea sobre cómo sonaría el programa, pero quedé atónito por los resultados: la música es aleatoria al principio. Pero con una intensidad de 3 y una complejidad de 9 aproximadamente, la música se establece gradualmente en una hermosa polirritmia.



### Descansar

Un programa informático bien escrito es el lugar de descanso perfecto para su autor. Los programas se originan en la imaginación humana, por lo que los programadores conocen sus creaciones extremadamente bien. La primera ejecución de un programa es, por lo tanto, un tiempo precioso. La imaginación del programador está integrada en algo intangible, pero con la presencia obtenida de la intemporalidad. Los pensamientos se solidifican en código y se vuelven fluidos una vez más en ejecución.

Pero un programa nunca es completo, siempre hay más ideas para eternizar, más algoritmos para perfeccionar y más datos para acomodarse.



### Bibliografía y lecturas recomendadas
* Music and the Mind, Storr, Harper Collins, 1992
* The Sound of Painting, Maur, 1999
* John Cage, Writer - Selected Texts, Ed. Kostelanetz, MIT Press, 1993
* The Computational Beauty of Nature, Flake, 1998
* http://mitpress.mit.edu/books/FLAOH/cbnhtml/
* Ocean of Sound, Toop, Serpents Tail, 1995
* How I drew one of my pictures, Ward, 1999
* http://www.generative.net/papers/autoshop/index.html
* Computer Lib/Dream Machines, Ted Nelson, 1974
* http://xanadu.com.au/ted/
* The New Hacker's Dictionary - second edition, Ed. Raymond, MIT Press, 1994
* http://tuxedo.org/jargon/
* Talking Music: Conversations with John Cage, Philip Glass, Laurie Anderson, and Five Generations of American Experimental Composers, Duckworth, Schirmer Press, 1995
* Aesthetics of Programming: Interview with Mark Napier, Brogger, "ON OFF", 2000
* http://www.afsnitp.dk/onoff/Projects/napierinterview.html
