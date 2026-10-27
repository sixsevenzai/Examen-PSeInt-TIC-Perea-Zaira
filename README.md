# Examen-PSeInt-TIC-Perea-Zaira 
ejercicio_12.psc
Algoritmo Búsqueda_de_un_NúmeroSecreto
	Definir numsecreto, num Como entero;
	
	Escribir "Ingrese un numero: "; 
	Leer num; 
	numsecreto= Aleatorio(1,100);
	Mientras  numsecreto <> num Hacer
			Si num > numsecreto  Entonces
				escribir "el numero secreto es mayor"; 
			SiNo
				Escribir "el numero es menor:";
			FinSi
			
	FinMientras
	

FinAlgoritmo
