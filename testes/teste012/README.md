## GRID

-Bidimensional
-Divisão de toda a pagina em linhas e colunas
-Colocar elementos onde quiser nessa divisão

## GRID ou FLEXBOX?

-Grid: Duas dimensões (linhas e colunas)
-Flexbox: Uma dimensão (linha ou coluna)
-Um complementa o outro

## PROPRIEDADES

Vamos separar em 2 grupos:
'container' e 'item(s)'

## CONTAINER

- display: grid;
- grid-template-columns;
- grid-template-rows
- grid-gap
    -grid-row-gap
    -grid-column-gap
-grid-template-areas;

... e mais 4 propriedades de **alinhamentos**

## ITEM(s)

- grid-column
    - grid-column-start
    - grid-column-end
- grid-row
    - grid-row-start
    - grid-row-end
-grid-area

... e mais 2 propriedades de **alinhamento**

## Grid: Alinhamento

1. 'justify-content'
2. 'align-content'
3.  'justify-items'
4. 'align-items
5. 'justify-self'
6. 'align-self'

Vamos separa-los em 2 grupos
1. 'justify' e 'align'
2. 'content' , 'items' e 'self'

## Justufy e Align

Sabendo que o grid é bidimensional, nós temos o eixo x e y

O **eixo x** é o posicionamento horizontal, da esquerda para a adireita

O **eixo y** é o posicionamento vertical, de cima para baixo

## Content, Items e Self

Juntando justify e align com esses elementos, nós observamos nossas propriedades

## Content

'justify-content' e 'align-content' nos premite alinhar o proprio grid, relativo ao espaço fora do grid

O uso dessas propriedades são raras, pois é só aplicado caso o grid seja menor que a area definida.
(Por exemplo, quando usamos em px o tamanho do grid, poderemos terminar com o grid pequeno, para o tamanho do grid real)

Valores:

1. start
2. end
3. center
4. strecth
5. space-around
6. space-between
7. space-evenly

## Items

justify-items e align-items vai permitir alinhar os items do nosso grid, em qualquer espaço disponivel, na celula que ele abilitar

## Self

justify-self e align-self vai nos permitir alinhar o item em si

Faz a mesma coisa que o justyfy-items e align-items, porem aplicando diretamente no item da grid

