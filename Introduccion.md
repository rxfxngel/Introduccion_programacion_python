# Modulo 1 Introduccion
## ¿Cómo funciona un programa de computadora?
Este curso tiene como objetivo mostrarle qué es el lenguaje Python y para qué se utiliza. Comencemos desde lo básico absoluto.
Un programa hace que una computadora sea utilizable. Sin un programa, una computadora, incluso la más poderosa, no es más que un objeto. Del mismo modo, sin un pianista, un piano no es más que una caja de madera.
Las computadoras pueden realizar tareas muy complejas, pero esta habilidad no es innata. La naturaleza de una computadora es bastante diferente.

## Lenguajes naturales frente a lenguajes de programación
Un lenguaje es un medio (y una herramienta) para expresar y registrar pensamientos. Hay muchos idiomas a nuestro alrededor. Algunos de ellos no requieren hablar ni escribir, como el lenguaje corporal; es posible expresar sus sentimientos más profundos con mucha precisión sin decir una palabra.

Otro idioma que utilizas a diario es tu lengua materna, que utilizas para manifestar tu voluntad y pensar en la realidad. Las computadoras también tienen su propio lenguaje, llamado lenguaje de máquina, que es muy rudimentario.

Una computadora, incluso la más sofisticada técnicamente, carece incluso de un rastro de inteligencia. Se podría decir que es como un perro bien adiestrado: responde solo a un conjunto predeterminado de comandos conocidos.

Los comandos que reconoce son muy simples. Podemos imaginar que la computadora responde a órdenes como "tomar ese número, dividir por otro y guardar el resultado".

Un conjunto completo de comandos conocidos se denomina lista de instrucciones, a veces abreviado como IL. Los diferentes tipos de computadoras pueden variar según el tamaño de sus IL, y las instrucciones pueden ser completamente diferentes en diferentes modelos.

Nota: los lenguajes de máquina son desarrollados por humanos.


Actualmente, ninguna computadora es capaz de crear un nuevo idioma. Sin embargo, eso puede cambiar pronto. Por otro lado, la gente también usa varios lenguajes muy diferentes, pero estos lenguajes se desarrollaron de forma natural. Además, todavía están evolucionando.

Cada día se crean nuevas palabras y las viejas desaparecen. Estos lenguajes se denominan lenguajes naturales. 

## ¿Qué hace un lenguaje?
Podemos decir que cada lenguaje (automático o natural, no importa) consta de los siguientes elementos:

UN ALFABETO
un conjunto de símbolos que se utilizan para construir palabras de un determinado idioma (por ejemplo, el alfabeto latino para el inglés, el alfabeto cirílico para el ruso, el kanji para el japonés, etc.)

UNA LEXIS
(también conocido como diccionario) un conjunto de palabras que el idioma ofrece a sus usuarios (p. ej., la palabra "computadora" proviene del diccionario de inglés, mientras que "cmoptrue" no; la palabra "chat" está presente tanto en los diccionarios de inglés como de francés , pero sus significados son diferentes)

UNA SINTAXIS
un conjunto de reglas (formales o informales, escritas o intuitivas) que se utilizan para determinar si una determinada cadena de palabras forma una oración válida (por ejemplo, "Soy una pitón" es una frase sintácticamente correcta, mientras que "Soy una pitón" no es 't)

SEMÁNTICA
un conjunto de reglas que determinan si una determinada frase tiene sentido (p. ej., "Me comí una rosquilla" tiene sentido, pero "Una rosquilla me comió" no)

El IL es, de hecho, el alfabeto de un lenguaje de máquina. Este es el conjunto de símbolos más simple y primario que podemos usar para dar comandos a una computadora. Es la lengua materna de la computadora.


Desafortunadamente, esta lengua está muy lejos de la lengua materna humana. Todos (tanto los ordenadores como los humanos) necesitamos algo más, un lenguaje común para los ordenadores y los humanos, o un puente entre los dos mundos diferentes.

Necesitamos un lenguaje en el que los humanos puedan escribir sus programas y un lenguaje que las computadoras puedan usar para ejecutar los programas, uno que sea mucho más complejo que el lenguaje de máquina y, sin embargo, mucho más simple que el lenguaje natural.

Estos lenguajes a menudo se denominan lenguajes de programación de alto nivel. Son al menos algo similares a los naturales en que utilizan símbolos, palabras y convenciones legibles para los humanos. Estos lenguajes permiten a los humanos expresar comandos a computadoras que son mucho más complejos que los que ofrecen los IL.

Un programa escrito en un lenguaje de programación de alto nivel se llama código fuente (en contraste con el código de máquina ejecutado por computadoras). De manera similar, el archivo que contiene el código fuente se denomina archivo fuente. 

## Compilación versus interpretación
La programación de computadoras es el acto de componer los elementos del lenguaje de programación seleccionado en el orden que causará el efecto deseado. El efecto puede ser diferente en cada caso específico, depende de la imaginación, el conocimiento y la experiencia del programador.

Por supuesto, tal composición tiene que ser correcta en muchos sentidos:

alfabéticamente: un programa debe estar escrito en una escritura reconocible, como romano, cirílico, etc.
léxicamente: cada lenguaje de programación tiene su diccionario y es necesario dominarlo; afortunadamente, es mucho más simple y más pequeño que el diccionario de cualquier lenguaje natural;
sintácticamente - cada idioma tiene sus reglas y deben ser obedecidas;
semánticamente, el programa debe tener sentido.
Desafortunadamente, un programador también puede cometer errores con cada uno de los cuatro sentidos anteriores. Cada uno de ellos puede hacer que el programa se vuelva completamente inútil.

Supongamos que ha escrito correctamente un programa. ¿Cómo podemos persuadir a la computadora para que lo ejecute? Tienes que convertir tu programa en lenguaje de máquina. Afortunadamente, la traducción puede ser realizada por una computadora, lo que hace que todo el proceso sea rápido y eficiente.


Hay dos formas diferentes de transformar un programa de un lenguaje de programación de alto nivel a un lenguaje máquina:

COMPILACIÓN: el programa fuente se traduce una vez (sin embargo, este acto debe repetirse cada vez que modifica el código fuente) obteniendo un archivo (por ejemplo, un archivo .exe si el código está destinado a ejecutarse en MS Windows) que contiene la máquina código; ahora puede distribuir el archivo en todo el mundo; el programa que realiza esta traducción se llama compilador o traductor;

INTERPRETACIÓN: usted (o cualquier usuario del código) puede traducir el programa fuente cada vez que deba ejecutarse; el programa que realiza este tipo de transformación se denomina intérprete, ya que interpreta el código cada vez que se pretende ejecutarlo; también significa que no puede distribuir el código fuente tal como está, porque el usuario final también necesita el intérprete para ejecutarlo.

Debido a algunas razones muy fundamentales, un lenguaje de programación de alto nivel en particular está diseñado para caer en una de estas dos categorías.

Hay muy pocos lenguajes que se puedan compilar e interpretar. Por lo general, un lenguaje de programación se proyecta con este factor en la mente de sus constructores: ¿será compilado o interpretado?

## ¿Qué hace realmente el intérprete?
Supongamos una vez más que ha escrito un programa. Ahora, existe como un archivo de computadora: un programa de computadora es en realidad un fragmento de texto, por lo que el código fuente generalmente se coloca en archivos de texto. Nota: tiene que ser texto puro, sin decoraciones como diferentes fuentes, colores, imágenes incrustadas u otros medios. Ahora tienes que invocar al intérprete y dejar que lea tu archivo fuente.

El intérprete lee el código fuente de una manera común en la cultura occidental: de arriba a abajo y de izquierda a derecha. Hay algunas excepciones; se tratarán más adelante en el curso.

En primer lugar, el intérprete verifica si todas las líneas siguientes son correctas (utilizando los cuatro aspectos cubiertos anteriormente).

Si el compilador encuentra un error, termina su trabajo inmediatamente. El único resultado en este caso es un mensaje de error. El intérprete le informará dónde se encuentra el error y qué lo causó. Sin embargo, estos mensajes pueden ser engañosos, ya que el intérprete no puede seguir sus intenciones exactas y puede detectar errores a cierta distancia de sus causas reales.

Por ejemplo, si intenta usar una entidad de nombre desconocido, causará un error, pero el error se descubrirá en el lugar donde intenta usar la entidad, no donde se introdujo el nombre de la nueva entidad.

En otras palabras, el motivo real generalmente se ubica un poco antes en el código, por ejemplo, en el lugar donde tuvo que informar al intérprete que iba a usar la entidad del nombre.



Si la línea se ve bien, el intérprete intenta ejecutarla (nota: cada línea generalmente se ejecuta por separado, por lo que el trío "lectura-verificación-ejecución" puede repetirse muchas veces, más veces que el número real de líneas en el archivo fuente , ya que algunas partes del código pueden ejecutarse más de una vez).

También es posible que una parte significativa del código se ejecute correctamente antes de que el intérprete encuentre un error. Este es un comportamiento normal en este modelo de ejecución.

Puede preguntar ahora: ¿cuál es mejor? ¿El modelo de "compilación" o el modelo de "interpretación"? No hay una respuesta obvia. Si lo hubiera existido, uno de estos modelos habría dejado de existir hace mucho tiempo. Ambos tienen sus ventajas y sus desventajas. 

## ¿Qué es Python?
Python es un lenguaje de programación de alto nivel, interpretado, orientado a objetos y ampliamente utilizado con semántica dinámica, utilizado para programación de propósito general.

Y si bien es posible que conozca a la pitón como una serpiente grande, el nombre del lenguaje de programación Python proviene de una antigua serie de sketches de comedia de televisión de la BBC llamada Monty Python's Flying Circus.

En el apogeo de su éxito, el equipo de Monty Python estaba realizando sus bocetos para audiencias en vivo en todo el mundo, incluso en el Hollywood Bowl.

Dado que Monty Python se considera uno de los dos nutrientes fundamentales para un programador (el otro es la pizza), el creador de Python nombró el lenguaje en honor al programa de televisión.

## ¿Quién creó Python?
Una de las características sorprendentes de Python es el hecho de que en realidad es el trabajo de una sola persona. Por lo general, los nuevos lenguajes de programación son desarrollados y publicados por grandes empresas que emplean a muchos profesionales y, debido a las reglas de derechos de autor, es muy difícil nombrar a las personas involucradas en el proyecto. Python es una excepción.

No hay muchos idiomas cuyos autores se conozcan por su nombre. Python fue creado por Guido van Rossum, nacido en 1956 en Haarlem, Países Bajos. Por supuesto, Guido van Rossum no desarrolló ni evolucionó todos los componentes de Python él mismo.

La velocidad con la que Python se ha extendido por el mundo es el resultado del trabajo continuo de miles (muy a menudo anónimos) programadores, probadores, usuarios (muchos de ellos no son especialistas en TI) y entusiastas, pero hay que decir que el mismo La primera idea (la semilla de la que brotó Python) vino a una cabeza: la de Guido. 
