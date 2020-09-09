# PRUEBA-TECNICA-SOFKA
DANIELA ANDREA SALAZAR ACEVEDO 
PRUEBA TECNICA / TRANING CALIDAD


CONSTRUCCIÓN DEL ALGORTIMO
Inicialmente desarrolle un pseudocodigo donde hago una recoleccion de datos de entrada con el fin de obtener lectura de datos,
y los procesos mediante operaciones matematicas y las salidas para finalizar.

PSEUDOCODIGO

Punto1
1.Algoritmo Pasaje
2.	definir distancia , descuento, valorp, pago como real;
3.	definir dias_estancia Como Entero;
4.	
5.	escribir "INGRESE LOS KM DE DISTANCIA A RECORRER";
6.	leer distancia ;
7.	escribir "INGRESE LOS DIAS DE ESTANCIA ";
8.	leer dias_estancia;
9.	valor_kilometro = 35.00; 
10.	valorp=valor_kilometro*distancia
11.	si (distancia > 1000 y dias_estancia > 7)
12.		descuento = distancia* valor_kilometro* 0.3;
13.		pago = valorp - descuento
14.		
15.	SiNo
16		
17.		pago = valorp
18.		descuento = 0;
19.	FinSi
20.	
21.	escribir "EL PAGO A REALIZAR ES DE : $",pago
22.	escribir "EL DESCUENTO ES DE : $",descuento
23.
24.
25.  FinAlgoritmo
 

Punto2 
1.	mayor = 0, menor = 501, bucle = 0, p = 0, b = 0, lb = 0, px = 0, i = 0, n = 0
2.	   
3.	    while bucle = 0
4.	        p = 0
5.	        while p = 0
6.	            input b
7.	            while b > 500
8.	                print "No puede exceder los 500 kg";
9.	                input b
10.	            endwhile
11.	            px = px + b
12.	            p = 1
13.	            if px > 18000
14.	                lb = px - 18000
15.	                print "Capacidad para bs en Kg: " lb;
16.	                px = px - b
17.	                p = 0
18.	            endif
19.	        endwhile
20.	       
21.	        if mayor < b
22.	            mayor = b
23.	        endif
24.	        if menor > b
25.	            menor = b
26.	        endif
27.	        if b <= 25
28.	            i = i + b*0
29.	        else
30.	            if b > 25 and b <= 300
31.	                i = i + b*1500
32.	            else
33.	                i = i + b*2500
34.	            endif
35.	        endif
36.	        n = n + 1
37.	        if px = 18000
38.	            exit
39.	        endif
40.	    endwhile
41.	   
42.	    print "Número total de bultos: n;
43.	    print "Peso del bulto más pesado: " mayor;
44.	    print "Peso del bulto más liviano: " menor;
45.	    print "Peso promedio de los bultos: " px/n;
46.	    print "Ingreso en soles por concepto de carga:
47.       " i;


TECNOLOGIAS UTILIZADAS

NETBEANS - JAVA
PSEINT
GIT-HUB



COMO EJECUTARLO
para la ejecución de los algoritmos:
Pasos:
1. Descargar el archivo zip (algoritmos)
2. Descargar NetBeans IDE 8.0.2
3. Ingresar a NetBeans y abrir los algoritmos 
4. Ejecutar Algoritmos

