# Ejemplo Documentación 
![ArduinoTinkercad](https://github.com/DylanFicocelli/SPD-1er-pacial/assets/138259829/5ee8614f-a3b0-4a44-b9e7-6fc14d10f65c)


## Integrantes 
- Facundo Fiestas
- Dylan Ficocelli 


## Proyecto: Displays 7 segmentos.
![Tinkercad](./img/ContadorBinario.png)


## Descripción
El proyecto consiste en un contador digital de dos dígitos con displays de 7 segmentos y botones de control. Su principal función es contar y mostrar números en el rango de 0 a 99, permitiendo al usuario incrementar, disminuir o reiniciar el contador según sus necesidades. 

## Función principal
Esta funcion se encarga de encender y apagar los leds.

B0, B1, B2, B3 son #define que utilizamos para agregar los leds, asociandolo a pines de la placa arduino.

(Breve explicación de la función)

~~~ C (lenguaje en el que esta escrito)
void EncenderBinario(int estado3, int estado2,int estado1,int estado0)
{
  digitalWrite(B3,estado3);
  digitalWrite(B2,estado2);
  digitalWrite(B1,estado1);
  digitalWrite(B0,estado0);
}
~~~

## :robot: Link al proyecto
- [proyecto](https://www.tinkercad.com/things/0REFfgG2ElS-1er-parcial-domiciliario-parte-1/editel?sharecode=fL2W4WToWBjQc9V-5es2W3xl5AusKXuD0pabNZhHJkQ)
