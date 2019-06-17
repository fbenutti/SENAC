# Aulas Programador de Dispositivos Móveis
## Aula Funções

Ensinando a criar função através de um exemplo de uma calculadora

```dart
void main() {
  print('Minha calculadora =) \n---------------');
  String operacao = "+";
  print('A operação que vamos fazer: $operacao \n\n');
  
  int n1 = 10;
  int n2 = 5;
  
  print('Quanto é $n1 $operacao $n2?');
  
  int resposta = n1 + n2;
  
  print("A resposta é: $resposta");
  
}

// E SE EU QUISER FAZER TODAS AS OPERAÇÕES DE UMA SÓ VEZ?
void main() {
  print('Minha calculadora =) \n---------------\n');
  
  double n1 = 10;
  double n2 = 5;
  
  //E é assim que a gente chama uma função
  calcular(n1, n2, "+");
  calcular(n1, n2, "-");
  calcular(n1, n2, "/");
  calcular(n1, n2, "*");
  
}

/*Como cria uma função?

primeiro vem o retorno
depois o nome da função
depois, entre parentese, os paremetros (pode ter ou não!)
Por último, dentro das chaves, o que a função faz, ou seja, o corpo da função

IMPORTANTE: só criar a função não serve para nada. 
A gente tem que chamar ela em algum lugar
*/

void calcular(double n1, double n2, String operacao){
    print('Quanto é $n1 $operacao $n2?');
    double resposta;
    
    if (operacao == "+") {
    	 resposta = n1 + n2;
    } else if (operacao == "-") {
      resposta = n1 - n2;
    } else if (operacao == "/") {
      resposta = n1 / n2;
    } else if (operacao == "*") {
      resposta = n1 * n2;
    } else {
      resposta = 0;
    }
  
    print("A resposta é: $resposta\n");
  }
```

## Aula Flutter

**Primeiro contato:**

Entrar em flutter.dev (ou flutter.io) e procurar o local para começar a utilizar o flutter (Get Started)
Seguir os passos de instalação, que constituem basicamente de:
 - Baixar o SDK do Flutter e colocá-lo na pasta "C:\src\flutter"
 - Baixar e instalar o Android Studio
 - Configurar o plugin do flutter no Android Studio
 - Rodar o comando "flutter doctor" no Prompt de Comando para certificar que está tudo ok.


**Criação do primeiro App**

Regra nº1: **Após aberta, nunca feche a máquina virtual**

1. Abrir o Android Studio
2. Abrir a Máquina Virtual (emulador do Android)
3. Apertar o botão "Start new Flutter Project" (iniciar novo projeto do flutter)
4. Escolher Aplicativo Flutter
5. Colocar o nome do projeto, descrição, e o caminho do SDK.
6. Nome da empresa (não mudou nada)






