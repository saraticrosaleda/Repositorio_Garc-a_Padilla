# Repositorio_Garc-a_Padilla






Algoritmo Promedio
	Definir opciones como caracter
	opciones<-"s"
	
	Mientras opciones == "s" Hacer
		Escribir "Ingrese la cantidad de datos: "
		Leer n
		acum<-0
		
		Si n>0 Entonces
			Escribir "El número es positivo"
			Para i<-1 hasta n Hacer
				Escribir "Ingrese el dato",i,":"
				Leer dato
				acum<-acum+dato
			FinPara
		Sino 
			Repetir
				Escribir "El número es negativo ingrese un número positivo"
				Leer n;
				si n<-0 Entonces
					
				FinSi
			Hasta Que n>0
			//Escribir "Correcto ingrese la cantidad de datos: "
			//Leer n;
			//acum<-0
			Para i<-1 Hasta n Hacer
				Escribir "Ingrese el dato ",i,":"
				Leer dato
				acum<-acum+dato
			FinPara
		FinSi
		
		prom<-acum/n
		Escribir "El promedio es:",prom
	Escribir "¿Desea seguir ejecutando el programa?" [S/N]
		Leer opciones 
	FinMientras
FinAlgoritmo
