## O que é CSS?


### Qual a diferença entre utilizar HTML e CSS?
  * As quatro principais diferenças são: 
    A quantidade de possibilidades de alteração de estilo. 
    Um estilo pode ser aplicado para varios elementos. 
    Os estilos do CSS pode ser aplicado usando o sistema de herança.
    Os estilos podem ser guardados em cache, agilizando o paint da view.


### Comente sobre a declaração da sintaxe CSS.
  * O CSS pode ser aplicado nos elementos HTML por ID ou CLASS.
  CSS pode ser escrito em um arquivo .css com a seguinte sintaxe:
    div {
      height: 100vh;
      width: 100vw;
      padding: 10vh;
    }
  
    #id {
      height: 100vh;
      width: 100vw;
    }
    
    .class {
      padding: 10vh;
    }
  Também pode ser escrito no elemento STYLE do HTML:
  <style>
    div {
      height: 100vh;
      width: 100vw;
      padding: 10vh;
    }
  
    #id {
      height: 100vh;
      width: 100vw;
    }
    
    .class {
      padding: 10vh;
    }
  </style>
  Ou escrito na propriedade style do elemento HTML:
  <div style="height: 100vh; width: 100vw; padding: 10vh;"></div>


### O que é seletor, propriedade e valor para CSS?
  *Seletor é o #id, .class ou (elemento html) que faz a seleção de em qual elemento HTML aquele estilo será aplicado.
  Propriedade é o estilo que será aplicado naquele seletor: height, width, background-color, transform, etc.
  Valor é o valor que irá definir a alteração que a propriedade fará naquele seletor.


### O que é seletor CLASS para CSS?
  *É o seletor que define a base de estilos de um conjunto de elementos HTML.


### Comente sobre o seletor ID.
  *É o seletor aplicado para um caso especifico de elemento HTML.


### O que é a regra de precedência de seletores para CSS?
  *Seletor CLASS deve ser utilizado para um estilos de um conjunto de elementos HTML e o seletor ID deve utilizado para casos especificos de estilos de um ou mais elementos HTML.


### O termo BOX MODEL é utilizado em CSS quando?
  * É utilizado para quando se fala em design e layout.
  
  
### Comente sobre BORDER, PADDING, MARGIN para CSS.
  * PADDING é uma area limpa que vai ao redor do elemento HTML.
  BORDER é uma borda que vai ao redor do PADDING.
  MARGIN é uma area limpa que vai ao redor do BORDER.
  
  
### Qual é a propriedade que altera a largura e a altura em CSS?
  *Para alterar a altura é utilizado HEIGHT, enquanto para alterar a largura é utilizado WIDTH.
  
  
### Comente sobre a utilização do FLOAT em CSS.
  *Ajusta a posição de um elemento HTML em TOP, RIGHT, BOTTOM, LEFT.
