# Ctrl + K; Ctrl + C -> Combinação para fazer comentário no VsCode

## FLEX-ITEM

Items flexiveis que estão dentro do conteiner_

__order__
propriedade padrão é o ZERO (0), mas ela serve para mudar a ordem dos items. Esta propridade é para coloar mesmo número nos indices

__align-self__
vai funcionar no cross-axis (eixo-transversal)

--- *align-self: auto*: vai herdar o alinhamento do pai
--- *align-self: flex-start*
--- *align-self: flex-end*
--- *align-self: center*
--- *align-self: strech*

__flex_basis__
Vai definir o tamanho dos items. O *flex-flow* deve ser *nowrap*

--- *flex-basis: auto*: valor padrão, vai se ajustar em função do tamanho do conteúdo que está dentro do ítem.
--- *flex-basis: 200px*: aqui vamos definir os tamanhos de acordo ao nosso gosto

__flex-grow: *0*__ O quanto pode Crescer
__flex-srink: *1*__ O quanto pode Enconlher

--- *flex-grow: 0* - Não pode crescer
--- *flex-grow: 1* - Pode crescer

--- *flex-srink: 0* - Não pode encolher
--- *flex-srink: 1* - Pode encolher

OBS: QUANDO USAMOS A PROPRIEDADE FLEX-FLOW: ROW WRAP, E USAMOS O FLEX-SHRINK E O FLEX-GROW COM OS VALORES 1, O CONTEÚDO FICA TODO MALEÁVEL, ELE QUEBRA E AJUSTA A TELA
