# Projeto-flexbox-Dio
project flexbox DIO

#Ultilisados as Funcinalides

# Flex Container

● display
● flex-direction
● flex-wrap
● flex-flow

● justify-content
● align-items
● align-content

# Flex Item

● flex-grow
● flax-basis
● flex-shrink
● flex

● order
● align-self

# Flex-direction

É a propriedade que estabelece o eixo principal do container,
definindo assim a direção que os flex items são colocados no flex
container.

# Flex-wrap

É a propriedade que define se os itens devem ou não quebrar a
linha.

Por padrão eles não quebram linhas, isso faz com que os flex itens
sejam compactados além do limite do conteúdo.

# Flex-flow

É um atalho para as propriedades flex-direction e flex-wrap.

Porém seu uso não é tão comum, visto que, quando mudamos o
flex-direction para column, mantemos o padrão do flex-wrap que
é nowrap.

# Justify Content

Essa propriedade vai se encarregar de alinhar os itens dentro do
container de acordo com a direção pretendida e tratar da
distribuição de espaçamento entre eles.

OBS: caso seus itens esteja ocupando 100% de todo o container,
ela não se aplica

# Flex-grow

Define a proporcionalidade de crescimentos dos itens,
respeitando o tamanho de seus conteúdos internos.

OBS: não irá funcionar caso tenhamos adicionado justify-content
ao nosso flex container

# Flex-shrink

É a propriedade que estabelecer a capacidade de redução ou
compressão do tamanho de um item.

# Flex

Esta propriedade é um atalho ou abreviação de escrita para as
propriedades: grow, shrink e basis.

# Valores possíveis

● auto: valor padrão, irá respeitar a definição de align-items do
container
● flex-start: ao início do container
● flex-end: ao final do container
● center: relativo ao centro de acordo com o eixo
● stretch: ocupa todo os espaço relativo
● baseline: utiliza a linha base da tipografia

