# Práticas Kanban

### Definiçaõ e visualização de um fluxo de trabalho

A otimização do fluxo requer primeiramente a definição do que significa fluxo de trabalho em um determinado contexto. A compreensão compartilhada do fluxo de trabalho entre os membros do sistema Kanban dentro de seu contexto é chamada de Definição de Fluxo de Trabalho, Definition of Workflow ou DoW. E o DoW é um conceito fundamental de Kanban. Todos os outros elementos do Kanban dependem muito de como o fluxo de trabalho é definido, e no mínimo nós devemos criar o DoW usando os seguintes elementos:

- Uma definição das unidades de valor que estão se movendo no fluxo de trabalho. https://exemplo-configuracao-lucas.atlassian.net/secure/admin/ConfigureOptionSchemes!default.jspa?fieldId=&schemeId=10132. Podemos adicionar outros tipos de atividades que gerem valor, por exemplo, não levei em consideração o fluxo de trabalho da Carol pois eu não tenho muito contexto sobre.
- Uma definição de quando os itens de trabalho são iniciados e concluídos em um fluxo de trabalho.
- Um ou mais estados definidos que os itens de trabalho fluem do início ao fim. Quaisquer itens de trabalho entre um ponto inicial e um ponto concluído são considerados trabalho em andamento. https://exemplo-configuracao-lucas.atlassian.net/secure/admin/workflows/ViewWorkflowSteps.jspa?atl_token=2f3a399f-7082-4025-a8ef-fd347fc09c73_6809a97b415c0c27b2294eeda8df249546389ae7_lin&workflowMode=live&workflowName=Development%20Subtask
- Uma definição de como o WIP será controlado do início ao fim, justamente por conta de criar um fluxo puxado.
- Políticas explícitas sobre como os itens de trabalho podem fluir em cada estado do início ao fim. Por exemplo, uma atividade só irá para refinamento técnico se ela tiver uma história bem descrita.
- Uma expectativa de nível de serviço (SLE), que é uma previsão de quanto tempo um item de trabalho deve levar para fluir do início ao fim.

Criei três fluxos de trabalho (DoW) e três quadros visuais.

- Primeiro nível - Importante para nível de Coordenadores. Por que? No caso meu pensamento ele foi focado em objetivos para a coorporação.
- Segundo nível - Importante para o nível de Gestores do projeto. O que? Histórias de como as coisas deverão ser implementadas para atingir um épico, Bugs que estão acontecendo, e definições de tarefas em geral.
- Terceiro nível - Importante para o nível operacional. Como? Após um refinamento técnico, todas as tarefas necessárias para alcançar uma atividade de segundo nível.

A visualização do DoW é chamada de quadro Kanban. Tornar pelo menos os elementos mínimos do DoW transparentes no quadro Kanban é essencial para processar o conhecimento que informa a operação ideal do fluxo de trabalho e facilita a melhoria contínua do processo.

Não há diretrizes específicas para a aparência de uma visualização, o importante é que o quadro mostre o entendimento compartilhado de como o valor é entregue.

[Início](README.md) | [Anterior](kanban_theory.md) | [Próximo](kanban_pratices_two.md)
