## Condicionais em Java 

Em Java, permite que o fluxo do programa seja alterado dependendo do valor de uma condição. Elas são fundamentais para lógica de controle em muitos programas. Existem três formas principais de estruturas condicionais em Java:

*  if
* if-else
* switch-case

### if 
A estrutura `if` é usada para executar um bloco de código se uma condição for verdadeira. Se a condição for falsa, o código dentro do bloco `if` não será executado.

Sintaxe:
```Java 
if (condição) {
// Bloco de código a ser executado se a condição for verdadeira.
}
```

Exemplo:
```Java
int numero = 10;

if (numero > 10) {
System.ouy.println("Olá, tudo bem");
}
```


### if-else 
A estrutura *if-else* faz com que nosso código execute um bloco de código caso a condição for verdadeira é caso tenha uma condição falsa ele também será executado.

Sintaxe: 
```Java 
if (Condição) {
// Bloco de códigoa ser executado se a condição for (verdadeira).
} else {
// Bloco de código a ser executado, caso a condição seja (falsa).
}
```

Exemplo:
```Java 
int numero = 10;

if (numero > 10){

System.out.println("Número é maior que: " + numero);

}else {
System.out.println("O numero é menor que: " + numero);
}
```


### if-else if-else
Utilizamos a estrutura `if-else if-else` quando temos diversas condições a serem verificadas, com isso podemos testar diversas condições sequenciais. *Adicionamos uma primeira condição é dentro da condição adicionamos alguma ação a ser executada pelo caso se torne verdadeira.* É segue dessa mesma forma para as demais if-else.

Sintaxe:
```Java 
if (condição) {

} else if(Condição 2) {

}else if(Condição 3) {

} else {

}
``` 

Exemplo:
```Java 
int numero = 0;

if (numero > 0) {
    System.out.println("O número é positivo.");
} else if (numero < 0) {
    System.out.println("O número é negativo.");
} else {
    System.out.println("O número é zero.");
}

```


### Switch-Case
A estrutura  `switch-case` é uma alternativa ao uso de várias instruções `if-else if` quando se tem muitas condições baseadas em valores fixos ( *números inteiros* ou *strings*).
Com isso podemos comparar variáveis e executar diferentes blocos de código dependendo do valor dessa variável.

Sintaxe: 
```Java 
switch (variável) {
    case valor1:
        // Bloco de código para valor1
        break;
    case valor2:
        // Bloco de código para valor2
        break;
    
    default:
        // Bloco de código se nenhum valor coincidir
}

```

Exemplo 1:
```Java 
int dia = 3;

switch (dia) {
    case 1:
        System.out.println("Segunda-feira");
        break;
    case 2:
        System.out.println("Terça-feira");
        break;
    case 3:
        System.out.println("Quarta-feira");
        break;
    case 4:
        System.out.println("Quinta-feira");
        break;
    case 5:
        System.out.println("Sexta-feira");
        break;
    case 6:
        System.out.println("Sábado");
        break;
    case 7:
        System.out.println("Domingo");
        break;
    default:
        System.out.println("Dia inválido");
}

```
Neste exemplo: 
* O código está relacionado a dias da semana.
* O usuário criou uma variável do tipo *int*  chamada *dia*. 
* O usuário atribuiu a essa variável um número. Ex: *3* 
 Saída no terminal:
 ```Java 
 Quarta-feira
```

<span style="background:#ff4d4f">Observação:</span>
* O *break* está sendo usado para interromper a execução do código após um dos casos ser executado. Assim evitando que o programa continue verificando os casos seguintes.