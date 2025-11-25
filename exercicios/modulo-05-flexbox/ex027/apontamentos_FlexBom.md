Ctrl + K; Ctrl + C -> Combinação para fazer comentário no VsCode

# Flex Conteiner - PAI

É o "Conteiner", que vai levar a configuração de 
--- *"Display: Flex"*
--- *flex-wrap:* __nowrap, wrap e wrap-reverse__

#  ITEM - Flex-items - FILHOS

São os blocos que estão dentro do Conteiner
--- *flex: auto;*
--- *text-align: center;*

# DIRECÇÕES E EIXOS

## flex-direction:

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

__felx-wrap:__ a propriedade flex-wrap é usada no conteiner e contem as seguintes propriedades: *nowrap*, *wrap* e *wrap-reverse*