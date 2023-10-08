# SPD 1er parcial - Display 7 segmentos
![ArduinoTinkercad](https://github.com/DylanFicocelli/SPD-1er-pacial/assets/138259829/5ee8614f-a3b0-4a44-b9e7-6fc14d10f65c)


## Integrantes 
- Facundo Fiestas
- Dylan Ficocelli 


## Proyecto: Displays 7 segmentos.
![display 7 segmentos](https://github.com/DylanFicocelli/SPD-1er-pacial/assets/138259829/a55ce53e-87b6-4aed-9d8c-a976a0f4632e)



## Descripción
El proyecto consiste en un contador digital de dos dígitos con displays de 7 segmentos y botones de control. Su principal función es contar y mostrar números en el rango de 0 a 99, permitiendo al usuario incrementar, disminuir o reiniciar el contador según sus necesidades. 

## Función principal
Esta función se encarga de reflejar el número actual en los displays y actualizar la visualización en tiempo real.

La función  printCount es la principal del proyecto. Utiliza dos funciones auxiliares, prendeDigito y mostrarNumero, para controlar y mostrar el número en los displays de siete segmentos. Primero, apaga todos los dígitos, luego muestra la cifra de las decenas en el display de la izquierda, enciende ese dígito y lo apaga, después muestra la cifra de las unidades en el display de la derecha y lo enciende.

~~~ C++ (lenguaje en el que esta escrito)
void printCount(int count)
{
            prendeDigito(APAGADOS);
  	mostrarNumero(count/10);
  	prendeDigito(DECENA); 
  	prendeDigito(APAGADOS);
  	mostrarNumero(count - 10*((int)count/10));
  	prendeDigito(UNIDAD);

}
~~~

## Link al proyecto
- [SPD - Displays 7 segmentos](https://www.tinkercad.com/things/0REFfgG2ElS-1er-parcial-domiciliario-parte-1/editel?sharecode=fL2W4WToWBjQc9V-5es2W3xl5AusKXuD0pabNZhHJkQ)
