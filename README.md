# FlexBox - Definitions
### FlexBox => Baseado num estudo sobre FlexBox, onde tento agrupar algumas informações que irão me auxiliar em futuros projetos.

### FLEX-BOX : TAMANHO DA PÁGINA DESCONHECIDO OU DINÂMICO

- Display : flex //criar um conteiner flexível a nível de bloco
- Display: inline-flex //faz o mesmo mas em linha
- Flex-direction: row //valor padrão, um ao lado do outro
- Flex-direction: column // organizado em coluna
- Flex-wrap: wrap //links que excedem são movidos para próxima linha
- Flex-wrap: nowrap //valor padrão que junta todos os itens conforme o tamanho do conteiner
- Justify-content: flex-start     //define alinhamento dos itens conforme o eixo principal => horizontal
- Justify-content: flex-end
- Justify-content: center 
- Justify-content: space-between
- Justify-content: space-around
- Justify-content: space-evenly
- Align-items:  stretch       //parecido com justify-content, mas define como itens serão posicionados conforme o eixo transversal do conteiner //linha 
- Align-items:  flex-start
- Align-items:  flex-end
- Align-items:  center
- Align-items:  baseline
- Align-content: flex-start		//alinha as linhas de um conteiner, para tirar espaços no eixo transversal
- Align-content: flex-end
- Align-content: center
- Align-content: stretch
- Align-content: space-between
- Align-content: space-around

#### Descrição de Cada Um
*não esquecer de acrescentar "display:flex" no css do elemento* 
#### antes => justify-content: ...
##### flex-start: Items align to the left side of the container.
##### flex-end: Items align to the right side of the container.
##### center: Items align at the center of the container.
##### space-between: Items display with equal spacing between them.
##### space-around: Items display with equal spacing around them.

*não esquecer de acrescentar "display:flex" no css do elemento*
#### antes => align-items: ...
##### flex-start: Items align to the top of the container.
##### flex-end: Items align to the bottom of the container.
##### center: Items align at the vertical center of the container.
##### baseline: Items display at the baseline of the container.
##### stretch: Items are stretched to fit the container.

*não esquecer de acrescentar "display:flex" no css do elemento*
#### antes => flex-direction: ...
##### row: Items are placed the same as the text direction.
##### row-reverse: Items are placed opposite to the text direction.
##### column: Items are placed top to bottom.
##### column-reverse: Items are placed bottom to top.

## Site que auxilia neste aprendizado => 
https://flexboxfroggy.com/
