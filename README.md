# 22a-emb-av3

| Entrega |
|---------|
| 15/6    |

Avaliação take-away de embarcados! A ideia aqui é que vocês criem um código exemplo de alguma coisa que temos no microcontrolador ou no laboratório e que ainda não foi explorado. 

Os exemplos podem ser em vários temas diferentes que a disciplina de computação embarcada trata: 

- periféricos uC: Periféricos do uC que ainda não foram explorados no curso
- Módulos: Temos gavetas cheias de módulos que precisam de exemplos!
- ARM Cortex M7: O core arm que utilizamos no curso possui diversas funcionalidades não trabalhadas
- CMSIS: A ARM disponibiliza implementações em C otimizadas para o CORE ARM, como: FFT, redes neurais.
- RTOS: Não existe apenas o freertos, diversos outros sistemas operacionais são usados mundo a fora.

A contribuição tem que ser na forma de um **Pull Request** para o repositório `same70-examples` e deve conter:

- um projeto do microchip studio com o código exemplo **COMENTADO**,
- um README explicativo
    - com referências aos manuais
    - diagrama 
    - trechos de código comentado
    - etx
    
O exemplo do TC é uma boa referência do que deve ser entregue:

- https://github.com/Insper/SAME70-examples/tree/master/Perifericos-uC/TC-IRQ

## Ideias

Temos uma lista de tópicos que podem ser escolhidos, notem que cada ideia já possui uma nota "máxima" atrelada, se você tiver outra ideia consulte o seu professor para saber se é válida e qual vai ser a nota.

- https://docs.google.com/spreadsheets/d/1y2Qp4ZpyMzFLdFuRBQkH_Xv0ON7it5ykk0pv9DZsSSU/edit?usp=sharing

### Exemplos fabricante

O fabricante disponibiliza exemplos para a maioria dos periféricos listados anteriormente, para acessar a lista:

1. abra o microchip studio
1. File -> New -> Example Project ...
1. Busque por `same70`
1. Expanda a lista (que por padrão está fechada)

:alert: Você pode usar o exemplo do fabricante como código base para o seu exemplo, mas você deverá editar e tornar ele mais amigável.

## Contribuindo

Para fazer o envio da contribuição você deve:

1. fazer um fork do repositório same70-examples
1. criar a nova pasta do exemplo
1. fazer um push para o fork
1. fazer um PR para o upstream 

## Validando

O Pull-request será avaliado pela equipe e só aceito se estiver com qualidade similar aos exemplos fornecido no repositório 
