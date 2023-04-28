#include <bits/stdc++.h>
using namespace std;
float aumentodesueldo(float a,float b,float c,float d,float e,float f,float g,float h,float i,float sueldo);
int main (){
	float sueldo,a,b,c,d,e,f,g,h,i;
	
    cout<<"Ingrese su sueldo mensual: "<<endl;
    cin>>sueldo;
    
    cout<<aumentodesueldo(a,b,c,d,e,f,g,h,i,sueldo)<<endl;
	
	return 0;
}

float aumentodesueldo(float a,float b,float c,float d,float e,float f,float g,float h,float i,float sueldo){

    if(sueldo<40000){
    	a=15*sueldo/100;
    	e=a+sueldo;
    cout<<"Se le agregara un 15% de comision. Que es igual a: "<<a<<endl;
	
	cout<<"El aumento mas el sueldo es igual a: "<<e<<endl;
	}
	
	else if(sueldo>=40001 && sueldo<80000){
		b=12*sueldo/100;
		f=b+sueldo;
	cout<<"Se le agregara un 12% de comision. Que es igual a: "<<b<<endl;
	
	cout<<"El aumento mas el sueldo es igual a: "<<f<<endl;
	}

	else if(sueldo>80001 && sueldo<=12000){
	    c=10*sueldo/100;
	    g=c+sueldo;
	cout<<"Se le agreagara un 10% de comision. Que es igual a: "<<c<<endl;
	
	cout<<"El aumento mas el sueldo es igual a: "<<g<<endl;
	}
	
	else if(sueldo>120001 && sueldo<=200000){
		d=7*sueldo/100;
		h=d+sueldo;
	cout<<"Se le agregara un 7% de comision. Que es igual a: "<<d<<endl;
	
	cout<<"El aumento mas el sueldo es igual a: "<<h<<endl;
	}
		else if(sueldo>200001){
		d=4*sueldo/100;
		h=d+sueldo;
	cout<<"Se le agregara un 4% de comision. Que es igual a: "<<d<<endl;
	
	cout<<"El aumento mas el sueldo es igual a: "<<h<<endl;
	}
	return a,b,c,d,e,f,g,h,i;
}
