Predecir la necesidad de una cesárea

@Author: Maite Sánchez Fornaris

@email: maite.sanchez@reduc.edu.cu

Los especialistas en gineco-obstretricia deciden hacerle una cesárea a una parturienta basados en distintas constantes físicas que describen el estado de la mujer y del bebé. En este caso, se se toman solamente algunas de las constantes vitales y padecimientos crónicos de la madre para entrenar un perceptrón simple y predecir resultados a partir del entrenamiento hecho.

Las variables que se utilizaron fueron:

      @attribute 'Age' { 22,26,28,27,32,36,33,23,20,29,25,37,24,18,30,40,31,19,21,35,17,38 }
      
      @attribute 'Delivery number' { 1,2,3,4 }
      
      @attribute 'Delivery time' { 0,1,2 } -> {0 = timely , 1 = premature , 2 = latecomer}
      
      @attribute 'Blood Pressure' { 2,1,0 } -> {0 = low , 1 = normal , 2 = high }
      
      @attribute 'Heart Problem' { 1,0 } -> {0 = apt, 1 = inept }
      
      @attribute 'Caesarian' { 0,1 } -> {0 = No, 1 = Yes }
      
Donde los rasgos de entrada son la edad, el número de partos, momento del parto, presión arterial, problemas del corazón previos. De estas variables, la edad y el número de partos son nominales; mientras que el momento del parto, la presión arterial y la variable problemas del corazón previos son ordinales.
Lo que se desea predecir es el atributo cesarea que se considera una variable ordinal.
