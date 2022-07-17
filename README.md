void main() {

print(calcAreaCirculo(5.0));

}
double calcAreaCirculo(double raio) => 3.14 * raio * raio;

class Pessoa {
  
  var nome;
  var idade;
  var altura;
  
  void dormir(){
    print("$nome esta dormido");
    
  }
  
  void aniver(){
    idade++;
  }
  
}

void main(){
  
  Pessoa pessoa1 = Pessoa();
  pessoa1.nome = "Joao";
  pessoa1.idade = 20;
  pessoa1.altura = 1.80;
  
  Pessoa pessoa2 = Pessoa();
  pessoa2.nome = "Raphael";
  pessoa2.idade = 15;
  pessoa2.altura = 1.66;
  
  print(pessoa1.nome);
  print(pessoa2.nome);
  
  print(pessoa1.idade);
  pessoa1.aniver();
  print(pessoa1.idade);
  
  pessoa2.dormir();
}
<!---
japa04p/japa04p is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
