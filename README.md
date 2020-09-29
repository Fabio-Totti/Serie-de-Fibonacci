# Serie-de-Fibonacci

Para entender mejor como funciona este programa primero se debe conocer como funciona esta serie en las matematicas:

En matemáticas, la sucesión o serie de Fibonacci es la siguiente sucesión infinita de números naturales:

0,1,1,2,3,5,8,13,21,34,55,89,144,233,377,610,987,1597...

La sucesión comienza con los números 0 y 1; a partir de estos, "cada término es la suma de los dos anteriores", es la relación de recurrencia que la define. Los números de Fibonacci quedan definidos por las ecuaciones:

![7](https://user-images.githubusercontent.com/72088585/94619471-97214780-0272-11eb-95e9-0660c0abcbab.png)

Esto produce los siguientes números:

![8](https://user-images.githubusercontent.com/72088585/94620126-b1a7f080-0273-11eb-856f-76557a77a89a.png)

Y asi sucesivamente.
Esta manera de definir, de hecho considerada algorítmica, es usual en Matemática discreta. Es importante definir f0=0,para que se pueda cumplir la importante propiedad de que: fn divide a fm*n, para cualquier m,n>=1.

# Serie-de-Fibonacci basado en codigo C++

![1](https://user-images.githubusercontent.com/72088585/94620819-dbade280-0274-11eb-8df5-95721a5d3aca.png)

Este programa se constituye por dos segmentos, entre estos se encuentra el main, el cual cumple la función de mostrar mensajes al usuario con el proposito de realizar una tarea, asi como poner en función la parte principal que ejecuta la serie.

![2](https://user-images.githubusercontent.com/72088585/94621794-97bbdd00-0276-11eb-9a70-bf2e8ae403ab.png)

En este segmento realiza la serie de Fibonacci, a través de condiciones que se cumplen o no con la ayuda de if and else (si y no), con la cual se cumple con la funcion principal de la serie ![7](https://user-images.githubusercontent.com/72088585/94622789-752ac380-0278-11eb-9dba-6f03b9983502.png), asi como respetar las reglas de ![34](https://user-images.githubusercontent.com/72088585/94623005-d6eb2d80-0278-11eb-8199-6c5e2a838acd.png) y ![34](https://user-images.githubusercontent.com/72088585/94623057-fd10cd80-0278-11eb-8325-8b0fab245c1a.png):

![3](https://user-images.githubusercontent.com/72088585/94623169-35181080-0279-11eb-80c2-2acb5a7420c0.png)

# Ejecución del programa.

Se calcula la serie de Fibonacci de 5.

![4](https://user-images.githubusercontent.com/72088585/94623627-41e93400-027a-11eb-9ad5-a67a833ca8aa.png)

Se comparan los resultados:

f(5) = f(5-1) + f(5-2)

f(5) = f(4) + f(3)

f(5) = 3 + 2

f(5) = 5


Se calcula la serie de Fibonacci de 20.

![5](https://user-images.githubusercontent.com/72088585/94623897-e0759500-027a-11eb-8f58-5f886aad2dbe.png)

Se comparan los resultados:

f(20) = f(20-1) + f(20-2)

f(20) = f(19) + f(18)

f(20) = 4181 + 2584

f(20) = 6765
