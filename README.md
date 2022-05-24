# 22a-emb-av3

| Entrega |
|---------|
| 7/6     |

Avaliação take-away de embarcados! A ideia aqui é que vocês criem um código exemplo de alguma coisa que temos no microcontrolador ou no laboratório e que ainda não foi explorado. 

A contribuição tem que ser na forma de um **Pull Request** para o repositório `same70-examples` e deve conter:

- um projeto do microchip studio com o código exemplo **COMENTADO**, 
- um README explicativo com:
    - com referências aos manuais
    - diagrama 
    - trechos de código comentado
    - explicação sobre o periférico com referência aos manuais
    - diagrama de blocos ([exemplo](https://github.com/Insper/SAME70-examples/raw/master/Perifericos-uC/AFEC-Pin/doc/Diagrama_AFEC-Pin.svg))
    - um vídeo (aprox 5 min) explicando o periférico e o exemplo
    
O exemplo do TC é uma boa referência do que deve ser entregue:

- https://github.com/Insper/SAME70-examples/tree/master/Perifericos-uC/TC-IRQ

## Ideias

As ideias estão listas nos issues do repositório de exemplos:

- https://github.com/Insper/SAME70-examples/issues

Notem que cada ideia já possui um conceito atrelado e os labels indicam o tópico que a ideia se encontra.  se você tiver outra ideia consulte o seu professor para saber se é válida e qual vai ser a nota.

Os exemplos são classificados em vários temas diferentes que a disciplina de computação embarcada trata (labels do issue): 

- periféricos uC: Periféricos do uC que ainda não foram explorados no curso
- Módulos: Temos gavetas cheias de módulos que precisam de exemplos!
- ARM Cortex M7: O core arm que utilizamos no curso possui diversas funcionalidades não trabalhadas
- CMSIS: A ARM disponibiliza implementações em C otimizadas para o CORE ARM, como: FFT, redes neurais.
- RTOS: Não existe apenas o freertos, diversos outros sistemas operacionais são usados mundo a fora.

### Exemplos fabricante

O fabricante disponibiliza exemplos para a maioria dos periféricos do uC listados anteriormente, eles podem servir como base para a sua contribuição, para acessar a lista:

1. abra o microchip studio
1. File -> New -> Example Project ...
1. Busque por `same70`
1. Expanda a lista (que por padrão está fechada)

⚠️ Você pode usar o exemplo do fabricante como código base para o seu exemplo, mas você deverá editar e tornar ele mais amigável.

## Entrega

Primeira etapa é indicar no issue que você deseja fazer o exemplo em questão, não pode repetir! 

### Contribuindo

Para fazer o envio da entrega você deve:

1. fazer um fork do repositório same70-examples
1. criar a nova pasta do exemplo
1. trabalhar no exemplo, criar readme....
1. fazer um push para o fork
1. fazer um PR para o upstream 

### Validando

O Pull-request será avaliado pela equipe e só aceito se estiver com qualidade similar aos exemplos fornecido no repositório, no PR nós iremos pedir revisões da entrega. A nota só sera liberada após o exemplo possuir (com qualidade) todos os itens listados.

Lembre de colocar no PR uma pequena descrição do que você está propondo.

### Aceite e liberacão da nota

O Pull-request será avaliado pela equipe e só aceito (nota liberada) se estiver com qualidade similar aos exemplos fornecido no repositório e todos e com todos os requisitos pedidos.
