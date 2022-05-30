# Programas en C++ de Javier Lucas 👨‍💻
![programacion](https://user-images.githubusercontent.com/101118941/170892136-e3d8b04b-e97b-4dd0-953f-83639361d968.jpeg)
# Datos del Creador 🧑‍💻​
#### Nombres del Creador:
Joseph Javier Lucas Angulo
#### Correo Electronico: 
joseph.lucas.angulo@utelvt.edu.ec
#### Actividad B1 video explicativo
https://www.youtube.com/watch?v=f7VARsCfIgE&t=197s


#   Programas ​🖥️​
### 1. *Suma de varios numeros*
### 2. *Comparacion de dos numeros*
### 3. *Contador de Monedas*
### 4. *Punto de Venta*
### 5. *La Edad de una persona*



# Descripción de cada Programa 📱​
### 1. Suma ​➕​
Este programa nos permite obtener un resultado del valor total de los numeros sumados, evaluando la cantidad de numeros ingresados y el valor que tiene cada cantidad.
### |Funcionalidad|
#### ¿Como funciona?

##### -El primer paso es declarar las variables, pueden ser estas letras o numeros.

*int LJ_c=0, LJ_n;*

*float LJ_x, LJ_s=0;*

##### -A continuacion mostramos en pantalla cualquier tipo de comentario utilizando el comando "cout".

*cout<<"Digite el valor de numeros que desea sumar: "<<endl;*

##### -En este caso introduciremos la variable utilizando el comando de "cin".

*cin>>LJ_n;*

##### -A continuacion utilizaremos una estructura de tipo repetitiva la cual permite ejecutar de manera repetitiva un bloque de instrucciones sin evaluar de forma inmediata una condición especifica, sino evaluándola justo después de ejecutar por primera vez el bloque de instrucciones.

do {
		
    cout<<"Digite el valor del numero: "<<endl;
		
    cin>>LJ_x;
		
    LJ_c=LJ_c+1; 
		
    LJ_s=LJ_s+LJ_x;
	
  } *while (LJ_c<LJ_n);*  
### |Salida|
##### -En este apartado se mostrará el resultado obtenido en dicho programa.

*cout<<"La porcion de numeros digitados es: "<<LJ_n<<endl;*

*cout<<"La suma total obtenida de los numeros es: "<<LJ_s<<endl;*

### 2. Compara "<" ">"
Este programa nos permite evaluar dos cantidades o valores y asi mismo llegar a una conclusión de que cantidad es mayor y cual menor o, si ambos valores son iguales.
### |Funcionalidad|
##### -Declaramos variables

*float  LJ_J, LJ_K;*

##### -Mostraremos en pantalla un comentario y introduciremos las variables con el comando "cin" como ya habia mencionado.

*cout<<"Digite un valor: "<<endl;*
  
*cin>>LJ_J;*
  
*cout<<"Digite un valor: "<<endl;*
  
*cin>>LJ_K;*

##### -En este caso se utilizara una estructura de tipo selectiva doble la cual permite definir una condición que se debe cumplir y de acuerdo a su cumplimiento o no tomar una acción correspondiente. 

if (LJ_J==LJ_K) {

	cout<<"Los dos valores son iguales"<<endl;
	}
	else if (LJ_J>LJ_K){
		cout<<"El valor "<<LJ_J<<" es mayor que "<<LJ_K<<endl;
	}
	else{
		cout<<"El valor "<<LJ_K<<" es mayor que  "<<LJ_J<<endl; 
	} 
  

### |Salida|
##### -Se muestran los resultados obtenidos
cout<<"Los dos valores son iguales"<<endl;
	
cout<<"El valor "<<LJ_J<<" es mayor que "<<LJ_K<<endl;
	
cout<<"El valor "<<LJ_K<<" es mayor que  "<<LJ_J<<endl; 
	
### 3. Contador de Monedas 💰​
Este programa permite que podamos contar o obtener la suma total de las monedas ingresadas, el numero de monedas que fueron digitadas, el valor de las monedas y cuantas monedas de (0.10, 0.25).
### |Funcionalidad|
#### ¿Como funciona?
##### -Declaramos variables
*int  LJ_n, LJ_d= 0 , LJ_d1= 0 , LJ_d2= 0 ;*

*float  LJ_x,LJ_e= 0 , LJ_e1= 0 , LJ_e2= 0 ;*

##### -Ingresamos un comentario y introducimos la variable.
  
*cout<< "Digite el valor de monedas a contar :" <<endl;*

*cin>>LJ_n;*

##### -Utilizamos una estructura repetitiva como ya habiamos mencionado anteriormente esta nos permite ejecutar de manera repetitiva un bloque de instrucciones sin evaluar de forma inmediata una condición especifica, sino evaluándola justo después de ejecutar por primera vez el bloque de instrucciones.

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
### |Salida|
##### -Obtenemos como resultado:
	cout<< " Nos da como resultado: " <<endl;
  
	cout<< " El valor de monedas digitadas: " <<LJ_d<<endl;
  
	cout<< " El valor total del dinero sumado: " <<LJ_e<<endl;
  
	cout<< " El valor de monedas de 10 digitadas: " <<LJ_d1<<endl;
  
	cout<< " El valor total de monedas de 10: " <<LJ_e1<<endl;
  
	cout<< " El valor de monedas de 25 digitadas: " <<LJ_d2<<endl;
  
	cout<< " El valor total de monedas de 25: " <<LJ_e2<<endl;

### 4. Punto de Venta 🏪​
Es un programa creado para llevar el control de ventas e inventarios en un negocio. En este caso se evaluara varios puntos entre ellos: número de productos comprados, el valor total de la compra, y el valor de descuento que utilizara.
### |Funcionalidad|
#### ¿Como funciona?
##### -Declaramos variables

*int LJ_a=0, LJ_b;*

*float LJ_m=0, LJ_h, LJ_e, LJ_v, LJ_v1, LJ_iv, LJ_f;*
##### -Mostramos un comentario y introduciremos la variable

*cout<<"Digite el valor de los producto a sumar"<<endl;*

*cin>>LJ_b;*
##### -Utilizamos un tipo de estructura repetitiva para evaluar el valor de la compra y el descuento a utilizar.

do{

        cout<<"Digite el valor de su compra "<<LJ_a+1<<endl;
	
	cin>>LJ_h;
	
	LJ_a=LJ_a+1;
	
        LJ_m=LJ_m+LJ_h;
	
}while (LJ_a<LJ_b);

cout<<"Digite el valor del descuento que utilizara: "<<endl;

cin>>LJ_e;
### |Salida|
##### -Mostramos el resultado obtenido

*cout<<"Valor bruto de compra: "<<LJ_m<<endl;*

*LJ_v=(LJ_m*LJ_e)/100;

*cout<<"Valor del descuento: "<<LJ_v<<endl;*

*LJ_v1=LJ_m-LJ_v;*

*LJ_iv=LJ_v1*0.12;

*cout<<"Valor del IVA: "<<LJ_iv<<endl;*

*LJ_f=(LJ_m-LJ_v)+LJ_iv;*

*cout<<"Valor final: "<<LJ_f<<endl;*
  
### 5. La Edad de una persona 🙍‍♂️​🙍​
Este programa nos permite calcular la edad de una persona, utilizando la fecha actual y la fecha de nacimiento de dicha persona.
### |Funcionalidad|
##### ¿Como funciona?
##### -Declarar variables

int LJ_dd, LJ_mm, LJ_jj, LJ_dd1, LJ_mm1, LJ_jj1, LJ_de, LJ_me, LJ_ye;
##### -En este caso se pedira que se muestre en pantalla la fecha actual y la fecha de nacimiento usando formato dd/mm/yy (dia-mes-año).

*cout<<"Digite la fecha actual usando formato dd/mm/yy: "<<endl;*

*cin>>LJ_dd>>LJ_mm>>LJ_jj;*

*cout<<"Digite su fecha de nacimiento usando formato dd/mm/yy: "<<endl;*

*cin>>LJ_dd1>>LJ_mm1>>LJ_jj1;*
##### -Se utilizara una estructura selectiva doble para evaluar una condición, en caso de que no se cumpla dicha condición realizar otra acción o instrucción.

	if (LJ_dd<LJ_dd1){
		LJ_dd=LJ_dd+30;
		LJ_mm=LJ_mm-1;
		LJ_de=LJ_dd-LJ_dd1;
	}
		else {
			LJ_de=LJ_dd-LJ_dd1;
		}
	if (LJ_mm<LJ_mm1){
		LJ_mm=LJ_mm+12;
		LJ_jj=LJ_jj-1;
		LJ_me=LJ_mm-LJ_mm1;
	}
		else {
			LJ_me=LJ_mm-LJ_mm1;
		}
	LJ_ye=LJ_jj-LJ_jj1;
 ### |Salida|
 ##### -Mostramos en pantalla el resultado obtenido
 
 *cout<<"Usted tiene "<<LJ_ye<<" años, "<<LJ_me<<" meses "<<"y "<<LJ_de<<" dias."<<endl;*
  
# Comandos para poder descargar los programas, compilarlos y asi mismo ejecutarlos en su maquina. 👩‍💻​
#### 1. Descargar los programas.
Para poder clonar o descargar los programas en la aplicacion de termux utilizamos el siguiente comando:

$ git clone (aqui se colocara el link o el codigo del repositorio) 

#### Ejemplo 
$ git clone https://github.com/JavierLu25/JavierLucas-Programacion.git

#### 2. Compilar el programa.
Para compilar un codigo de c++ en termux se utiliza el siguiente comando:

$ g++ (nombre del codigo de c++ con terminacion en .cpp) -o (nombre del codigo sin la terminación .cpp)

#### Ejemplo
$ g++ LucasJavier-SumaN.cpp -o LucasJavier-SumaN

#### 3. Ejecutar el programa.
En este caso para ejecutar el programa se utiliza el siguiente comando:

$ ./(nombre del codigo de c++)

#### Ejemplo
$ ./LucasJavier-SumaN
  
 
![la_importancia_de_dar_gracias](https://user-images.githubusercontent.com/101118941/171066707-627d6187-5e69-4709-9f65-1dc926e479a3.png)

 
  
 
  
  
