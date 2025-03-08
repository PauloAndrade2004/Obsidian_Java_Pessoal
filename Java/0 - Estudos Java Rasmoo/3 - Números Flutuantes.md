Em Java, as variáveis numéricas de ponto flutuante são usadas para representar números reais e são armazenadas em tipos de dados específicos. Existem dois tipos principiais de variáveis de ponto flutuante em Java:

## Float  
* **Tamanho**: 32 bits. 
* **Precisão**: A aproximadamente 7 dígitos decimais. 
* **Formato**: Usa a notação de ponto flutuante de 32 bits. *
* **Uso**: Usamos quando a memoria é uma preocupação e a precisão não precisa ser muito alta.

Exemplo de uso:
```Java 
float numero = 3.14f;
```
Usamos o **f** para indicar que o número que digitamos e do tipo *float*.

## Double 

* **Tamanho**:  64 bits.
* **Precisão**: Aproximadamente 15 dígitos decimais.
* **Formato**:  Usa a notação de ponto flutuante de 64 bits.
* **Uso**: O tipo ***double*** é o mais comum para cálculos que exigem maior precisão, e é o tipo padrão para números de ponto flutuante em Java.

Exemplo de uso:
```Java 
double numero = 3.14159265359;
```
Não precisa de sufixo, pois o tipo de default é double.

<span style="background:#ff4d4f">Observação</span>
Eu consigo armazenar um valor Int em uma variável do tipo flutuante.