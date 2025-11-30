
Reto1: simula el comportamiento de la tortuga usando solo print() e input()


[ ]
pasos=40
print("creando tortuga simulando que da...",pasos,"pasos")
print("-" * pasos + ">")
creando tortuga simulando que da... 40 pasos
---------------------------------------->
Reto 2: Tortuga bajando


[ ]
pasos=12
#(the turtle takes) "12 steps" (pasos)
print("|\n" * pasos,end="v")

print("\n la tortuga da 12 pasos hacia abajo...")


|
|
|
|
|
|
|
|
|
|
|
|
v
 la tortuga da 12 pasos hacia abajo...
Reto 3: Girar y dibujar usando solo print() e input()


[143]
0 s
pasosderecha=14
pasosabajo=8

#(The turtle advances 14 steps and turns 90 degrees to the right)
print("-" * pasosderecha + ">")
print((" " * pasosderecha +"|\n") * pasosabajo,end="")
print(" " *pasosderecha,end="v")



-------------->
              |
              |
              |
              |
              |
              |
              |
              |
              v
Reto 4: Encapsula los comportamientos anteriores usando funciones


[230]
0 s
def adelante(pasosadelante):
  print("-" * pasosadelante + ">")

def abajo(pasosadelante, pasosabajo):
  print((" " * pasosadelante +"|\n") * pasosabajo,end="")
  print(" " * pasosadelante,end="v")


adelante(40)
abajo(40,14)
---------------------------------------->
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        v
Reto 5: La tortuga baja las escalas


[246]
0 s
# escalon 1
adelante(40)
abajo(40,14)

# escalon 2
adelante(40)
abajo(81,14)

# escalon 3
adelante(40)

---------------------------------------->
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        |
                                        v---------------------------------------->
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 |
                                                                                 v---------------------------------------->
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          |
                                                                                                                          v
