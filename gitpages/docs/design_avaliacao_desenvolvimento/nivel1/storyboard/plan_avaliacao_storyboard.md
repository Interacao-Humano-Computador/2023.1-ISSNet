# Planejamento da Avaliação de Storyboard

## Introdução
Este artefato apresenta os principais elementos do planejamento da avaliação dos storyboards ulitizados para a vizualização das tarefas apresentadas na [análise de tarefas](../../analise_de_requisitos/analise_de_tarefas.md) do sistema. Para garantir uma avaliação adequada, o planejamento se apoia nas atividades propostas pelo framework DECIDE:
<ul>
    <li><strong>D</strong>: Determinar os objetivos da avaliação;
    <li><strong>E</strong>: Explorar perguntas a serem respondidas com a avaliação
    <li><strong>C</strong>: Escolher os métodos de avaliação a serem utilizados
    <li><strong>I</strong>: Identificar e administrar as questões práticas da avaliação
    <li><strong>D</strong>: Decidir como lidar com as questões éticas
    <li><strong>E</strong>: Validar, interpretar e apresentar os dados
</ul>

## Objetivo
Os principais objetivos da avaliação dos storyboards é avaliar se as tarefas representadas condizem com a realidade do usuário e coletar feedback dos usuários a respeito das tarefas. Esse planejamento é importante pois permite identificar problemas precocemente e coletar dados para futuras tomada de decisões.

## Metodologia
A avaliação do planejamento dos storyboards será conduzida por meio de entrevistas, que podem ocorrer presencialmente ou de forma online utilizando a plataforma Teams, e questionários online, para atingir um maior número de usuários. 

Levando em consideração as questões éticas, no início da entrevista será apresentado o [termo de consentimento](../../../analise_de_requisitos/aspectos_eticos.md#termo-de-consentimento) ao entrevistado, permitindo que ele decida se deseja ou não participar. Caso o entrevistado concorde, o entrevistador seguirá o [roteiro](#roteiro-de-perguntas) estabelecido neste artefato para realizar as perguntas. Para o caso do questionário, o termo será apresentado antes das perguntas, caso o participante concorde com os termos, ele poderá prosseguir para as perguntas. 

A partir dos dados obtidos durante a entrevista e a partir do questionário, a equipe poderá analisar os pontos fortes e áreas de melhoria do site, possibilitando uma refatoração eficiente e alinhada aos requisitos dos usuários.

## Questões Práticas

### Participantes
Os usuários que participarão da avaliação serão contatados por meio de mensagens via WhatsApp ou Telegram. A seleção desses usuários foi realizada com base em seu interesse e disponibilidade para participar da entrevista. 

Está prevista a participação de, no mínimo, dois usuários na avaliação por meio de entrevistas. Essa quantidade foi determinada devido ao número limitado de participantes que manifestaram interesse e disponibilidade para o estudo. No entanto, para mitigar esse problema, os questionários também serão utilizados como parte do processo de coleta de dados.

### Equipamentos necessários
A avaliação por meio de entrevistas poderá ocorrer tanto de forma presencial quanto remota, levando em consideração as circunstâncias e preferências dos participantes. No caso das entrevistas presenciais, a voz dos entrevistados será gravada em dispositivo móvel em conformidade com os [termos de consentimento](../../../analise_de_requisitos/aspectos_eticos.md#termo-de-consentimento) estabelecidos para fins de avaliação. Se a entrevista for realizada de forma remota, a equipe utilizará a plataforma Teams para gravar a reunião.

### Cronograma planejado e prazos
A expectativa é que as entrevistas para a avaliação sejam concluídas até o próximo sábado (27/05), levando em conta o tempo necessário para a preparação, agendamento e realização das entrevistas. Essas considerações práticas foram feitas para garantir a viabilidade e o bom andamento da avaliação, visando obter insights relevantes sobre a usabilidade do site IssNetDF. A seguir, apresentamos o cronograma planejado para as entrevistas:

| Entrevista                            | Entrevistador(es)  | Período de realização    | Entrevistado |
| ------------------------------------- | ------------------ | :----------------------: | -------------|
| Avaliação do storyboard 1             | Arthur Trindade    | 22/05/2023<br>27/05/2023 | -            |
| Avaliação do storyboard 2             | Miguel Moreira     | 22/05/2023<br>27/05/2023 | -            |
| Avaliação do storyboard 3             | Gabriel de Souza   | 22/05/2023<br>27/05/2023 | -            |

<center>

*Tabela 1: Cronograma planejado de avaliação dos storyboards*

</center>

## Questões Éticas
Para realizar a entrevista, é necessário que o entrevistador informe ao entrevistado o [termo de consentimento](../../../analise_de_requisitos/aspectos_eticos.md#termo-de-consentimento) e obtenha sua concordância com os termos estabelecidos. É fundamental ressaltar que a equipe valoriza e assegura a máxima proteção, respeito e confidencialidade dos dados coletados dos entrevistados.

## Roteiro de Perguntas
A seguir, apresentamos o roteiro de perguntas que será utilizado durante a avaliação, que deve ser executado para cada um dos storyboards desenvolvidos.

#### Perguntas
<ol>
    <li> As tarefas representadas no storyboard são condizentes com a realidade?
        <ul>
            <li> Sim
            <li> Não
            <li> Não tenho certeza
        </ul>
    </li>
    <li> A sequência de ações do storyboard é condizente com a realidade?
        <ul>
            <li> Sim
            <li> Não
            <li> Não tenho certeza
        </ul>
    </li>
        <li> Existe alguma situação que você considera ruim e que não está ilustrada no storyboard? Se sim, qual(is)?
        <ul>
            <li> Sim (aberta)
            <li> Não
        </ul>
    </li>
    <li> Em uma escala de 1 a 5, qual o seu grau de satisfação com a tarefa ilustrada no storyboard?
        <ul>
            <li> 1: Insatisfeito
            <li> 2: Pouco satisfeito
            <li> 3: Indiferente
            <li> 4: Satisfeito
            <li> 5: Muito satisfeito
        </ul>
    </li>
        <li> Sobre o storyboard, você possui alguma sugestão de melhoria que poderia ser implementada na tarefa ilustrada? Se sim, qual(is)?
        <ul>
            <li> Sim (aberta)
            <li> Não
        </ul>
    </li>
</ol>

## Interpretação e apresentação dos dados
A interpretação dos dados será realizada após as entrevistas, e os dados obtidos serão apresentados de acordo com o [planejamento do relato dos reultados](relato_storyboard.md).

## Storyboards desenvolvidos
Os storyboards foram desenvolvidos usando as [análises de tarefa](../../analise_de_requisitos/analise_de_tarefas.md) e [cenários](../../analise_de_requisitos/cenarios.md) desenvolvidos para tarefas de geração, cancelamento e consulta de NFS-e, foi usado a ferramenta [StoryboardThat](../../../planejamento/ferramentas/#storyboardthat)

Na Figura 1 é apresentado o storyboard de consulta de NFS-e, um chefe de um funcionário pede para ele que consulte a nota fiscal de uma empresa que prestou serviços a eles.
<center>

*Figura 1: Storyboard Consulta NFS-e* 

</center>

![Storyboard Consulta NFS-e](../../img/storyboard-consulta.png)

<center>

*Fonte: Autor* 

</center>

Na figura 2 é mostrado o storyboard de geração de NFS-e, no fim do mês, um chefe pede ao funcionário para que ele cadastre todas as notas de serviço do mês.

<center>

*Figura 2: Storyboard Geração NFS-e* 

</center>

![Storyboard Geração NFS-e](../../img/storyboard-geracao.png)

<center>

*Fonte: Autor* 

</center>

No storyboard da figura 3, um cliente pede reembolso por motivo de serviço não prestado, em seguida a funcionária devolve o dinheiro e cancela a nota fiscal de serviço.

<center>

*Figura 3: Storyboard Cancelamento NFS-e* 

</center>

![Storyboard Cancelamento NFS-e](../../img/storyboard-cancelamento.png)

<center>

*Fonte: Autor* 

</center>

## Bibliografia
<!-- FONTES CONSULTADAS DURANTE A ELABORAÇÃO DO TEXTO, CITADAS OU NÃO. REMOVER CASO NÃO HOUVER -->
SIMONE DINIZ JUNQUEIRO BARBOSA, BRUNO SANTANA DA SILVA, Interação Humano-Computador, 1a.
Edição, Editora Campus, 2010. Publicado em: 03/05/2021.

Planejamento da Avaliação do Storyboard, Lichess. Disponível em: <https://interacao-humano-computador.github.io/2022.2-Lichess/design_avaliacao_desenvolvimento/nivel_1/storyboard/planejamento_avaliacao/>

Planejamento da Avaliação do Storyboard, Millenium Papelaria. Disponível em: <https://interacao-humano-computador.github.io/2022.1-Millenium-Papelaria/DesignAvaliacaoDesenvolvimento/nivel1/planejamentoAvaliacaoStoryBoard/>

## Histórico de revisão

| Versão     | Data        | Descrição                                  | Autor(es)       | Revisores       |
| :--------: | :---------: | ------------------------------------------ | --------------- | --------------- |
| `0.0`      |  20/05/2023 | Criação do arquivo                         | Júlio César     | - |
| `0.1`      |  22/05/2023 | Planejamento da avaliação dos storyboards  | Arthur Trindade | Miguel Moreira |
| `0.2`      |  28/05/2023 | Adiciona storyboards desenvolvidos na sala | Júlio César<br>Arthur Trindade<br>Arthur Assumpção<br>Miguel Moreira<br>Gabriel de Souza<br>Marcus Vinicius | Miguel Moreira |
| `0.3`      |  28/05/2023 | Padronização do documento e ajustes        | Arthur Trindade | Julio César |

