#include <iostream>
using namespace std;



int main(int argc, char** argv) {
	int pessoa1, pessoa2, pessoa3, pessoa;
	float media;
	
	cout << "Digite a idade da pessoa 1: ";
	cin >> pessoa1;
	cout << "Digite a idade da pessoa 2: ";
	cin >> pessoa2;
	cout << "Digite a idade da pessoa 3: ";
	cin >> pessoa3;
	
	if (pessoa1 >=10 && pessoa1 < 100 && pessoa2 >=10 && pessoa2 < 100 && pessoa3 >=10 && pessoa3 <100){
		cout << "As idades estao dentro do intervalo.\n";
	}
	else{
		cout <<"As idades estao fora do intervalo.\n";
	}
	
	media = (pessoa1 + pessoa2 + pessoa3) /3;
	cout << "A media de idades e: " << media << endl;
	
	
	if(media < 25){
		cout << "A turma e jovem.\n ";
		
	}
	else if(media >=26 && media <=60){
		cout << "A turma e adulta.\n ";
	
	}else{
	cout << "A turma é senior.\n";
}
	
	
	
	
	
	
	return 0;
}
