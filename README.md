# operadores em javaScript e algumas execuçoes em html

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

Operadores de atribuição:
* `=` -> Atribui um novo valor para uma `var`,`let` ou `const`.
* `+=` -> Atribuição do proprio valor somando ao novo valor. 
* `-=` -> Atribuição do proprio valor subtraindo ao novo valor. 
* `*=` -> Atribuição do proprio valor multiplicando ao novo valor.
* `/=` -> Atribuição do proprio valor dividindo ao novo valor. 
* `**=` -> O próprio valor elevado à pontencia de novo valor.
* `%=` -> O resto da divisão do proprio valor pelo novo valor.
* `++` -> O próprio valor **incrementando (somado) com 1** (pode ser um _pré-incremento_ ou _pós-incremento_).  
* `--` ->O próprio valor **decrementando (subtraindo) com 1** (pode ser um _pré-decremento_ ou _pós-decremento_).