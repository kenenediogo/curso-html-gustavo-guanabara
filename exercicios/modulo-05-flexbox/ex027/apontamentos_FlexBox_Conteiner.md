# Ctrl + K; Ctrl + C -> Combinação para fazer comentário no VsCode

## Flex Conteiner - PAI: É o "Conteiner", que vai levar a configuração de

--- *"Display: Flex"*
--- *flex-wrap:* __nowrap, wrap e wrap-reverse__

## ITEM - Flex-items - FILHOS: São os blocos que estão dentro do Conteiner

--- *flex: auto;* - alinha automaticamente os blocos, isto é, distribui todos no tamanho da janela, não permite ter espaços em branco dentro do conteiner. Ele se ajusta ao tamanho do bloco, e quando não tiver mais espaço, dependendo do tipo de direção, ele segue o flex-flow. Não funciona no pai (conteiner) só no filho.

O flex: auto, quando for usar em colunas, temos que ter uma altura consideravel para ele fazer a quebra.

--- *text-align: center;*

## DIRECÇÕES E EIXOS

__flex-direction:__

Vai ser usado no conteiner, e não nos items

--- *flex-direction: row;*
--- *flex-direction: row-reverse;*
--- *flex-direction: column;*
--- *flex-direction: column-reverse*

## tipos de eixos

--- __main-axis (eixo principal):__ - gera dois pontos principais:
    - mais-start
    - main-end

--- __cross-axis:__ (eixo transversal) - gera dois pontos principais:
    - cross-start
    - cross-end

O *main-start, o main-end, o cross-star e o cross-end*, a sua posição vai depender da direção do __"main-axis e o cross-axis"__

## empacotamentos (dentro do Flex Conteiner)

__felx-wrap:__
a propriedade flex-wrap é usada no conteiner e contem as seguintes propriedades:

*nowrap*,
*wrap* e
*wrap-reverse*

__flex-flow:__
é uma propriedade short hand que junta o *flex-direction + flex-wrap*

Exemplo sem o Short-hand:
*flex-direction: row;*
*flex-wrp: norap;*

Exemplo Short-hand: substituindo os dois, vamos usar:
*flex-flow: row nowrap;*

## ALINHAMENTO NOS EIXOS (o que fazer com os ítems)

__justify-content e align-items:__ são configurados dentro do conteiner.

__justify-content:__
vai fazer o alinhamento em função do *main-axis (eixo principal)*

--- *justify-content: flex-start;* quer dizer quer o primeiro item, vai ficar colado no main-start, e se tiver um espaço no fim em branco, ele vai continuar lá mesmo, no final do main-end.

--- *justify-content: flex-end;* vai fazer o oposto do flex-start, o último ítem vai ficar colado no mai-end e o espaço em branco será no main-start.

--- *flex-content: center;* vai colocar todos os ítems no centro do conteiner, deixando espaço no main-start e no main-end de forma igual.

## propriedades de espaçamento dos items

--- *justify-content: space-between;* Vai colocar o primeiro item no main-star e o último no main-end e daí vai distribuir os ítems por igual.

--- *justify-content: space-evenly;* vai colocar os elementos dentro do conteiner de forma igual e antes e depois do ítem, os espaçamentos são iguais.

--- *justify-content: space-around;* vai pegar o número de ítems, vai dividir o conteiner pela quantidade de ítems existentes e dividir por este número, e dentro de cada divisão ele vai centralizar os items.

__align-items:__
vai fazer o alinhamento no sentido do *cross-axis (eixo transversal)*

--- *align-items: strech;* os items vão esticar (valor padrão)
--- *align-items: flex-start;* vai colar os items no princípio do cross-axis.
--- *align-items: flex-end;* vai fazer o inverso do flex-start.
--- *align-items: center;* vai colocar os items no centro.

OBS: o align items não tem as opções de espaçamento.

## ALINHAMENTO DE UM ELEMENTO AO CENTRO DO ECRÃ

Propriedade que vão ser usadas no Conteiner. independentemente do formato do conteiner o item vai ficar no meio da tela.

--- *justify-content: center;*
--- *align-items: center;*

## ALINHAMENTO DE CONTEÚDO EMPACOTADO (CONTEINER)

Alinha os elementos no eixo transversal __cross-axis__ mas quando eles estão empacotados.

--- *align-content: strech;* vai pegar o espeço todo e dividir pelo número de linhas, distribir os elementos nessas caixas divididas, e esticar os elementos.

--- *align-content: flex-start* vai colar todos os elementos na parte superior e reservar a parte em branco.

--- *align-content: flex-end* vai fazer o oposto do flex-start.
--- *align-content: center* os items vão ficar alinhados no centro.
--- *align-content: space-bwtween* vai colocar os itens de cima e colocar colado no cross start, vai pegar os items de baixo e colocar colado no cross-end e deixar o espaço do meio livre.
--- *align-content: space-evenly*
--- *align-content: space-around*
