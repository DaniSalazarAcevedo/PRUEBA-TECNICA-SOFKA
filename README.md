
DANIELA ANDREA SALAZAR ACEVEDO 
PRUEBA TECNICA / TRANING CALIDAD


CONSTRUCCIÓN DEL ALGORTIMO
Inicialmente desarrolle un pseudocodigo donde hago una recoleccion de datos de entrada con el fin de obtener lectura de datos,
y los procesos mediante operaciones matematicas y las salidas para finalizar.




PSEUDOCODIGO

PUNTO 1 

  Algoritmo Pasaje
   definir distancia , descuento, valorp, pago como real;
   	definir dias_estancia Como Entero;

  escribir "INGRESE LOS KM DE DISTANCIA A RECORRER";
  leer distancia ;
  escribir "INGRESE LOS DIAS DE ESTANCIA ";
  leer dias_estancia;
	  valor_kilometro = 35.00; 
 valorp=valor_kilometro*distancia
 descuento = distancia* valor_kilometro* 0.3;
		pago = valorp - descuento
		
	SiNo
	
		pago = valorp
		descuento = 0;
	FinSi

	escribir "EL PAGO A REALIZAR ES DE : $",pago
	escribir "EL DESCUENTO ES DE : $",descuento


  FinAlgoritmo
 

PUNTO 2


mayor = 0, menor = 501, bucle = 0, p = 0, b = 0, lb = 0, px = 0, i = 0, n = 0	   
    while bucle = 0
        p = 0
	        while p = 0
	            input b
	            while b > 500
                print "No puede exceder los 500 kg";
	                input b
            endwhile
            px = px + b
	            p = 1
	            if px > 18000
	                lb = px - 18000
                print "Capacidad para bs en Kg: " lb;
	                px = px - b
	                p = 0
            endif
	        endwhile
       
	        if mayor < b
            mayor = b
	        endif
        if menor > b
	            menor = b
	        endif
        if b <= 25
            i = i + b*0
        else
	            if b > 25 and b <= 300
	                i = i + b*1500
	            else
	                i = i + b*2500
	            endif
        endif
	        n = n + 1
        if px = 18000
            exit
        endif
	    endwhile
	   
	    print "Número total de bultos: n;
	    print "Peso del bulto más pesado: " mayor;
	    print "Peso del bulto más liviano: " menor;
	    print "Peso promedio de los bultos: " px/n;
	    print "Ingreso en soles por concepto de carga:
      " i;



TECNOLOGIAS UTILIZADAS

NETBEANS - JAVA
PSEINT
GIT-HUB



COMO EJECUTARLO

para la ejecución de los algoritmos:


1. Descargar el archivo zip (algoritmos)
2. Descargar NetBeans IDE 8.0.2
3. Ingresar a NetBeans y abrir los algoritmos 
4. Ejecutar Algoritmos

