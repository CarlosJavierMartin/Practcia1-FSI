Prueba a mano:
Para realizar la prueba he escogido un ejemplo sencillo y corto, ademas para el calculo de las distancias simplemente he cogido la suma de 
el valor absoluto la resta de las distancias por coordenadas:

O-T
Bien sacamos de la pila el nodo inicial 'O' y metemos los 2 a los que nos podemos mover, apuntando su coste de movimiento, su distancia 
hasta el objetivo y la suma de ambos:
Camino: O
Stack: Z{71,135,206}--S{151,160,311}.
Como el valor mas pequelo es 206 entonces nos movemos a Z, este proceso describido lo aplicaremos hasta llegar al nodo objetivo, asi:

Camino: O -> Z{71,135,206} ->
Stack: S{151,160,311}--A{75,85,160}.

Camino: O -> Z{71,135,206} -> A{75,85,160}
Stack: S{151,160,311}--S'{140,160,300}--T*{118,0,118}.

Camino: O -> Z{71,135,206} -> A{75,85,160} -> T*{118,0,118}.
Stack: S{151,160,311}--S'{140,160,300}.

El resultado obtenido para el camino es O-Z-A-T
