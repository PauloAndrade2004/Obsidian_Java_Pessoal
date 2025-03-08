Em Java, o tipo booleano é utilizado para representar valores lógicos, ou seja, *verdadeiro* ou *falso*. 

## Tipo **boolean**

* Tamanho: O tipo boolean é otimizado pela JVM, a especificação não defini explicitamente quantos bits ele ocupa. Normalmente, em termos de implementação, ele usa 1 bits para armazenar #true ou #false.

* Valores possíveis : Ele pode ter apenas dois valores:
   * *true* : Representa verdadeiro.
   * *false* : Representa falso.

### Declaração e uso do tipo #boolean 

Um valor booleano pode ser declarado e utilizado da seguinte forma: 
```Java 
boolean flag = true;
boolean ativo = false;
```
* Declaramos uma variável *booleana* com valor *verdadeiro*.
* Declaramos uma variável *booleana* com valor *falso*.

### Operadores #Lógicos
Os operadores booleanos são muito utilizado com os operadores lógicos, que produzem resultado booleanos ( *true* ou *false* ) 
- **`&&` (E Lógico)**: Retorna `true` se ambos os operandos forem `true`.
- **`||` (OU lógico)**: Retorna `true` se pelo menos um dos operandos for `true`.
- **`!` (Não lógico)**: Inverte o valor do operando. Se o valor for `true`, se torna `false`; e se for `false`, se torna `true`.

Exemplo: 
```Java
boolean a = true;
boolean b = false;
boolean resultado;

resultado = a && b; 
resultado = a || b; 
resultado = !a;     

```

* *&&* - <span style="background:#b1ffff">Este operador retorna true se ambas as expressões forem verdadeiras</span>. Caso contrario retorna *false* 
```Java 
boolean a = true;
boolean b = false;

boolean resultado = a && b; 

//Tera como saida: False 
```

* **OR (OU) - `||`** - Este operador retorna *true* se pelo menos uma das expressões for verdadeira. Se ambas forem *falsas* , o resultado será *false*.
```Java 
boolean a = true;
boolean b = flase;
boolean resultado = a || b; // true 
```

### **NOT (NÃO) - `!`**

O operador `!` inverte o valor de uma expressão booleana. Se a expressão for `true`, ele a torna `false`, e vice-versa.

**Exemplo:**
```Java 
boolean a = true; boolean resultado = !a; // false
```

### 4. **Operadores de comparação**

Embora não sejam estritamente lógicos, os operadores de comparação também são fundamentais ao se trabalhar com lógica em Java. Eles comparam valores e retornam um resultado booleano (`true` ou `false`).

- **`==`**: Igualdade
- **`!=`**: Diferente
- **`>`**: Maior que
- **`<`**: Menor que
- **`>=`**: Maior ou igual a
- **`<=`**: Menor ou igual a

**Exemplo:**
```Java 
int x = 10; int y = 5; boolean resultado = x > y; // true
```
