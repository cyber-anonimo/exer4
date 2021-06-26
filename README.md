# exer4

#include<iostream>
#include<string>
using namespace std;

void quadrado(float lado){
	float area = lado * lado;
	float perimetro = lado * 4;
	
	cout << "figura geometrica: quadrado \n";
	cout << "area:" << area << "\n";
	cout << perimetro << "\n";
	
}

void retangulo(float base, float altura){
	float area = base * altura;
	float perimetro = (base + altura) * 2;
	
	cout << "figura geometrica: retangulo \n";
	cout << "area:" << area << "\n";
	cout << perimetro << "\n";
}
  
void triangulo(float base, float altura){
	float area = (base * altura) / 2;
	float perimetro = base + (altura * 2);
	
	cout << "figura geometrica: triangulo \n";
	cout << "area:" << area << "\n";
	cout << "perimetro:" << perimetro << "\n";
}
	
void circulo(float diametro){
	float pi = 3.1415;
	float area = pi * (diametro / 2);
	float perimetro = (2 * pi) + (diametro * 2);
	
	cout << "figura geometrica: circulo \n";
	cout << "area:" << area << "\n";
	cout << perimetro << "\n";
}
  
	int main(){
		quadrado(6.4);
		retangulo(5.3, 9);
		triangulo(2.3, 4);
		circulo(6);
system("pause");
return 0;
	}
	
	
	
	
