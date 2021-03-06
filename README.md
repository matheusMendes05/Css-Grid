# CSS GRID

## GRID
 - Bidimensional
 - Divisão de toda a pagina em linhas e colunas
 - Colocar elementos onde quiser nessa divisão

 ---
 ## Grid ou Flexbox
 - Grid: Duas dimensões (colunas e linhas)
 - Flexbox: Uma dimensão(ou coluna ou linha)
 - Um complementa o trabalho do outro
 - Verificar quais navegadores aonda nao estao aceitando css grid

 ### CONTAINER
 - display: grid;
 - grid-template-columns;
 - grid-template-rows;
 - grid-gap
    - grid-row-gap
    - grid-column-gap
-grid-template-areas;

... e mais 4 propriedades de **alinhamento**
---
## ITEM(s)
- grid-column
    - grid-column-start
    - grid-column-end
- grid-row
    - grid-row-start
    - grid-row-end
- grid-area

... e mais 2 propriedades de **alinhamento**

# Grid: Alinhamento
---

Existem 6 propriedades para alinhamento:
 `justify-content`
 `align-content`
 `justify-items`
 `align-items`
 `justify-self`
 `align-content`

Vamos Separa-los em 2 grupos
 `justify` e `align`
 `content`, `items` e `self`


 ---
 ## Justify e Align

 Sabendo que o grid é bidimensional, nos temos o eixo x e o y.
 
 O **eixo x** é o posicionamento horizontal, da esquerda para a direita.

 o **eixo y** é o posicionamento vertical, de cima para baixo

 ## content, Items e Self
  
  Juntando o `justify`, ou `align`, com esses elementos: `content`, `items` e `self`; nós observamos nossas propriedades

  ---

  ### Content

`justify-content` e `align-content` nos permite alinhar o proprio grid, relativo ao espaco fora do grid.

O Uso dessas propriedades são raras, pois só é aplicado caso seja menor que a area definida. (Por exemplo, quando usamos em px  o tamanho do grid, poderemos terminar com um grid pequeno, para po tamanho da area do grid)

Podemos usar **7 valores**:
1. start
2. end
3. center
4. stretch
5. space-between
6. space-around
7. space-evenly

  ### Items

`justify-items` e `align-items` vai permitir alinhar os items do nosso grid, em qualquer espaço disponivel, na célula que ele abitar.

Podemos usar **4 valores**:
1. start
2. end
3. center
4. stretch

  ### Self.

`justify-self` e `align-self` vai permitir alinhar os items em si

Faz a mesma coisa que o `justify-items` e `align-items`, porém, aplicados diretamente no item de um grid