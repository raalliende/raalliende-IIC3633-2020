El paper comienza describiendo el problema y dando un outline de lo que el paper va a tratar. despues describe metodos similares a los que va a exponer, seguido de una formalización del problema, una descripcion del problema de optimización, seguido de los metodos para resolver el problema de optimización. Luego el paper describe como se puede aplicar ese modelo a distintas metodologias de prediccion, terminando con una comparasion experimental del metodo comparado con otros metodos.

Uno de los puntos que en mi opinion son los más fuertes del paper, es el buen planteamiento del problema y su formalización. Que es responder la pregunta, ante dos opciones cual va a prefeferir el usuario. En el paper exigen que este orden sea total, a pesar de que hacen referncia a que no es posible saber el orden de algunos items con la información entregada. Esto parece contradictorio, pero despues se hace evidente que la restirccion de orden total es impuesta para simplificar calculos. Lo que lleva a la pregunta de si existe un metodo para calcular facilmente un orden parcial.

El paper tambien hace alusión al uso de stochastic gradient descent, como metodo de optimización, metodo bastante utilizado y que ayuda considerablemente en los calculos del optimo.

En cuanto a la metodología de evaluación, es importante notar como utilizaron el metodo leave-one-out, este metodo si bien es costoso es bastante preciso y aporta mucho en dar validez a los resultados obtenidos.