# Estudo de CSS3 - Flexbox

### Repositório criado para o curso "Posicionando elementos com Flexbox em CSS", da [Digital Innovation One](https://www.dio.me/).


### <<< Anotações >>> ✍ 


## Hierarquia

### Flex container - contém elementos filhos denominados flex item's

 - **Flex item** e/ou **flex container** 2 (visto que também pode conter outros elementos filhos);

    - Flex item 1.1;

    - Flex item 1.2;

      [...]

    - Flex item 1.n

  - **Flex item** 2;

    [...]

  - **Flex item** n.


## Propriedades (+  comuns)

### Container's:

- **display** (inicializador do flexbox);
- **flex-direction** (direcionamento dos ITENS, como linha ou coluna);
- **flex-wrap** (quebra de linha);
- **flex-flow** (abrev. direction e wrap);
- **justify-content** (alinhamento dos CONTAINERS de acordo com a direção);
- **align-items** (alinhamento dos ITENS de acordo com o eixo do CONTAINER);
- **align-content** (alinhamento das linhas dos CONTAINERS).

### Item's:

- **flex-grow** (fator de crescimento);
- **flex-basis** (tamanho inicial do item antes da distribuição);
- **flex-shrink** (capacidade de redução);
- **flex** (abrev. para grow, basis e shrink);
- **order** (ordem de distribuição / listagem dos itens);
- **align-self** (alinhamento de um item específico de nosso item).

## Variações / "Valores" das propriedades:

### justify-content
- **flex-start:** início do container;
- **flex-end:** final do container;
- **center:** ao centro do container;
- **space-between:** cria um espaçamento igual entre os elementos;
- **space-around:** os espaçamentos do meio são duas vezes maiores que o início e o final.

### align-items
- **center:** alinhamento dos itens ao centro;
- **stretch:** padrão, e os flex itens cresçam igualmente;
- **flex-start:** alinhamento dos itens no início;
- **flex-end:** alinhamento dos itens no final;
- **baseline:** alinhamento de acordo com a linha base da tipografia dos itens.

### align-content
- **center:** alinhamento dos itens ao centro;
- **stretch:** é o padrão e os flex itens crescem igualmente;
- **flex-start:** alinhamento dos itens ao início;
- **flex-end:** alinhamento dos itens no final;
- **space-between:** cria um espaçamento igual entre os elementos;
- **space-around:** os espaçamentos do meio são duas vezes maiores que o inicial e final.

### align-self
- **auto:** valor padrão, irá respeitar a definição de align items do container
- **flex-start:** ao início do container
- **flex-end:** ao final do container
- **center:** relativo ao centro de acordo com o eixo
- **stretch:** ocupa todo os espaços relativos
- **baseline:** utiliza a linha base da tipografia

