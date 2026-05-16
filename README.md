# UP2-Entrega-BD-Modelo-E-R

Esta entrega consistio en realizar un diagrama entidad relación sobre un sistema de gestion de reservas, para nuestro proyecto intermodular


## Enunciado de Aules
Instrucciones en el PDF adjunto

Comentarios Generales a las prácticas de la UD2:
Hay que tener en cuenta que al corregir las prácticas valoro bastante el hecho de que me las
mandéis, por lo que las notas son en general altas.
Cuando tenéis un error en todos los ejercicios, sólo os quito nota en el primero de ellos, luego no os quito nota (porque si no sabéis que tenéis un error, no lo podéis corregir). Ahora bien, en el examen, sólo tendremos un ejercicio, por lo que si cometéis esos errores se os quitará nota (y en algunos casos mucha).
Una vez dicho eso, hay cosas que penalizarán mucho en el examen (y son fáciles de corregir, y además saltan a la vista):
Errores muy graves:
• Entidades sin atributo identificador. Tanto si se especifica en el enunciado como si no, toda entidad debe llevar atributo identificador
• máximas y mínimas no se corresponden con cardinalidades. Si tengo por un lado (1,1) y
(0,n) por ejemplo y pongo que la cardinalidad es N:M o falla una cosa o falla otra pero es el
propio diagrama el que está mal.
• Débiles con relaciones N:M. No pueden existir. ¿Porqué?
• Entidades o relaciones con el mismo nombre. Cada objeto en el diagrama debe llevar un
nombre distinto (excepto los atributos que sean equivalentes, nombre en la entidad cliente y
nombre en la entidad vendedor).
Errores graves:
• Atributos definidos por extensión. Cuando definimos un atributo podemos hacer por
extensión (especificando todos los posibles valores). Eso no quiere decir que haya que hacer
una ISA (especialización o generalización). Por ejemplo, Si decimos que de un cliente
vamos a guardar el sexo, Hombre o Mujer, no quiere decir que tengamos que hacer una
especialización de Cliente, sino que tenemos un atributo, sexo que tiene unos valores
definidos que pondremos en el diccionario de datos.