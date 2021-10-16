# flexbox-exercises
Flexbox training

-----------------------------------
1-display-flex.html

Objetivos:
1- entender o comportamento padrão horizontal de um flex container.
2- Aprender a modificar a orientação horizontal.

Definição: Flex-direction é a propriedade que estabelece o eixo principal do container definindo assim a direção em que os flex items são colocados no flex container. (são 2 eixos: linha: horizontal, coluna: vertical)

Row(padrão): à direção do texto, esquerda p/ direita
row-reverse: sentido oposto à direção do texto
column: ordenação de cima pra baixo
column-reverse: ordenação inversa de baixo pra cima

-----------------------------------
2-flex-wrap.html
* Flex Wrap é a propriedade que define se os itens devem ou não quebrar a linha.
* Por padrão eles não quebram linhas. Isso faz com que os flex items sejam compactados além do limite do conteúdo.

nowrap: é o comportamento padrão e não permite a quebra de linha.
wrap: permite a quebra de linha assim que um dos flex items não puder mais ser compactado.
wrap-reverse: permite a quebra de linha assim que um dos flex items não puder mais ser compactado, porém, ele joga o item pra cima e não pra baixo! (estranho né hauhuah)

-----------------------------------
3-flex-flow.html
Flex-flow: é um atalho para as propriedades flex-directions e flex-wrap.
Seu uso não é muito comum, visto que quando mudamos o flex-direction para column, mantemos o padrão do flex-wrap que é o nowrap.

-----------------------------------
4-justify-content.html
Justify content: alinha os itens dentro do container de acordo com a direção pretendida e trata da distribuição de espaçamento entre eles.

* Se os itens estiverem ocupando 100% de todo o container, justify content não se aplica.

Variações
* flex-start: início do container;
* flex-end: final do container;
* center: ao centro do container;
* space-between: cria um espaçamento igual entre os elementos;
* space-around: os espaçamentos do meio são duas vezes maiores que o inicial e final.

-----------------------------------
5-align-items.html
Align-items: trata do alinhamento dos flex items de acordo com o eixo do container.
O alinhamento dos itens se estiverem em linha ou em coluna será diferente.
Permite o alinhamento central no eixo vertical.

Tipos de alinhalmento do align-items:
* center: alinhamento dos itens no centro;
* stretch: padrão - os flex-items crescem igualmente;
* flex-start: alinhamento dos itens no início;
* flex-end: alinhamento dos itens no final;
* baseline: alinhamento de acordo com a linha base da tipografia od itens

-----------------------------------
6-align-content.html
Align Content: é responsável por tratar o alinhamento das linhas do container em relação ao eixo vertical do container.

Observações importantes?
* O container deve utilizar quebra de linhas;
* A altura do container deve ser maior que a soma das linhas dos itens.

Tipos de alinhamento:
* center: alinhamento dos itens ao centro;
* stretch: é o padrão e os flex-items crescem igualmente;
* flex-start: alinhamento dos itens no início;
* flex-end: alinhamento dos itens no final;
* space-between: cria um espaçamento igual entre os elementos;
* space-around: os espaçamentos do meio são duas vezes maiores que o inicial e o final.