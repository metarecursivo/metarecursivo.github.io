---
title: ¿Quién elije primero?
featured: images/frac1.jpg
layout: post
---

<style TYPE="text/css">
code.has-jax {font: inherit; font-size: 100%; background: inherit; border: inherit;}
</style>
<script type="text/x-mathjax-config">
MathJax.Hub.Config({
    tex2jax: {
        inlineMath: [['$','$'], ['\\(','\\)']],
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'] // removed 'code' entry
    }
});
MathJax.Hub.Queue(function() {
    var all = MathJax.Hub.getAllJax(), i;
    for(i = 0; i < all.length; i += 1) {
        all[i].SourceElement().parentNode.className += ' has-jax';
    }
});
</script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-AMS_HTML-full"></script>

<div style="text-align: justify"> 


Prueba $x^2$

</div> 

<br>

<img src="/assets/images/Nier6.jpg" style="width: 100%; height: 100%" hspace="20">

<div style="text-align: justify"> 

El año 2020 va a estar marcado por cientos de eventos que se engloban entre lo terrorífico y la crisis existencial. Saldrán, además, nuevas consolas. Sony con su PlayStation5 y Microsoft con su XBox Series X que parecen querer dejarnos para final de año un pequeño regalito que nos quite este mal sabor de boca que nos está dejando un universo enfurecido. 
<br>
Conocemos el diseño de ambas consolas, ciertos elementos técnicos e incluso algunos de los juegos que podremos disfrutar durante estas primeras navidades con olor a generación 4K. Pero no sabemos el precio. Lo intuimos. Lo tememos. Nos empieza a doler la cartera. Alguna hucha que otra ya se ha empezado a llenar. Pero la incertidumbre sobre el precio sigue estando presente. Demasiadas variables y demasiado en juego parecen estar forzando a las compañías a retrasar la decisión sobre un número de 3 cifras que conoceremos en los próximos meses. 
<br>
A todo esto viene el conocido juego del ratón y el gato. Sony está esperando a Microsoft. Y Microsoft está esperando a Sony. Pero, ¿Por qué?
<br>
Como muchas cosas en esta vida la explicación es bastante sencilla pero, como economista que soy, me voy a encargar en este artículo de rodearla de palabraría y un modelito matemático que nos permita hacer algo más serio ese “análisis” de por qué es mejor esperar a decidir el precio. 
<br>
La información es poder. No es difícil entender por tanto que es mejor decidir con información en la mano que sin ella. Conocer el precio que va a poner tu competidor te deja en bandeja el intentar superarle. Y esperar a que tu competidor muestre sus cartas suele ser una estrategia nada desdeñable. Dicho grosso modo, la empresa X está esperando a que la empresa Y diga su precio para poder poner uno más barato (o para no pasarse de largo) e intentar robar una parte del pastel que le sería más difícil conseguir si ambas tuvieran que decidir y decir el precio con los ojos vendados.
<br>
Es curioso, no obstante, que el que elija segundo sea el que salga ganando en este duelo, sobre todo cuando casi todo estudiante de economía acaba sus estudios microeconómicos viendo el modelo de Stackelberg, un modelo en donde el que elije primero, obtiene más beneficio. La diferencia, como siempre es importante recalcar, es que los modelos son abstracciones que se nutren de unas hipótesis iniciales. Si estas no se cumplen, el modelo no nos vale para describir la microrealidad que estamos estudiando. En este caso el modelo de Stackelberg se refiere a la competencia empresarial en cantidades de un producto homogéneo. Esto es: Ambas empresas hacen un producto similar que compartirán el mismo precio en un mercado en dónde los consumidores no distinguen entre empresas. En este contexto, la primera empresa que consiga “copar” el mercado se va a llevar el gato al agua. 
<br>
La realidad es que la competencia entre Sony y Microsoft se parecen a esos modelos iniciales como un huevo a una castaña. La diferencia fundamental es que ambas empresas están diferenciadas, en mayor o menor grado, y eso implica que aunque exista una cierta sustituibilidad entre los productos que vendan una y otra, no son exactamente iguales. Esa diferenciación implica que cada empresa debe elegir un precio y dejar que los consumidores decidan en base a ese precio cuantas unidades específicas de los productos de esa empresa comprar. 
<br>
¿Cómo podemos crear un modelo que recoja esta competencia oligopolística (entre dos empresas) con un producto diferenciado que va a competir en precios? Como todo modelo, nos vamos a dejar muchas cosas por el camino, pero intentaremos destacar lo más importante.
<br>
Primero, vamos a utilizar unas funciones de demanda con las que he trabajado bastante que son las de Dixit-Stiglitz. Éstas se basan en el concepto de “competencia monopolística”, en donde se intenta unir el hecho de que empresas diferentes con marcas específicas (y por tanto con el monopolio de la identidad de su producto) compiten por satisfacer necesidades concretas o similares (con cierto grado de sustituibilidad entre los productos).
<br>
Supondremos que existen dos empresas (empresa 1 y empresa 2). La cantidad de demanda (q) de cada una de las empresas se puede describir de la siguiente manera:
<br>
Lo primero que voy a quitarme de en medio para hacer un poco más simple el análisis es el valor de sigma. Este parámetro mide precisamente el grado de diferenciación del producto. Va desde 1 hasta infinito. Es el valor de la elasticidad de demanda o del grado de homogeneidad del producto.
<br>
Si el valor fuera muy alto, significaría que el producto es muy elástico y homogéneo, es decir, un consumidor que tenga que elegir entre las dos empresas elegirá siempre el producto más barato porque, por lo demás, le parecen idénticos.  
<br>
Si el valor fuera muy bajo, el producto sería menos elástico y, por tanto, más diferenciado. En este caso que una empresa suba el precio va a hacerle perder clientes, pero no muchos, porque tiene una gran parte del mercado que “va a caer al pozo” y comprar su producto siempre y cuando el precio no se vaya de madre. Su producto es tan diferenciado que el que tu producto pueda ser más caro no va a hacer directamente que los clientes salten a comprar los productos de la competencia. 
<br>
Por descontado, las empresas no solo eligen cuánto producir y a qué precio poner sus productos en las tiendas. La variable de la diferenciación es crucial para crear ese mercado menos elástico sobre el que poder poner unos precios más altos. En el tema que nos toca, las videoconsolas, dos claros ejemplos me vienen a la mente: La potencia y los exclusivos. Pueden diferenciarse intentando meterle más teraflops (la variable de moda en esta entrada a la nueva generación) y además Sony y Microsoft disponen de estudios propios y externos que hacen juegos específicos para sus consolas. En este contexto, comprar la más barata ya no es lo más importante, si lo que quieres es jugar a Bloodborne 2 o al nuevo Halo. 
<br>
En lo que concierne al modelo, vamos a suponer para hacer las cuentas más simples que el valor es de 2. De esta forma los exponentes quedan más sencillos (después relajaré un poco este supuesto para que podamos ver algunas extensiones interesantes). En cualquier caso, por si a alguno le interesa, la conclusión más importante del parámetro sigma es que, contra más bajo sea, mayor poder monopolístico tendrán las empresas (más importante será el concepto de marca) y mayor serán los precios y los beneficios. Hasta Desatranques Jaen conoce bien el poder de la diferenciación del producto.
<br>
La otra parte que nos queda (mu Y) hace referencia al dinero que la gente se va a gastar en videoconsolas. Contra mayor sea la renta de la gente, o más % de su gasto quieran destinar a gastar en videoconsolas (que como es un “bien de lujo” crecerá también conforme crezca la renta), más consolas venderán. Algo bastante obvio que luego realmente no va afectar al precio óptimo. 
<br>
Vale. ¿Qué hace una empresa para optimizar su producto? Coge su función de beneficio y la optimiza. Si el producto es homogéneo, el precio va a venir determinado por un mercado al que el producto de cada empresa le es indiferente, y lo que la empresa puede decidir es cuánta cantidad quiere producir y enviar al mercado. Si es diferenciado, como en este caso, la empresa tiene un cierto poder de decisión sobre su precio, permitiéndose poner un precio particular a su producto. Supondremos, pues es el origen del análisis de este artículo, que la empresa elije el precio que maximiza su beneficio.
<br>
¿Cuál es su beneficio?
<br>
Pues ingresos menos costes, claro. Ah, pero para el carro que la cosa no es tan simple. Obviamente la empresa incurrirá en unos costes para la fabricación de cada producto, que supondremos que son constantes e iguales a c. Supondremos, además, que el coste es el mismo para cada una de las empresas. Aquí ya empezamos con problemas puesto que es posible que por motivos técnicos una tenga unos costes de fabricación ligeramente superiores a la otra. De nuevo, al no disponer de información correcta sobre este tema, lo mejor que puedo hacer es intentar no complicarlo más de la cuenta poniendo costes diferentes que, de ocurrir, tampoco serán tan distintos (Siempre podemos al final afinar un poco complicando algo más el modelo).
<br>
En cuanto a ingresos, la cosa es algo más peliaguda. Aquí entramos en otra estrategia de diseño en la que la empresa puede incidir, dado que la consola como tal no es un bien que permita satisfacer una necesidad de forma directa, si no a través de los juegos que se compren y jueguen con ella. Esto es, el ingreso potencial de una consola vendida no es únicamente su precio, si no el flujo de beneficios que pueda conseguir extraer de los consumidores que la hayan comprado. Beneficios por juegos first-party, gamepasses, pspluses… Esto permite que en el mercado el precio de las máquinas pueda incluso ser inferior al coste de fabricación, ya que puede expandir mucho más su mercado y recuperar esas perdidas en la venta de otros servicios. PlayStation y Xbox son bienes sustitutivos pero, dentro de cada una de las marcas, los servicios y productos de cada una de ellas son bienes complementarios. Si los juegos de una de las consolas fueran de serie más baratos, por ejemplo si tuviéramos en cuenta el GamePass de Xbox, a lo mejor admitiría que la consola fuera un pelín mas cara, o viceversa. 
<br>
Por ello, vamos a suponer que los beneficios son iguales a: El precio por consola vendida – los costes por consola vendida + Beneficios potenciales futuros por consola vendida:
<br>
</div> 

<div style="text-align: justify"> 
$B_{1}=P_{1} q_{1}-c q_{1}+BP q_{1}=P_{1} q_{1}-cn q_{1}$
<br>
Donde $cn=c-BP$
</div> 

<br>
<div style="text-align: right"> 
<blockquote> 
I never quite realized, how beautiful this world is
<br>
<strong>A2</strong>
</blockquote>
</div> 
<br>

<strong>Pod 153</strong>: Proposal: R debería finalizar aquí.
