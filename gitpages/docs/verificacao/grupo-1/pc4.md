# Verificação Ponto de Controle 4 Bilheteria Digital

## Introdução
Este artefato apresenta a verificação das entregas da [etapa 4](https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/planejamento/cronograma/#entrega-4) feitos pelo grupo 8 no projeto IHC do sistema da [Bilheteria Digital](https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/). O objetivo da etapa de verificação é garantir a qualidade e a correção dos produtos desenvolvidos. Nesse contexto, esses processos são realizados para confirmar se os artefatos do software estão em conformidade com os requisitos definidos e se atendem às normas e convenções estabelecidas, e propondo melhorias para as falhas encontradas, contribuindo para a melhoria da qualidade do projeto.

## Metodologia
A verificação de artefatos de software pode ser feita por meio da análise estática, que revisa os artefatos sem executar o código, ou pela análise dinâmica, que executa o código e realiza testes. No contexto específico dos artefatos a serem verificados, optaremos pela abordagem de verificação estática, pois ela nos permitirá examinar a documentação e outros elementos relacionados, e para a verificação, utilizaremos o método de inspeção de Fagan <a href='#fagan'>[1]</a>. Durante a verificação, classificamos os problemas em padronização e conteúdo, utilizando checklists para abordar aspectos críticos. Essa abordagem estruturada ajuda a garantir a qualidade e a conformidade dos artefatos, aproveitando a perspectiva externa para identificar erros.

A inspeção terá como base os requisitos definidos para a entrega no plano de ensino da disiplina, os projetos anteriores, os feedbacks do professor durante as apresentações e o exemplo disponibilizado no moodle <a href='#exemplo'>[2]</a>.

## Checklists
A primeira checkçist verifica a padronização geral do documento, em seguida, apresentaremos as checklists para a verificação dos seguintes artefatos:

- [Planejamento da Avaliação da Análise de Tarefas](https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/design-avaliacao-desenvolvimento/nivel-1/analise-de-tarefas-dad/planejamento-avaliavao-at/)
- [Planejamento do relato dos resultados da Avaliação do Análise de Tarefas](https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/design-avaliacao-desenvolvimento/nivel-1/analise-de-tarefas-dad/planejamento-relato-resultados-at/)
- [Planejamento da Avaliação do Storyboard](https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/design-avaliacao-desenvolvimento/nivel-1/storyboard-dad/planejamento-avaliavao-sb/)
- [Planejamento do relato dos resultados da Avaliação do Storyboard](https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/design-avaliacao-desenvolvimento/nivel-1/storyboard-dad/planejamento-relato-resultados-sb/)


### Padronização

<center>

| Item | Descrição                                                                               | Avaliação                                          | Descrição do problema | Sugestão de ação corretiva |
|:----:|---------------------------------------------------------------------------------------- |:--------------------------------------------------:|---------------------- | -------------------------- |
| 1    | Possui o histórico de versão padronizado?                                               |<span style="color:#00E44E">Sim</span>              | |  |
| 2    | Possui o(s) autor(es) e revisor(es) de cada artefato?                                   |<span style="color:#00E44E">Sim</span>              | |  |
| 3    | Referências bibliográficas e/ou bibliografia são padronizadas usando as normas da ABNT? |<span style="color:#E2B93B">Incompleto</span>       | O planejamento do relato da Avaliação do Storyboard não possui Bibliografia | Adição da bibliogrfia para fins de padronização |
| 4    | Tabelas e imagens possuem legenda, fonte e são referenciadas dentro do texto?           |<span style="color:#00E44E">Sim</span>              | |  |
| 5    | Possui texto de introdução em cada artefato?                                            |<span style="color:#00E44E">Sim</span>              | |  |
| 6    | Possui links de referência?                                                             |<span style="color:#00E44E">Sim</span>              | |  |
| 7    | Possui erros de pontuação ou gramática?                                                 |<span style="color:#00E44E">Não identificados</span>| |  |

Tabela 1: Verificações de padronização.

</center>

### Conteúdo

#### Planejamento da Avaliação da Análise de Tarefas

<center>

| Item | Descrição                                                                                  | Avaliação                            | Descrição do problema | Sugestão de ação corretiva |
|:----:| ------------------------------------------------------------------------------------------ |:------------------------------------:|---------------------- | -------------------------- |
| 1    | O planejamento da avaliação segue o framework DECIDE?                                      |<span style="color:#00E44E">Sim</span>| |  |
| 2    | O artefato apresenta o(s) objetivo(s) do planejamento?                                     |<span style="color:#E2B93B">Sim</span>| | Remoção da frase que sugere uma avaliação do design na etapa de avaliação do modelo conceitual |
| 3    | O artefato apresenta o(s) método(s) de avaliação a ser(em) utilizado(s)?                   |<span style="color:#00E44E">Sim</span>| |  |
| 4    | O artefato aborda as questões práticas do planejamento?                                    |<span style="color:#00E44E">Sim</span>| |  |
| 5    | Existe um roteiro de perguntas a serem realizadas nas entrevistas?                         |<span style="color:#00E44E">Sim</span>| |  |
| 6    | As perguntas avaliam a interação do entrevistado com as tarefas analisadas?                |<span style="color:#00E44E">Sim</span>| |  |
| 7    | Os entrevistadores de cada avaliação são especificados?                                    |<span style="color:red">Não</span>| |  |
| 8    | O artefato aborda e explica o número de participantes das entrevistas?                     |<span style="color:#00E44E">Sim</span>| |  |
| 9    | O artefato apresenta os custos envolvidos e equipamentos necessários nas entrevistas?      |<span style="color:#00E44E">Sim</span>| |  |
| 10   | O artefato apresenta o cronograma com data, horário e local de realização das entrevistas? |<span style="color:#00E44E">Sim</span>| |  |
| 11   | O artefato aborda as questões éticas do planejamento?                                      |<span style="color:#00E44E">Sim</span>| |  |
| 12   | O artefato apresenta o termo de consentimento livre e esclarecido?                         |<span style="color:#00E44E">Sim</span>| |  |
| 13   | Apresenta quais dados serão coletados e como e por que serão utilizados?                   |<span style="color:#E2B93B">Incompleto</span>| Não há um detalhamento de como os dados obtidos serão utilizados | Detalhamento de que dados serão utilizados para a elaboração do protótipo final de alta fidelidade |
| 13   | Um teste piloto foi realizado?                                                             |<span style="color:#00E44E">Sim</span>| |  |

Tabela 1: Verificações do planejamento da Avaliação da Análise de Tarefas.

</center>

#### Planejamento do relato dos resultados da Avaliação da Análise de Tarefas

<center>

| Item | Descrição                                                                                       | Avaliação                            | Descrição do problema | Sugestão de ação corretiva |
|:----:| ----------------------------------------------------------------------------------------------- |:------------------------------------:|---------------------- | -------------------------- |
| 1    | O artefato apresenta o(s) objetivo(s) do planejamento?                                          |<span style="color:#00E44E">Sim</span>| |  |
| 2    | O artefato aborda como os participantes serão selecionados?                                     |<span style="color:#00E44E">Sim</span>| |  |
| 3    | O artefato apresenta as etapas a serem seguidas durante a entrevista?                           |<span style="color:#00E44E">Sim</span>| |  |
| 4    | O artefato explicita como será feita a análise e interpretação dos dados obtidos na entrevista? |<span style="color:#00E44E">Sim</span>| |  |
| 5    | O artefato apresenta onde e por que esses dados serão utilizados?                               |<span style="color:#00E44E">Sim</span>| |  |

Tabela 2: Verificações do planejamento do relato dos resultados da Avaliação da Análise de Tarefas.

</center>

#### Planejamento da Avaliação do Storyboard

<center>

| Item | Descrição                                                                                  | Avaliação                            | Descrição do problema | Sugestão de ação corretiva |
|:----:| ------------------------------------------------------------------------------------------ |:------------------------------------:|---------------------- | -------------------------- |
| 1    | O planejamento da avaliação segue o framework DECIDE?                                      |<span style="color:#00E44E">Sim</span>| |  |
| 2    | O artefato apresenta o(s) objetivo(s) do planejamento?                                     |<span style="color:#00E44E">Sim</span>| |  |
| 3    | O artefato apresenta o(s) método(s) de avaliação a ser(em) utilizado(s)?                   |<span style="color:#00E44E">Sim</span>| |  |
| 4    | O artefato aborda as questões práticas do planejamento?                                    |<span style="color:#00E44E">Sim</span>| |  |
| 5    | Existe um roteiro de perguntas a serem realizadas nas entrevistas?                         |<span style="color:#00E44E">Sim</span>| |  |
| 6    | As perguntas avaliam se o storyboard corresponde à realidade do usuário?                   |<span style="color:#00E44E">Sim</span>| |  |
| 7    | Os entrevistadores de cada avaliação são especificados?                                    |<span style="color:red">Não</span>| |  |
| 8    | O artefato aborda o número de participantes das entrevistas?                               |<span style="color:#00E44E">Sim</span>| |  |
| 9    | O artefato apresenta os custos envolvidos e equipamentos necessários nas entrevistas?      |<span style="color:#00E44E">Sim</span>| |  |
| 10   | O artefato apresenta o cronograma com data, horário e local de realização das entrevistas? |<span style="color:#00E44E">Sim*</span>| |  |
| 11   | O artefato aborda as questões éticas do planejamento?                                      |<span style="color:#00E44E">Sim</span>| |  |
| 12   | O artefato apresenta o termo de consentimento livre e esclarecido?                         |<span style="color:#00E44E">Sim</span>| |  |
| 13   | Apresenta quais dados serão coletados e como e por que serão utilizados?                   |<span style="color:red">Não</span>| |  |
| 14   | Um teste piloto foi realizado?                                                             |<span style="color:#00E44E">Sim</span>| |  |
| 15   | O artefato apresenta os storyboards produzidos?                                            |<span style="color:#00E44E">Sim</span>| |  |

Tabela 3: Verificações do planejamento da Avaliação do Storyboard.

</center>

#### Planejamento do relato dos resultados da Avaiação do Storyboard

<center>

| Item | Descrição                                                                                       | Avaliação                            | Descrição do problema | Sugestão de ação corretiva |
|:----:| ----------------------------------------------------------------------------------------------- |:------------------------------------:|---------------------- | -------------------------- |
| 1    | O artefato apresenta o(s) objetivo(s) do planejamento?                                          |<span style="color:#00E44E">Sim</span>| |  |
| 2    | O artefato aborda como os participantes serão selecionados?                                     |<span style="color:#00E44E">Sim</span>| |  |
| 3    | O artefato apresenta as etapas a serem seguidas durante a entrevista?                           |<span style="color:#00E44E">Sim</span>| |  |
| 4    | O artefato explicita como será feita a análise e interpretação dos dados obtidos na entrevista? |<span style="color:#00E44E">Sim</span>| |  |
| 5    | O artefato apresenta onde e por que esses dados serão utilizados?                               |<span style="color:red">Não</span>| |  |

Tabela 4: Verificações do planejamento do relato dos resultados da Avaliação do Storyboard.

</center>

## Referências
[1]<span id='fagan'>UNIVESP. "Técnica de revisão (Verificação) - Gerência e Qualidade de Software." 21 Jun. 2018. Disponível em: <https://youtu.be/nA1BVDd9GUE>. Acesso em: 4 de Junho de 2023.</span>

[2]<span id='exemplo'>GOV.BR. "Lista de Verificação da Qualidade de Artefatos", 2018. Disponível em: <https://aprender3.unb.br/mod/url/view.php?id=978988>. Acesso em: 4 de Junho de 2023.</span>
<!-- FONTES CITADAS UTILIZADAS PARA EMBASAR O TEXTO. REMOVER CASO NÃO HOUVER  -->

## Bibliografia
<!-- FONTES CONSULTADAS DURANTE A ELABORAÇÃO DO TEXTO, CITADAS OU NÃO. REMOVER CASO NÃO HOUVER -->
SIMONE DINIZ JUNQUEIRO BARBOSA, BRUNO SANTANA DA SILVA, Interação Humano-Computador, 1a.
Edição, Editora Campus, 2010. Publicado em: 03/05/2021.

UNIVESP. "Gerência e Qualidade de Software - Aula 05 - Verificação e Validação." 21 Jun. 2018. Disponível em: <https://youtu.be/1Y-1zz6rZxo>. Acesso em: 4 de Junho de 2023.

UNIVESP. "Técnica de revisão (Verificação) - Gerência e Qualidade de Software." 21 Jun. 2018. Disponível em: <https://youtu.be/nA1BVDd9GUE>. Acesso em: 4 de Junho de 2023.

Planejamento da Verificação, Lichess. Disponível em: <https://interacao-humano-computador.github.io/2022.2-Lichess/verificacao_validacao/pc4-planejamento/>


## Histórico de revisão

| Versão     | Data        | Descrição                                 | Autor(es)       | Revisores       |
| :--------: | :---------: | ----------------------------------------- | --------------- | --------------- |
| `0.0`      | 04/06/2023  | Criação do arquivo                        | Júlio César     | - |
| `0.1`      | 04/06/2023  | Adição da introdução e metodologia        | Arthur Trindade | Arthur D'Assumpção |
| `0.2`      | 05/06/2023  | Adição das listas de verificação          | Arthur Trindade | Arthur D'Assumpção |