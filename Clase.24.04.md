# Aclaraciones solemne

1. En Github existen diferentes tipos de archivo que uno puede crear. Para los apuntes en clases se debe usar .md este es el que se usa para texto y les aceptará el formato con markdown.
2. Es importante llevar las bitácoras al día, tanto la carpeta de cada sesión, como también ejercicios y desafíos.
3. Para agregar código de programación en los apuntes de clases, se debe usar también el formato de markdown. Se hace:
    * '''código''' (bloque de código)  
    *  'código p5' (Se usa entre medio de una oración)
4. Comentar el código de manera formal.
5. angleMode(DEGREES) solo configura el modo de medir los ángulos en grados.
___

# 4 pilares fundamentales 

**1. Descomposición**

"Dividir para conquistar"  
Consiste en tomar un problema grande y complejo y romperlo en partes más pequeñas y manejables.  
* **En diseño:** No hago todo de una vez. Primero creo una parte, después la otra, luego veo cómo se relacionan entre sí y, al final, agrego los detalles.
* **En el código:** Se traduce en el uso de Funciones Propias. En lugar de un draw() gigante, tienes una función dibujarIconos() y otra calcularDiferencia(), etc.

___

**2. Reconocimiento de patrones**  

"Encontrar similitudes"  
Es observar tendencias o regularidades dentro de un problema. Si algo se repite o sigue una lógica constante, podemos automatizarlo.
* **En diseño:** Para representar muchas cosas, no necesito dibujarlas una por una. Por ejemplo, si quiero mostrar muchos árboles, no tengo que dibujar cada uno desde cero, basta con repetir la misma forma cambiando su posición en el espacio.
* **En el código:** Se traduce en el uso de Bucles (for). Si hay un patrón, el código lo repite por ti con solo tres líneas.

___

**3. Abstracción**

"Lo importante vs. el detalle"  
Es filtrar la información que es innecesaria y quedarse solo con las características que definen el problema. Es crear una representación simbólica de la realidad.  
* **En diseño:** No necesito representar todo para transmitir una idea. A veces basta con una figura que se encoge cuando me acerco con el mouse para que se entienda.
* **En el código:** Se traduce en el uso de Variables y la función map(). Una posición de mouse (mouseX) se "abstrae" para convertirse en un valor de opacidad o miedo.

___

**4. Algoritmo**

"La receta paso a paso"  
Es el diseño de una serie de reglas ordenadas para resolver el problema. Es el "plan de acción" que debe seguir el sistema.  
* **En diseño:** Es el flujo de la experiencia. "Si el usuario hace esto, pasa aquello; si no, pasa esto otro”.
* **En el código:** Se traduce en el Diagrama de Flujo y en las Condicionales (if/else). Es el mapa lógico que conecta todas las partes   anteriores.

___

# Tipos de interacción

1. Interacción discreta (Eventos)  
Es cuando ocurre un evento específico (clic) y el sistema responde con una acción única (aparecen círculos). Es un interruptor de "encendido/apagado" o "acción/reacción".

En el código: Se suele usar dentro de la función mousePressed() o con un if(mouseIsPressed).

2. Interacción Continua (Input de Datos)  
Es cuando el sistema reacciona constantemente al movimiento o estado del usuario, sin necesidad
de hacer algo especifico (clic).

En el código: Usar mouseX o mouseY directamente para afectar el tamaño, color o velocidad
de algo.

___

# Funciones Propias

Las **Funciones propias** nos permiten darle modularidad al código.  Y reusabilidad, que nos permite repetir el código.  
Son unas especies de carpetas, para separar cada elemento del código. Cada "carpeta" va a contener cierta acción. 

Ej: function Nombredelafunción(){}

___

# Solemne 2

1. El Desafío  
El objetivo es demostrar:  
* Razonamiento lógico  
* Pensamiento sistémico

Diseñar un:  
"Organismo visual" en p5.js que funcione mediante reglas preestablecidas para visibilizar una problemática de genero.

Lo más importante es cómo traduces un problema social a una regla de comportamiento computacional.

2. Debe contener los 4 pilares fundamentales

* Descomposición: ¿Dividiste tu problemática en partes más pequeñas y manejables (funciones)?
* Reconocimiento de Patrones: ¿Usaste ciclos para crear estructuras o repeticiones con sentido (loops -for)?
* Abstracción: ¿Lograste que un movimiento o cambio visual represente un concepto real (ej. usar map para que el mouse represente "presión social")?
* Algoritmos: ¿Tu diagrama de flujo explica paso a paso cómo funciona tu sistema?

# INSTRUCCIONES

1.Pensar en una problemática de género que les interese. (Ej: La desigualdad en los honorarios entre hombres y mujeres, los estrictos cánones de belleza en las mujeres, los femicidios en Chile, la disforia de género, etc.)

2.Luego diseñar (idear) un sketch en movimiento, que represente (metafóricamente) o que nos ayude a visualizar de manera gráfica ese problema.

3.Hacer un diagrama de flujo de su idea. (Diseño de sistema)

4.Programar un sketch en p5.js de 400x400 pixeles. (Cómo mínimo) 
