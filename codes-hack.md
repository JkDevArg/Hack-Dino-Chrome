Puedes desconectarte o no del internet para poder ingresar:


chrome://dino/ 🦖

------------------------------------------------------------------------------

## Cambiar la apariencia del dinosaurio 🦖:

- Mario
- Batman
- Yoshi
- Jocker
- Default

------------------------------------------------------------------------------

Para poder usar los códigos se debera colocar dentro de la consola (Inspeccionar - Pestaña Consola)

## Cambiar el valor de la velocidad:

```Runner.instance_.setSpeed(1)```   -> Setea la velocidad x1.

```Runner.instance_.setSpeed(100)``` -> Setea la velocidad x100.

```Runner.instance_.setSpeed(-1)```  -> Setea la velocidad en -1 (Va perdiendo puntos a medida que retrocede)

```Runner.instance_.setSpeed(0.1)``` -> Setea la velocidad en 0.1 (No se mueve)

```Runner.instance_.setSpeed(500)``` -> Setea la velocidad x500 (va muy rapido)

## Cambiar el valor del salto en fuerza:

```Runner.instance_.tRex.setJumpVelocity(20)```   -> Salto Aumentado x20

```Runner.instance_.tRex.setJumpVelocity(50)```   -> Salto Aumentado x50

```Runner.instance_.tRex.setJumpVelocity(1000)``` -> Salto Auemntado x1000 (para ir a tomar un café y volver para ver como cae)

```Runner.instance_.tRex.setJumpVelocity(0)```    -> Salto x0 (No salta)

## Agregar Nubes dentro del panorama:

```Runner.instance_.horizon.addCloud()```

## Remueva el siguiente obstaculo:

```Runner.instance_.horizon.removeFirstObstacle()```

## Sale la Luna aunque sea de día:

```Runner.instance_.inverted = true```

## Remueve la función GameOver (Nunca se pierde)

```Runner.prototype.gameOver = function() {}```

## Valor para ganar puntos en el recorrido

```Runner.instance_.msPerFrame = 0.01``` -> cuanto menor sea el valor mas rápido se gana puntos

## Puntuación:

```Runner.instance_.distanceRan = 3999900```
