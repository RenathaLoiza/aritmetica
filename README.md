# operadores em javaScript e execultando alguns no HTML

Aprendendo a utilizar operadores na linguagem JavaScript


Inicialmente, declaramos as variaveis com a palavra `const` em exercicios variados 

~~~js
const num1 = 30;
const num2 = 20;
~~~

Depois realizamos as operações utilizando os operadores aritmeticos:

* `+`: Soma de dois números. 
* `-`: Subtração de dois números. 
* `/`: Divisão de dois números. 
* `*`: Multiplicação de dois números. 
* `%`: Obter o resto de uma divisão de dois números. 
* `**`: Potenciação

Depois realizamos alguns execicios de calculo de média 

~~~js
const nota1 = 4;
const nota2= 6;
const nota3= 4.6;
const aluno= "carlos";
~~~

* `-`: subtração de dois números.
* `/`: divisão de dois números.


Realizamos a interpolação e a concatenação de string


## interpolação 
~~~js
console.log(`meu carro é ${corDoCarro} e o seu modelo ${modeloDoCarro} da marca ${marcaDoCarro} e possui o chassi ${chassiDoCarro} e o seu ano ${anoDoCarro}`);
~~~

## concatenação
~~~js
console.log("meu carro é ",corDoCarro , "e o seu modelo" ,modeloDoCarro,"da marca ",marcaDoCarro,"e possui o chassi",chassiDoCarro,"e o seu ano",anoDoCarro);
console.log("meu carro é "+ corDoCarro +" e o seu modelo " + modeloDoCarro +" da marca "+ marcaDoCarro + " e possui o chassi "+ chassiDoCarro + " e o seu ano " + anoDoCarro);
~~~
## litearal templates
~~~js
console.log(`bem vindo ao bar do programador
1- mainDrinks
2- pitão_python
3- noMeuPcFunciona
4- SemPontoEVirgula
`);
~~~

~~~js
let num = 10;
~~~
Declaramos a variavel `num` usando a palavra reservada `let`, pois essa variavel sera reatribuida ao longo do código.
em seguida, fazemos uma serie de reatribuições utilizando operadores de atribuição.

~~~js
console.log(`soma : ${num+=10}`);
console.log(`subtração :${num-=10}`)
console.log(`multiplicação :${num*=10}`);
console.log(`divisão :${num/=10}`);
console.log(`elevando a potencia :${num**=10}`);
console.log(`resto de 10 é :${num%=10}`);
console.log(`incrementando um: ${++num}`);
console.log(`decrementando um:${--num}`);
console.log(`numero final é: ${num}`);
~~~

## Operadores de atribuição:
* `=` -> Atribui um novo valor para uma `var`,`let` ou `const`.
* `+=` -> Atribuição do proprio valor somando ao novo valor. 
* `-=` -> Atribuição do proprio valor subtraindo ao novo valor. 
* `*=` -> Atribuição do proprio valor multiplicando ao novo valor.
* `/=` -> Atribuição do proprio valor dividindo ao novo valor. 
* `**=` -> O próprio valor elevado à pontencia de novo valor.
* `%=` -> O resto da divisão do proprio valor pelo novo valor.
* `++` -> O próprio valor **incrementando (somado) com 1** (pode ser um _pré-incremento_ ou _pós-incremento_).  
* `--` ->O próprio valor **decrementando (subtraindo) com 1** (pode ser um _pré-decremento_ ou _pós-decremento_).

  ## operadores-comparacao.js

Neste arquivo conhecemos os operadores de comparação e a estrutura lógica de decisão **if-else**.

~~~js
if (condicao) { 
    console.log('VERDADEIRO'); 
} else {
    console.log('FALSO');
}
~~~

Esta estrutura exibe no console se a condição testada é `true` (verdadeira) ou `false` (falsa). A condição armazena o resultado da **comparação entre duas variáveis**, como segue:

~~~js
const a = 'a', b = 'A';
const condicao = a == b;
~~~

### Operadores de comparação:

* `==`  -> é igual
* `!=`  -> _não_ é igual
* `>`   -> maior que
* `<`   -> menor que
* `>=`  -> maior OU igual
* `<=`  -> menor OU igual
* `===` -> é estritamente igual (valor **E** tipo)
* `!==` -> _não_ é estritamente igual (valor **OU** tipo)

## desafio1.js

Escreva um código em JavaScript que resolva o problema descrito no livro **Lógica de Programação I, p. 20**, em que temos que obter as 3 notas de um aluno, calcular a média e exibir se o aluno foi aprovado, reprovado ou se ficou para exame. Não é necessário ler as notas, você pode defini-las com variáveis.

Você precisará utilizar uma estrutura de decisão composta, como a seguir:

~~~js
if (condicao1) {
    // código da condição 1
} else if (condicao2) {
    // código da condição 2
} else {
    // código se nenhuma das condições for verdadeira
}
~~~

## desafio2.js

Crie um programa que calcule o Índice de Massa Corporal (IMC) de uma pessoa. 

Orientações: 
* Utilize o método `prompt()` do objeto `window` para realizar a leitura dos dados de entrada.
* Utilize a fórmula **IMC = peso / altura²** para calcular o IMC.
* Utilize a estrutura **if-else** para classificar o IMC de acordo com a tabela da OMS:

IMC | Indicação
----- | -----
Abaixo de 18,5	| Abaixo do peso
18,5 - 24,9	| Peso normal
25,0 - 29,9	| Sobrepeso
30,0 - 34,9	| Obesidade grau I
35,0 - 39,9	| Obesidade grau II
Acima de 40,0 |	Obesidade grau III

Observações:

O IMC é apenas uma medida geral e não leva em consideração a composição corporal (músculos versus gordura).
Pessoas com muita massa muscular podem ter um IMC alto, mesmo que não sejam obesas.
É importante consultar um médico ou nutricionista para uma avaliação individualizada.

Para mais informações:

Organização Mundial da Saúde (OMS): <https://www.who.int/news-room/fact-sheets/detail/obesity-and-overweight>

## desafio3.js

Crie um conversor de temperatura entre as escalas Celsius, Fahrenheit e Kelvin. O usuário deve digitar a temperatura a ser convertida, a escala da temperatura atual e a escala para o qual o valor deve ser convertido.

Entradas (3): valor atual da temperatura, escala atual da temperatura, escala para exibição (conversão).

Saída (1): valor convertido na escala de conversão.

### Fórmulas:

De | Para | Fórmula
--- | --- | ----
Celsius | Fahrenheit | tF = (tC * 9/5) + 32
Celsius | Kelvin | tK = tC + 273.15
Fahrenheit | Celsius | tC = (tF - 32) * 5/9
Fahrenheit | Kelvin | tK = (tF + 459.67) * 5/9
Kelvin | Celsius | tC = tK - 273.15
Kelvin | Fahrenheit | tF = tK * 9/5 - 459.67

### Problema adicional

Como executar dois "programas" na mesma página?


