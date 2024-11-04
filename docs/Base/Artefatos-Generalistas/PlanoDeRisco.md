# Plano de Risco

## Introdução

O projeto Tsírco consiste em uma aplicação web que tem como objetivo ajudar a aumentar o interesse das pessoas
pela arte circense, que nos últimos 20 ano vêm passando por um processo de declínio de interesse do público e aos poucos está caindo no esquecimento. Porém, em todo projeto de desenvolvimento de um software, é vital avaliar todos os riscos que podem representar um obstáculo no desenvolvimento da aplicação. Eventos que geram incertezas e têm o potencial de afetar o alcance dos objetivos estratégicos são uma realidade em qualquer empreendimento. A gestão de riscos desempenha um papel fundamental na garantia do sucesso dos objetivos, servindo também como uma valiosa ferramenta para embasar decisões e minimizar ou eliminar retrabalho. 


## Contextualização
Risco representa o resultado, seja ele positivo ou negativo, de um evento singular ou de uma série de eventos que se materializam em um ou mais cenários. A sua avaliação se baseia na combinação da probabilidade de o evento ocorrer e do impacto que ele potencialmente acarretaria. Para a construção de um plano de risco é necessário os seguintes elementos:

- **Evento**: O que poderia acontecer?
- **Probabilidade**: Com que frequência ele poderia acontecer?
- **Impacto**: Quão ruim será se ele acontecer?
- **Mitigação**: Como você pode reduzir a sua probabilidade (e quanto poderia reduzir)?
- **Contingência**: Como você poderia reduzir seu impacto (e quanto poderia reduzir)?

## Nove Etapas para Criar um Plano de Risco
1. **Defina o escopo**: Avalie os riscos associados ao projeto, processo, ativos ou planejamento estratégico.
2. **Levante informações**: Questione o porquê, quem, como, quando, onde, o quê e quanto.
3. **Identifique os riscos e suas consequências**: Quais são os riscos e suas possíveis consequências?
4. **Atribua uma probabilidade**: Classifique a probabilidade de ocorrência em alta, média ou baixa.
5. **Avalie o impacto**: Classifique o impacto em alto, médio ou baixo.
6. **Determine o nível do risco**: Analise a probabilidade e o impacto.
7. **Ordene os riscos conforme suas avaliações**: Priorize do mais grave ao menos impactante.
8. **Analise a eficácia das estratégias implementadas**: Avalie a redução na probabilidade e no impacto dos riscos.
9. **Calcule o risco residual**: Após as ações de mitigação, determine o risco restante.

## Objetivos
I - Garantir que os tomadores de decisão tenham acesso às informações sobre os riscos que afetam o projeto, incluindo a capacidade de tomar decisões relacionadas à delegação, quando necessário;

II - Aumentar a probabilidade de atingir os objetivos do projeto, diminuindo os riscos para patamares aceitáveis;

III - Acrescentar valor ao projeto através da melhoria dos procedimentos de tomada de decisão e do tratamento adequado dos riscos.

## Metodologia
A metodologia adotada consiste em 5 passos para elicitação dos riscos.

1. **Elicitação de dados do ambiente e dos objetivos**
2. **Identificação de eventos de riscos**: Eventos que podem evitar, atrasar, prejudicar ou impedir o atingimento dos objetivos do projeto.
3. **Avaliação de eventos de riscos e controles**: Avaliar os eventos de risco sob a perspectiva de **Probabilidade** e **Impacto** para definir o nível de risco com a equação:
   
   **Nível de risco = impacto X probabilidade**

   ### Exemplo de Avaliação de Risco
   | Evento   | Probabilidade | Impacto | Nível de risco       |
   |----------|---------------|---------|----------------------|
   | Apagão   | 2             | 3       | 5 - Risco moderado   |

   #### Tabela 1. Exemplo de avaliação de risco. 

   ### Escala de Probabilidade
   | Peso | Escala             | Descrição                                                |
   |------|---------------------|----------------------------------------------------------|
   | 1    | Raro               | Eventos incomuns, sem nenhuma evidência que irá ocorrer   |
   | 2    | Pouco provável     | Eventos imprevísiveis ou acidentais                       |
   | 3    | Provável           | Evento que tem uma frequencia razoável de ocorrência      |
   | 4    | Muito provável     | Eventos que acontecem muito frequentemente                |
   | 5    | Praticamente certo | É quase garantido que ocorra                              |

   #### Tabela 2. Escala de Probabilidade. 

   ### Escala de Impacto
   | Peso | Escala        | Descrição                                    |
   |------|---------------|----------------------------------------------|
   | 1    | Muito baixo   | Têm um impacto mínimo                        |
   | 2    | Baixo         | Compromete só um pouco o projeto             |
   | 3    | Médio         | Compromete consideravelmente o projeto       |
   | 4    | Alto          | Compromete a maior parte do projeto          |
   | 5    | Muito alto    | Impossibilita a entrega do projeto           |

   #### Tabela 3. Escala de Impacto. 

   ### Classificação do Risco
   | Classificação           | Faixa       |
   |-------------------------|-------------|
   | RP (risco pequeno)      | 1 >= R <= 3 |
   | RM (risco moderado)     | 4 >= R <= 6 |
   | RA (risco alto)         | 8 >= R <= 12|
   | RC (risco crítico)      | 15 >= R <= 25|

   #### Tabela 4. Classificação do Risco. 
   ### Matriz de Risco
   No eixo Y está o impacto e no eixo X a probabilidade.

   |                   | (1) Raro | (2) Pouco provável | (3) Provável | (4) Muito provável | (5) Praticamente certo |
   |-------------------|----------|--------------------|--------------|--------------------|------------------------|
   | (5) Muito alto    | 5 - RM   | 10 - RA           | 15 - RC      | 20 - RC            | 25 - RC                |
   | (4) Alto           | 4 - RM   | 8 - RA            | 12 - RA      | 16 - RC            | 20 - RC                |
   | (3) Médio          | 3 - RP   | 6 - RM            | 9 - RA       | 12 - RA            | 15 - RC                |
   | (2) Baixo          | 2 - RP   | 4 - RM            | 6 - RM       | 8 - RA             | 10 - RA                |
   | (1) Muito baixo    | 1 - RR   | 2 - RP            | 3 - RP       | 4 - RM             | 5 - RM                 |

   #### Tabela 5. Matriz de Risco. 

## Categoria dos Riscos
- **Técnico**: Requisitos, Tecnologia, Confiabilidade, Usabilidade, Desempenho, Qualidade.
- **Externo**: Políticas, Infraestrutura, Condições climáticas.
- **Organizacional**: Dependências do projeto.
- **Gerencial**: Planejamento, Controle.

## Riscos Projeto Tsírco

Os principais riscos identificados  para o projeto Tsírco foram listados abaixo de acordo com a sua classificação: 

- **Gerencial**: Planejamento, Estimativa, Comunicação ineficiente, Prazos curtos.
- **Organizacional**: Recursos humanos, Priorização, Saída de membros do grupo, Baixo desempenho.
- **Externo**: Mercado, Cliente, Ambiente, Atraso das aulas.
- **Técnico**: Requisitos, Alteração de escopo, Plataforma, Funcionalidade.



## Probabilidade x Impacto
### Gerencial
#### Planejamento
O cronograma do projeto pode ter sido mal planejado, centralização do líder do grupo, má gestão.

| Probabilidade | Impacto |
|---------------|---------|
| 3             | 4       |

#### Tabela 6: Probabilidade x Impacto. 

#### Estimativa
Erros na hora de fazer estimativas acerca de prazos, custos...

| Probabilidade | Impacto |
|---------------|---------|
| 3             | 3       |

#### Tabela 7: Probabilidade x Impacto. 

#### Comunicação Ineficiente
A comunicação da equipe entre si e também a comunicação com o cliente podem haver ruídos ou falta de atualizações.

| Probabilidade | Impacto |
|---------------|---------|
| 2             | 2       |

#### Tabela 8: Probabilidade x Impacto. 

#### Prazos Curtos
Pouco tempo para desenvolver o projeto.

| Probabilidade | Impacto |
|---------------|---------|
| 4             | 4       |

#### Tabela 9: Probabilidade x Impacto. 

### Organizacional
#### Recursos Humanos
Imprevistos e emergências podem ocorrer com membros da equipe, o que compromete a sua dedicação ao projeto.

| Probabilidade | Impacto |
|---------------|---------|
| 1             | 2       |

#### Tabela 10: Probabilidade x Impacto. 

#### Priorização
Podem ser priorizadas tarefas que não são tão necessárias.

| Probabilidade | Impacto |
|---------------|---------|
| 2             | 5       |

#### Tabela 11: Probabilidade x Impacto. 
#### Saída de Membros
Pode ocorrer de algum membro sair da equipe de trabalho, devido a vários motivos.

| Probabilidade | Impacto |
|---------------|---------|
| 1             | 4       |

#### Tabela 12: Probabilidade x Impacto. 
#### Baixo Desempenho
Membros da equipe podem se sentir desmotivados ao longo do projeto.

| Probabilidade | Impacto |
|---------------|---------|
| 2             | 3       |

#### Tabela 13: Probabilidade x Impacto. 
### Externo
#### Mercado
Mudanças podem ocorrer no mercado, como proibição dos espetáculos de circo devido a periculosidade das apresentações.

| Probabilidade | Impacto |
|---------------|---------|
| 1             | 4       |

#### Tabela 14: Probabilidade x Impacto. 

#### Cliente
As prioridades e necessidades do cliente podem mudar ao longo do projeto.

| Probabilidade | Impacto |
|---------------|---------|
| 2             | 5       |

#### Tabela 15: Probabilidade x Impacto. 

#### Ambiente

Podem ocorrer mudanças climáticas nas regiões dos espetáculos que impossibilitem as apresentações, o que pode prejudicar o escopo do projeto.

| Probabilidade | Impacto |
|---------------|---------|
| 3             | 5       |

#### Tabela 16: Probabilidade x Impacto. 

#### Atraso das Aulas
Podem ocorrer atrasos durante o semestre do conteúdo passado, o que pode influenciar nos prazos das tarefas.

| Probabilidade | Impacto |
|---------------|---------|
| 2             | 2       |

#### Tabela 17: Probabilidade x Impacto. 

### Técnico
#### Requisitos
Requisitos podem ter sido elicitados erroneamente, pode ocorrer mudança na priorização dos requisitos, pode surgir necessidade de novas funções.

| Probabilidade | Impacto |
|---------------|---------|
| 2             | 4       |

#### Tabela 18: Probabilidade x Impacto. 

#### Alteração de Escopo
O escopo trabalhado pode ser alterado devido à circunstâncias externas.

| Probabilidade | Impacto |
|---------------|---------|
| 1             | 5       |

#### Tabela 19: Probabilidade x Impacto. 

#### Plataforma
A plataforma de desenvolvimento dos membros da equipe pode apresentar defeitos críticos impossibilitando a continuidade do trabalho.  

| Probabilidade | Impacto |
|---------------|---------|
| 2             | 5       |

#### Tabela 20: Probabilidade x Impacto. 
#### Funcionalidade
As funcionalidades implementadas podem apresentar erros.

| Probabilidade | Impacto |
|---------------|---------|
| 2             | 2       |

#### Tabela 21: Probabilidade x Impacto. Fonte: Autores.

## Classificação de Risco
Utilizando a Fórmula 1, foi calculado o nível de risco dos eventos mostrados acima.

| Evento                     | Probabilidade | Impacto | Nível de risco        |
|---------------------------|---------------|---------|-----------------------|
| Planejamento               | 3             | 4       | (12 - RA) - Risco alto|
| Estimativa                 | 3             | 3       | (9 - RA) - Risco alto |
| Comunicação ineficiente    | 2             | 2       | (4 - RM) - Risco médio|
| Prazos curtos              | 4             | 4       | (16 - RC) - Risco crítico|
| Recursos humanos            | 1             | 2       | (2 - RA) - Risco alto |
| Priorização                | 2             | 5       | (10 - RA) - Risco alto |
| Saída de membros           | 1             | 4       | (4 - RP) - Risco pouco provável|
| Baixo desempenho           | 2             | 3       | (6 - RM) - Risco médio |
| Mercado                    | 1             | 4       | (4 - RM) - Risco médio |
| Cliente                    | 2             | 5       | (10 - RA) - Risco alto |
| Ambiente                   | 3             | 5       | (15 - RC) - Risco crítico|
| Atraso das aulas           | 2             | 2       | (4 - RM) - Risco médio |
| Requisitos                 | 2             | 4       | (8 - RA) - Risco alto |
| Alteração de escopo        | 1             | 5       | (5 - RM) - Risco médio |
| Plataforma                 | 2             | 5       | (10 - RA) - Risco alto |
| Funcionalidade             | 2             | 2       | (4 - RM) - Risco médio |

## Medidas
Medidas que podem ser tomadas para mitigar os riscos. Em uma primeira fase, foram preparadas providências para os eventos classificados como risco alto e risco crítico, já que são os que mais impactam no projeto.

### Planejamento
Reuniões de alinhamento com os membros acerca do prazo e da demanda, de forma que o planejamento seja sempre ajustado com o intuito de entregar o projeto no prazo. A comunicação efetiva e a divisão equitativa de tarefas contribuem para diminuir esse evento.

### Estimativa
Estimar com mais precisão, utilizar ferramentas de estimativa comprovada cientificamente, e manter sempre contato com o cliente.

### Prazos Curtos
Requer um planejamento eficiente e comprometimento da equipe.

### Recursos Humanos
O líder deve semanalmente checar como a equipe está se sentindo em relação aos prazos, à demanda, e se necessitam de ajuda com algo.

### Priorização
Utilizar mais de uma ferramenta de priorização e fazer uma comparação entre as duas, com o intuito de realmente priorizar as que são mais importantes.

### Cliente
Organizar reuniões quinzenais com os clientes, fazer ata e assinatura, para mitigar imprevistos e novas demandas que possam ocorrer.

### Ambiente
Estar por dentro das notícias e acompanhar o que está acontecendo nos locais em que estão sendo realizadas as apresentações.

### Requisitos
Checar com os clientes se é isso mesmo que é necessário, questionar sempre e deixar claro as prioridades.

### Alteração de Escopo
Organizar reuniões com o cliente para entender o que é necessário, qual a prioridade de cada entrega.

### Funcionalidade
Implementar um bom teste do software em questão.

## Conclusão
A elaboração do plano de risco se torna uma ferramenta essencial para uma boa gestão do projeto, já que possibilita uma visão ampla e clara sobre os riscos a serem enfrentados e as medidas a serem tomadas para que eles não impactem de forma negativa na entrega final do projeto. 

## Histórico de versão

| Versão | Data | Descrição | Autor(es) |
| ------ | ---- | --------- | --------- |
| 0.1  | 02/11/2024 | Criação do Artefato | [João Pedro](https://github.com/joaopedrodasilvarodrigues), [Raphael Mendes da Silva](https://github.com/Raphides), [Henrique Batalha](https://github.com/HeBatalha), [Isaque Santos](https://github.com/IsaqueSH)|
| 0.2  | 04/11/2024 | Criação do Histórico de Versão | [Henrique Batalha](https://github.com/HeBatalha), [Isaque Santos](https://github.com/IsaqueSH), [Magno Luiz](https://github.com/magnluiz)|

> **Observação:** A adição do histórico de versão 0.1 foi feito posteriormente na data 04/11/2024. Devido a falta de uma ata criada na ocasião alguns detalhes podem estar incorretos.

