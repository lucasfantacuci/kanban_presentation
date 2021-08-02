# Práticas Kanban

### Gerenciamento ativo de items em um fluxo de trabalho

O gerenciamento dos itens em um fluxo de trabalho pode assumir várias formas, que devem incluir pelo menos:

- Controle de WIP.
- Evitando que os itens de trabalho se acumulem em qualquer parte do fluxo de trabalho.
- Garantir que os itens de trabalho não envelheçam desnecessariamente, usando o SLE como referência.
- Desbloqueando trabalho bloqueado.

Uma prática comum é os membros do sistema Kanban revisarem o gerenciamento ativo de itens regularmente. Embora alguns possam escolher uma reunião diária, não há necessidade de formalizar a revisão ou reunir-se em uma cadência regular, desde que o gerenciamento ativo ocorra.

E esse gerênciamento só é possível, pois temos muitas informações sobre todo o nosso fluxo de trabalho. Por exemplo, conseguimos responder à perguntas como: Quanto tempo uma atividade ficou parada esperando o deploy.

#### Controle de trabalho em andamento - ou WIP

Os membros do sistema Kanban devem controlar explicitamente o número de itens de trabalho em um fluxo de trabalho do início ao fim. Esse controle é geralmente representado como números ou slots / tokens em um quadro Kanban que são chamados de limites WIP. Um limite de WIP pode incluir (mas não está limitado a) itens de trabalho em uma única coluna, várias colunas / pistas / áreas agrupadas ou um quadro inteiro.

Um efeito colateral do controle do WIP é que ele cria um sistema puxado. Quando o WIP cai abaixo do limite no DoW, é um sinal para selecionar um novo trabalho. Os membros devem evitar puxar / selecionar mais do que o número de itens de trabalho em uma determinada parte do fluxo de trabalho, conforme definido pelo Limite de WIP. Em casos raros, os membros do sistema podem concordar em extrair itens de trabalho adicionais além do Limite de WIP, mas não deve ser rotina.

O controle do WIP não apenas ajuda o fluxo de trabalho, mas também melhora o foco coletivo, o comprometimento e a colaboração dos membros do sistema Kanban. Quaisquer exceções aceitáveis para controlar o WIP devem ser explicitadas como parte do DoW.

![kanban](https://user-images.githubusercontent.com/13895978/127755355-f4f3ae66-705d-46fa-b262-f0f8442d0a1a.jpg)

#### Service Level Expectation

Somos os vilões para o Rafa.

O SLE é uma previsão de quanto tempo deve levar um único item de trabalho para fluir do início ao fim. O próprio SLE tem duas partes: um período de tempo decorrido e uma probabilidade associada a esse período (por exemplo, "85% dos itens de trabalho serão concluídos em oito dias ou menos"). O SLE deve ser baseado no tempo de ciclo histórico e, uma vez calculado, deve ser visualizado no quadro Kanban. Se os dados de tempo de ciclo histórico não existirem, uma melhor estimativa servirá até que haja dados históricos suficientes para um cálculo SLE adequado.

[Início](README.md) | [Anterior](kanban_pratices_one.md) | [Próximo](kanban_pratices_three.md)
