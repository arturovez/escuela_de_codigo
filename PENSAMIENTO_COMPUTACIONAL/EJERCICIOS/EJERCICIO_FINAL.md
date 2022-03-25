Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.


int intentos = 10
int num secreto =5
int num
print "Juego"
while intentos > 0{
print tiene "intentos" intentos
print ingrese un numero
num = num
print ??????????
if num = numsecreto {
print Ganaste en (10 - intentos)
intentos = 0}
else {
  if num < numsecreto
    print numero menor !
    print quedan "intentos" intentos !
  else
    print numero mayor !
    print quedan intentos !
    }


Algoritmo Juego
	numSecreto <- 5
	intentos <- 10
	ganar<-0
	
	Mientras intentos > 0 Hacer
		Escribir 'juego ! tienes ', intentos, ' intentos !'
		Escribir 'Adivina un número!'
		Leer num
		Si num == numSecreto Entonces
			Escribir 'El número secreto es ', num, ', Ganaste en ', (11-intentos), ' intentos !'
			intentos <- 0
			ganar <- 0
		SiNo
			 
			intentos<-intentos -1
			Si num < numSecreto Entonces
				Escribir 'Es menor, te quedan ', intentos, ' intentos.'
			SiNo
				Escribir 'Es mayor, te quedan ', intentos, ' intentos.'
			Fin Si
			Si intentos == 0 Entonces
				Escribir 'Perdiste !'
			Fin Si
		Fin Si
		
	Fin Mientras
	
	Escribir 'Fin del Juego?'	
	
FinAlgoritmo




Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing
