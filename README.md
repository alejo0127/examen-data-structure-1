# examen-data-structure-1

PREGUNTA NUMERO 1.

numeral 1:
Primero que todo es importante hacer el resize como primer punto por el hecho de que se cuenta con un numero limitado de elementos al momento de insertar en el vector, y por eso es necesario/obligatorio el hecho de expandir el tamaño del vector, el problema de almancenar en diferentes lugares de la memoria es que para eso existe previamente un storage que converge con el size, de tal manera que la cantidad de elementos que tengamos en nuestro vector deben estar guardados en ese lugar, entonces no habria una manera de guardalos en varios lugares de la memoria, y al momento que se hace resize tambien estamos expandiento tanto el tamaño del vector como su storage, entonces para concluir el resize es mas que necesario y seguir guardado el tamaño del vector y los elementos es imprescindible para el correcto uso de la estructura de datos vector.

numeral 2:
Yo opino que la lista enlazada tiende a ser mas eficiente debido a diferentes puntos, como por ejemplo el hecho de no tener que limitar a un numero exacto de elementos comparandose con el vector, que ademas tenemos un enlace que nos conecta tanto al primer como al ultimo elemento lo cual es beneficioso para poder movernos mejor en la estructura de datos, ademas contamos con la ventaja de no tener que hacer continuamente resize para agregar nuevos elementos que va un poco de la mano con el primer punto que expuse en esta respuesta, ademas de las diferentes funcionalidades que se puede llegar a tener, con la ventaja de insertar elementos con el push_front, push_back, es decir tanto por delante como por detras de la lista, y para finalizar el hecho de que vaya enlazada es importante porque siempre vamos a tener un apuntador a la direccion en memoria del siguiente elemento, y asi saber tanto siguiente de cada elemento y en las doblemente enlazadas aun mejor porque se sabe tanto el anterior como el siguiente pero en el caso de las enlazadas el siguiente sigue siendo una gran ventaja, en comparacion con lo que no ocurre en el vector.



PREGUNTA NUMERO 2.

numeral 1:
            CAPACIDAD FINAL  |   DESPERDICIO
Vector x :      10240        |       240
Vector y :      11568        |      1568
Vector z :      12800        |      2800


numeral 2:
El vector X fue el vector mas optimo el cual desperdicio menos espacio, sorprendentemente porque a primera vista pareciera el vector Y mas optimo, pero el vector x redimensionandose en 2 es mejor, opinaria que por el hecho de ser primero el size del vector mas pequeño entre los 3 y ademas pues mientras el empieza a redimensionarse multplicandose por 2 el espacio es mas pequeño a comparasion de los otros dos vectores que de a poco van mostrando un gasto mayor en el espacio y de esta manera al iterar la i hasta 10000, se demuestra que el vector mas eficiente es el numero 1, y los otros dos a pesar de la diferencia no se tan abismal tienden a gastar o a tener ese espacio basura en los vectores.



PREGUNTA NUMERO 3.

<typename T>

class AdjacencyList{

    T transporte;

    class Nodo{

        Nodo *siguiente;
        Nodo *anterior;




















