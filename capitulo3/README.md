# Algoritimos e estrutura de dados

Este capitulo será um dos capitulos mais importante do nosso estudo, porque este capitulo estudaremos sobre algoritimos e estrutura de dado. No primeira capitulo nós vimos sobre a introdução das linguagens de programação penso que até este momento todos percebem o que é uma linguagem de programação e a linguagem de programação que vamos usar é o JavaScript.

# O que aprender neste capitulo

- Introdução a algoritemo e Estrutura de dados
- Introdução a JavaScript
- O ambiente de programação JavaScript
- Boas práticas de programação na linguagem Javascript
- Declaração e inicialização de variaveis
- Bibliotecas de funções Matemáticas em JavaScript
- Fluxo de deicisão
- Construções de repetições
- Funções
- Escope de variaveis
- Recursão
- Objectos e Programação orientada a objectos
- Parte II

# Introdução a Algoritimo e Estrutura de dados

Durante o desenvolvimento de um software, cada método que será utilizado deve ser analisado, deve-se verificar sua complexidade e seus impactos no desempenho. Deve-se saber o que será mais importante, a velocidade ou a estabilidade.

Se uma coleção de dados está salva na memória, provavelmente essas informações serão usadas posteriormente, para isso precisaram ser recuperadas e para o fim utiliza - se os métodos de busca. Quando os dos dados encontra-se já ordenados o processo de busca se torna muito eficiente, então ordenar uma coleção de elementos torna-se muito importante. Embora se tenha muitos métodos que ealiza essa tarefa, existem uma diferença muito grande entre eles, principalmente em relação ao desempenho. Além disso, essa coleção de dados tem que estar organizada. A organização de uma coleção de dados pode ser feita através de vetores estáticos ou listas dinâmicas dali que vem o topico algoritimo e estrutura de dados.

# Algoritmo e Implementação

Embora as vezes não percebemos, utilizamos algoritmos no nosso dia-a-dia e não sabemos. Para a execução de alguma tarefa ou mesmo resolver algum problema, muitas vezes inconscientemente executamos algoritmos. Mas o que é Algoritmo?

Algoritmo é simplesmente uma "receita" para executarmos uma tarefa ou resolver algum problema. E como toda receita, um algoritmo também deve ser finito. Se seguirmos uma receita de bolo corretamente, conseguiremos fazer o bolo. A computação utiliza muito esse recurso, então se você pretende aprender programação, obviamente deve saber o que é algoritmo.

Podemos conferir abaixo um exemplo de algoritimo de trocar uma lâmpada:

para trocar uma lâmpa seguimos o seguinte algoritimo

1. Verificar se o interroptor não está desligado
2. Se o interroptor não estiver disligado então pegamos numa escada
3. Colocamos a escada em direção da lâmpa e enroscamos a lâmpa até ficar solta
4. Substituimos por outra lâmpada que funcione
5. Descemos da escada
6. Testamos a nova lâmpa ligando o interroptor
7. Se acender fim algoritimo caso não faça de novo

# Estrutura de dados e Implementação

Computadores são máquinas que manipulam dados e informações. A computação abrange o estudo da forma como as informações são organizadas, manipuladas e utilizadas em um computador.

Ao desenvolver um programa para realizar o processamento de dados, é preciso transcrever de forma que o computador possa compreender e executar tal programa e que o programador também compreenda o que escreveu. As linguagens de programação são códigos escritos em uma linguagem que o programador compreende e que o computador consegue interpretar e executar.

As estruturas de dados mais simples que se conhece são os **vetores** e **matrizes**. Estas estruturas de dados são estruturas de dados homogêneos pois permitem o armazenamento de dados de um único tipo de dado. Elas permitem acesso direto a um elemento através do nome do vetor/matriz seguido do índice. Permitem também o acesso sequencial, percorrendo elemento a elemento do vetor/matriz.

Entretanto existem outras estruturas de dados mais complexas e que são usadas para representar de forma organizada arranjos de dados específicos. Existem as seguintes estruturas de dados:

- **Lista** - Uma Lista é uma estrutura de dados que é composta por nós, elementos, que apontam para o próximo elemento da lista, o ultimo elemento apontará para nulo. Para compor uma lista encadeada, basta guardar seu primeiro elemento

- **Fila** - As filas são estruturas de dados baseadas na idéia de que o primeiro elemento a entrar na pilha é o primeiro elemento a sair. Esta idéia é conhecida como princípio FIFO (first in, first out), em que os elementos que foram inseridos no início são os primeiros a serem removidos. Uma fila possui duas funções básicas que são adicionar elemento ao final da fila e remover o elemento que está no inicio da fila.

- **Árvore** - Uma árvore é uma estrutura de dados em que cada elemento tem um ou mais elementos associados. Uma árvore possui apenas uma raiz. Em uma árvore os elementos associados a cada nó da árvore são habitualmente chamados de filhos desses nós. Os nós sem filhos de uma árvore são chamados de folhas.

- **Grafo** - Um grafo é uma estrutura de dados composta por um conjunto de vértices e um conjunto de arrestas. Sendo que cada arresta é representada por um par de vértices.

# Introdução ao JavaScript

Nesta sessão do nosso curso introduziremos a linguagem principal que estaremos usando, ela chama - se JavaScript, em primeiro lugar, o termo javaScript nada tem haver com a linguagem de programação Java, as vezes faz - se muita confusão em torno destas duas linguagem que o que mais têm em comum é o nome Java, apsar que essa confusão é mais notória entre os iniciantes.

# JavaScript e a especificação ECMAScript

Algum tempo atras o JavaScript foi originalmente chamado assim com este nome, aproveitando a boa fama do Java na época isso ajudaria de certa forma e como ajudou a tornar o JavaScript famoso aproveitando a assim buleia do nome Java. Então a Netscape enviou JavaScript para a organização que padroniza informações, conhecida como ECMA International for Standardization. Isso resultou em um novo padrão de idioma, conhecido como ECMAScript.

Simplificando, o ECMAScript é um padrão. Enquanto o JavaScript é a implementação mais popular desse padrão. O JavaScript implementa o ECMAScript e constrói em cima dele, essa evolução trouxe algumas nomeclatura tais como:

- ES1 junho de 1997
- ES2 junho de 1998
- ES3 dezembro de 1999
- ES4 Abandonado
  as versões mais recentes
- ES5 Dezembro 2009
  agora as actualizações são anuais
- ES6 / ES2015
- ES2016 (ES7)
- ES2017 (ES8)

# O ambiente de programação JavaScript

O JavaScript tem sido historicamente uma linguagem de programação que era executada apenas dentro de um navegador web ou se preferir um browser. No entanto, nos últimos anos, houve o desenvolvimento de ambientes de programação JavaScript que podem ser executados a partir de um PC, ou similarmente, de um servidor. Neste curso usaremos o nagegador como também quem quiser pode configurar o node js em sua máquipa dará na mesma, só que o NodeJs não está no escopo deste curso.

# Como executar um código JavaScript

Daqui em diante nos consentraremos só nos código depois deste esclarecimento alias para quem quiser haverá o código fonte de cada sessão de código que teremos aqui no curso, então sem vamos ao esclarecimento de como executar um código JavaScript:

Em primeiro lugar crie uma pasta com o nome que você quiser no nosso caso vamos chama - lo de `curso-introdutorio-de-programacao`, dentro da pasta crie outra pasta com o nome `capitulo3` e lá crie uma pasta com o nome `pro01` dentro desta pasta criar dois ficheiro um se chama `index.html` e outro se chama `app.js` se tudo deu certo abra o teu editor de código o meu é o vscode e vamos ao código.

**index.html**

```html
<!DOCTYPE html>
<head>
    <title>app 01</title>
</head>
<body>
    <script src="app.js"></script>
</body>
</html>
```

abra o ficheiro `app.js` e degite o seguinte código

```javascript
console.log("olá mundo...");
```
