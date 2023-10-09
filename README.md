Evidencia 07

Integrantes:

    Kihara Millaldeo

    Camille Elgueta


(4)Actividades a realizar:

i. Identifique las clases y lo que éstas representan. Luego, establezca una descripción textual breve del contexto problema.

ii. Analice los atributos y métodos de cada clase, luego, identifique las relaciones existentes entre las clases identificadas y establezca una descripción textual breve del contexto problema..

iii. De lo anterior, establezca una representación detallada del código fuente, usando un diagrama de clases UML y la herramienta de modelado Visual Paradigm.

iv. Genere un código fuente Java a partir de su modelo de clases.

ANÁLISIS:

i. En el código fuente podemos distinguir entre dos clases:
    (1) Clase Calculadora(): En esta clase se realizan operaciones matemáticas (suma y multiplicación) con los datos ingresados en las variables n1 y n2, ambos de tipo int. Y a medida que se vayan ingresando los datos, las variables se van modificando, ya que están sujetas a Setters.
    (2) Clase CarroCompra(): En esta clase se ingresan los datos de cantidad y precio de los productos que se están "comprando" para luego calcular el total de la compra con la clase Calculadora().

En general, se está realizando una compra de algunos productos, lo cuales contienen un precio y una cantidad, y al final del programa se imprimirá por consola el total de la compra.

ii. En la clase Calculadora() tenemos los atributos n1 y n2 (ambos private int) y los siguientes métodos: sumar(), multiplicar(), los constructores Calculadora() y Calculadora(int num1,int num2), y los Setters setN1(int num1) y setN2(int num2).
La clase CarroCompra() posee un atributo, el cual es una matriz (private int) llamada productos. Además, se pueden apreciar los siguientes métodos: el constructor CarroCompra(), calcularTotal(), subTotal(int cant,int precio) y mostrarTotal().

La clase CarroCompra() depende de la clase Calculadora() para obtener los valores de subtotal y total mediante las operaciones matemáticas suma y multiplicación, y así entregar el resultado final por consola mediante un mensaje textual.