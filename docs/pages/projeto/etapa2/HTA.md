# Análise Hierárquica de Tarefas (HTA) 

## Introdução

Análise de tarefa é um documento destinado a entender qual a rotina do usuário com o sistema, para saber qual suas necessidades e seus objetivos. Utilizada em diversos momentos do desenvolvimento de um software, mas principalmente na análise da situação atual (apoiada ou não por um sistema computacional) no (re)design de um sistema computacional e na avaliação do resultado de uma intervenção que inclua a introdução de um (novo) sistema computacional.

Neste documento faremos uma Análise Hierárquica de Tarefas (sigla em inglês HTA – Hierarchical  Task  Analysis).

## Metodologia

A Análise Hierárquica de Tarefas (ATS) foi desenvolvida na decada de 1960 e foi originalmente proposta para identificar necessidades de treinamento. Teve como objetivo compreender as incompetências e aptidões associadas a tarefas complexos e geralmente não repetitivas e identificar problemas de desempenho. Nesses casos, após a identificação, seria possível pensar em treinamentos adequados para melhorar a eficiência na execução de tais atividades. A ideia básica desta análise é relacionar o que as pessoas fazem (tarefas), por que o fazem, e as consequências se não o efectivar correctamente. O ponto de partida para esta análise são os objetivos do usuário. A partir do objetivo as principais tarefas relacionadas à consecução desse objetivo são diferentes.

O formato utilizado para a tarefa de demonstração será a notação textual e gráfica proposta por (Preece, Rogers e Sharp, 2005). Na notação de texto, os itens zero representam objetivos, os itens subsequentes representam tarefas e seus filhos representam subtarefas. Na notação gráfica, retângulos representam tarefas, linhas representam relações hierárquicas entre elas e planos representam relações entre hierarquias.

## Análises

### Representação textual

### Representação gráfica

<div style="text-align: center">
<p>Figura 1: Exemplo. </p>

```mermaid
graph TD
A[Hard] -->|Text| B[Round]
B --> C[Decision]
C -->|One| D[Result 1]
C -->|Two| E[Result 2]
```
<p>Fonte: Autoria própria. </p>
</div>



## Referências Bibliográficas

> Barbosa, S. D. J.; Silva, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2010.

> Preece, J.; Rogers, Y.; Sharp, H. Design de Interação. Porto Alegre: Bookman, 2005.

## Tabela de Versionamento

|    Data    | Versão |   Descrição    |                      Autor                      |                        Revisor                        |
| :--------: | :----: | :------------: | :---------------------------------------------: | :---------------------------------------------------: |
| 12/12/2022 | `1.0`  | Criação do HTA | [Pablo S. Costa](https://github.com/pabloheika) | [Charles Serafim](https://github.com/charles-serafim) |
