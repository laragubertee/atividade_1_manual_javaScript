# Manual De JavaScript

## Introdução
# O que é JavaScript.
JavaScript é uma linguagem de programação que permite a você implementar itens complexos em páginas web, toda vez que uma página da web faz mais do que simplesmente mostrar a você informação estática, mostrando conteúdo que se atualiza em um intervalo de tempo, mapas interativos ou gráficos 2D/3D animados, etc.



# Para que ele serve.
Criar conteúdo dinâmico
Atualizar elementos da página em tempo real
Controlar vídeos, áudios e animações
Responder às ações do usuário (cliques, teclas, etc.) 



# Como ele complementa HTML e CSS.
Complementa o HTML e o CSS ao transformar páginas web estáticas em experiências interativas e dinâmicas. Enquanto o HTML define a estrutura e o CSS anm  aparência, o JavaScript manipula ambos em tempo real, permitindo que o site responda a ações do usuário.


# Formas de uso no HTML
## JavaScript escrito dentro da própria página HTML.
JavaScript pode ser incorporado diretamente em um arquivo HTML usando a tag <script>
## JavaScript em arquivo separado (script.js).
Utilizar JavaScript em um arquivo separado (.js)



# Variáveis, tipos e escopo
## O que é uma variável;
Uma variável é um símbolo, nome ou espaço de armazenamento que representa um valor que pode mudar ou ser alterado, sendo fundamental em diversas áreas como matemática, estatística e programação.


## Como declarar variáveis em JavaScript;
Em JavaScript podemos declarar variáveis de duas formas: atualmente, com let ou var, sendo let a forma recomendada. 


## Diferença entre var, let e const;
Variáveis de var podem ser atualizadas e declaradas novamente dentro de seu escopo (região do código). Esse tipo de variável existe desde o começo na linguagem JavaScript.
As variáveis de let podem ser atualizadas, mas não podem ser declaradas novamente.
As variáveis de const não podem ser atualizadas nem declaradas novamente (são utilizadas para valores constantes, como o valor de pi, por exemplo).


## Quando cada uma pode ser usada;
Enquanto var e let podem ser declarados sem serem inicializadas, variáveis declaradas com const devem ser inicializadas no momento da declaração.


## O que é escopo global;
Em JavaScript, o escopo global é o escopo mais amplo disponível. Variáveis ​​declaradas no escopo global são acessíveis de qualquer lugar no seu código, seja dentro de funções, instruções condicionais, loops ou outros blocos de código.
## O que é escopo de função;
No escopo de função, as variáveis ​​declaradas dentro da função, somente serão acessadas por dentro da função, não sendo possível acessá-las do lado de fora.
No escopo de função, esse comportamento acontece independente da palavra chave usada na criação da variável ou constante, var, letou const.

## O que é escopo de bloco.
Em JavaScript, o escopo de bloco é como uma série de caixas aninhadas dentro de um contêiner maior, cada uma com seu próprio conjunto de variáveis.
Ao contrário dos escopos global e local, que são definidos por funções ou contexto global, o escopo de bloco é criado dentro de blocos de código específicos, como instruções condicionais (if, else, switch) e loops (for, while).

# Operadores, comparações e lógica

## operadores aritméticos principais;
Os operadores aritméticos padrão são os de soma (+), subtração (-), multiplicação (*) e divisão (/)
O Módulo (%) é o operador que foca no que sobra, retornando apenas o resto inteiro de uma divisão entre dois números.
O Incremento (++) adiciona uma unidade ao valor. Se colocado antes da variável, ele soma e já entrega o valor novo; se colocado depois, ele entrega o valor atual e só soma depois.
O Decremento (--) funciona de forma idêntica ao incremento, mas subtraindo uma unidade. Ele também muda o momento da entrega do valor dependendo de sua posição (antes ou depois da variável).
A Negação (-) serve para inverter o estado numérico, transformando um valor positivo em negativo ou vice-versa.
A Adição Unária (+) tem o papel principal de tentar converter o que vem logo após ela em um número, sendo muito usada para transformar textos numéricos em números reais.
A Exponenciação ()** trata de potências, onde o primeiro número é a base e o segundo é o expoente, calculando o resultado dessa elevação.


## Operadores relacionais principais;
Um operador relacional compara seus operando e retorna um valor booleano baseado em se a comparação é verdadeira;
IN: Retorna verdadeiro se a propriedade específica estiver no objeto especificado


## Operadores lógicos principais;
AND Lógico (&&)
O operador "E" foca na primeira falha ou no último sucesso(retorna verdadeiro caso ambos operandos sejam verdadeiros; caso contrário, retorna falso.)
OU Lógico (||)
O operador "OU" foca no primeiro sucesso(retorna verdadeiro caso ambos os operandos sejam verdadeiros; se ambos forem falsos, retorna falso.)
NOT Lógico (!)
O operador de Negação inverte o estado( Retorna falso caso o único operando possa ser convertido para verdadeiro; senão, retorna verdadeiro.)


## diferença entre == e ===;
== : Compara se os valores são iguais, realizando conversão de tipo automaticamente. Ex: 1 == '1' é true.
===:  Compara se valor e tipo são idênticos. Ex: 1 === '1' é false porque um é number e outro é
## diferença entre != e !==.
!= (Diferente): Compara se dois valores são diferentes, mas realiza a coerção de tipo (converte os tipos para comparar).
!== (Estritamente Diferente): Compara se dois valores são diferentes ou se são de tipos diferentes. Não realiza conversão automática.

