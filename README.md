# Programas en C++ de Javier Lucas 👨‍💻
![programacion](https://user-images.githubusercontent.com/101118941/170892136-e3d8b04b-e97b-4dd0-953f-83639361d968.jpeg)
# Datos del Creador 🧑‍💻​
#### Nombres del Creador:
Javier Lucas Angulo
#### Correo Electronico: 
joseph.lucas.angulo@utelvt.edu.ec
#### Actividad B1 video explicativo
https://www.youtube.com/watch?v=f7VARsCfIgE&t=197s


# Programas ​🖥️​
### 1. *Suma de varios numeros*
### 2. *Comparacion de dos numeros*
### 3. *Contador de Monedas*
### 4. *Punto de Venta*
### 5. *La Edad de una persona*



# Descripción de cada Programa 📱​
### 1. Suma ​➕​
Este programa nos permite colocar la cantidad de numeros que deseamos o vamos a sumar y asi mismo obtener un resultado del valor total de los numeros sumados.
#### |Funcionalidad|
*int LJ_c=0, LJ_n;*

*float LJ_x, LJ_s=0;*

*cout<<"Digite el valor de numeros que desea sumar: "<<endl;*

*cin>>LJ_n;*

do {
		
    cout<<"Digite el valor del numero: "<<endl;
		
    cin>>LJ_x;
		
    LJ_c=LJ_c+1; 
		
    LJ_s=LJ_s+LJ_x;
	
  } *while (LJ_c<LJ_n);*  
#### |Salida|

*cout<<"La porcion de numeros digitados es: "<<LJ_n<<endl;*

*cout<<"La suma total obtenida de los numeros es: "<<LJ_s<<endl;*

### 2. Compara "<" ">"
Este programa nos permite evaluar dos cantidades o valores y asi mismo llegar a una conclusión de que cantidad es mayor y cual menor o, si ambos valores son iguales.
#### |Funcionalidad|
*float  LJ_J, LJ_K;*

*cout<<"Digite un valor: "<<endl;*
  
*cin>>LJ_J;*
  
*cout<<"Digite un valor: "<<endl;*
  
*cin>>LJ_K;*
#### |Salida|
if (LJ_J==LJ_K) {

	cout<<"Los dos valores son iguales"<<endl;
	}
	else if (LJ_J>LJ_K){
		cout<<"El valor "<<LJ_J<<" es mayor que "<<LJ_K<<endl;
	}
	else{
		cout<<"El valor "<<LJ_K<<" es mayor que  "<<LJ_J<<endl; 
	} 
  
### 3. Contador de Monedas 💰​
Este programa permite que podamos contar o obtener la suma total de las monedas ingresadas, el numero de monedas que fueron digitadas, el valor de las monedas y cuantas monedas de (0.10, 0.25).
#### |Funcionalidad|

*int  LJ_n, LJ_d= 0 , LJ_d1= 0 , LJ_d2= 0 ;*

*float  LJ_x,LJ_e= 0 , LJ_e1= 0 , LJ_e2= 0 ;*
  
	cout<< "Digite el valor de monedas a contar :" <<endl;
	cin>>LJ_n;
	do{
		cout<< " Valor de moneda (0.10,0.25): " ;
		cin>>LJ_x;
		LJ_d=LJ_d+ 1 ;
		LJ_e=LJ_e+LJ_x;
		if (LJ_x== 10 ){
			LJ_d1=LJ_d1+ 1 ;
			LJ_e1=LJ_e1+LJ_x;
		} else {
		LJ_d2=LJ_d2+ 1 ;
		LJ_e2=LJ_e2+LJ_x;
		}
    } while (LJ_d<LJ_n);
#### |Salida|

	cout<< " Nos da como resultado: " <<endl;
  
	cout<< " El valor de monedas digitadas: " <<LJ_d<<endl;
  
	cout<< " El valor total del dinero sumado: " <<LJ_e<<endl;
  
	cout<< " El valor de monedas de 10 digitadas: " <<LJ_d1<<endl;
  
	cout<< " El valor total de monedas de 10: " <<LJ_e1<<endl;
  
	cout<< " El valor de monedas de 25 digitadas: " <<LJ_d2<<endl;
  
	cout<< " El valor total de monedas de 25: " <<LJ_e2<<endl;
  
  
  
  
  
  
  
  
  
  
  
  
  
  
