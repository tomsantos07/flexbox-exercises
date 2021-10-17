-------------------------------
0-flex-grow.html
Flex grow: define a proporcionalidade de crescimento dos itens, respeitando o tamanho de seus conteúdos internos.

Obs: não irá funcionar caso tenha sido adicionado justify-content ao flex-container.

-------------------------------
1-flex-basis.html
Flex Basis: estabelece o tamanho inicial do item antes que ocorra a distribuição do espaço restante dentro dele, usando como base, o conteúdo interno disposto.

Valores possíveis
* auto: caso o item não tenha tamanho, este será proporcional ao conteúdo do item.
* , %, em, ...: são valores exatos previamente definidos.
0 (zero): se relaciona com a definição do flex-grow.

-------------------------------
2-flex-shrink.html
Flex-shrink é a propriedade que estabelece a capacidade de redução ou compressão do tamanho de um item.

-------------------------------
3-flex.html
Flex: é um atalho ou abreviação de escrita para as propriedades grow, shrink e basis.

-------------------------------
4-order.html
Order: lida diretamente com a ordenação dos items.

-------------------------------
4-align-self.html
Align Self: estabelece o alinhamento de modo individual sobre um determinado item.

Valores possíveis:
* auto: valor padrão - respeita a definição de align-items do container;
* flex-start: ao início do container;
* flex-end: ao final do container;
* center: relativo ao centro de acordo com o eixo;
* stretch: ocupa todos os espaços relativos;
* base-line: utiliza a linha base da tipografia.