# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

| Juliana Souza      |                                    |                |
|--------------------|------------------------------------|----------------------------------------|
|![](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e3-proj-mov-t2-comanda-do-chefe/blob/main/docs/img/personas/juliana_souza.jfif)|**Idade:** 29 anos - **Ocupação:** Desenvovedora de Software, Dona de Casa |**Aplicativos:** Facebook, Whatsapp, Instagram.|
|**Motivações:** Juliana tem problemas em relação a dificuldade em si fazer um pedido em alguns lugares, pois a maioria de bares que frequenta estão sempre cheios, dificultando seus pedidos.  |**Frustrações:** Juliana não consegue realizar um pedido de forma fácil pois em alguns lugares não há organização em relação às filas dos caixas. |**Hobbies, História:** Juliana sempre foi dedicada em relação ao estudo/trabalho, encontrou sua paixão na tecnologia e durante sua faculdade unificou o trabalho ao seu dia a dia pois desde jovem tinha o sonho de morar sozinha.| 

| Nair Viana      |                                    |                |
|--------------------|------------------------------------|----------------------------------------|
|![](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e3-proj-mov-t2-comanda-do-chefe/blob/main/docs/img/personas/nair_viana.jfif)|**Idade:** 63 anos - **Ocupação:** Aposentada, Dona de Casa |**Aplicativos:** Whatsapp.|
|**Motivações:**  Pelos ambientes normalmente cheios ou com falta de organização na hora de retirar os pedidos Nair não consegue fazer seus pedidos de forma rápida e acaba tendo que esperar por muito tempo pela sua comida. |**Frustrações:**  PPor possuir hipoglicemia, Nair se vê em um beco sem saída quando quer comer em alguns restaurantes, pois sempre há uma demora na retirada e na preparação de seu pedido. |**Hobbies, História:** Por ser cultura de suas amigas sempre saírem para almoçar juntas aos sábados, Nair sempre teve que se preocupar em ter uma refeição pequena antes de sair para que não passe mal devido sua condição de saúde.

| João Marques    |                                    |                |
|--------------------|------------------------------------|----------------------------------------|
|![](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e3-proj-mov-t2-comanda-do-chefe/blob/main/docs/img/personas/jo%C3%A3o_marques.jfif)|**Idade:** 42 anos - **Ocupação:** Dono do restaurante Comida Mineira.     |**Aplicativos:** Facebook, Whatsapp, LinkedIn, Instagram, Jornais.|
|**Motivações:** Visando garantir melhor qualidade de atendimento em seu restaurante, o restaurante de João visa o uso de comanda digital que facilita o gerenciamento dos pedidos.  |**Frustrações:** Devido a recentes reclamações do atendimento falho em seu restaurante João decidiu melhorá-lo e agilizá-lo, trazendo mais satisfação do cliente.|**Hobbies, História:** Gosta de passar o tempo livre se divertido com a família.|

| Clara Lima   |                                    |                |
|--------------------|------------------------------------|----------------------------------------|
|![](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e3-proj-mov-t2-comanda-do-chefe/blob/main/docs/img/personas/clara_lima.jfif)|**Idade:** 19 anos - **Ocupação:** Estudante e garçonete em um bar local.     |**Aplicativos:**  Facebook, Instagram e WhatsApp.|
|**Motivações:** Clara começou a trabalhar como garçonete em um bar no período da noite para pagar sua faculdade. |**Frustrações:** Clara, por ser uma garçonete ainda sem experiência muitas vezes aca confundido os pedidos dos clientes.|**Hobbies, História:** Clara terminou o ensino médio e está se preparando para entrar na faculdade, e com o tempo tão corrido, procura sempre processos que agilizem suas atividades.|

| Milena Martins  |                                    |                |
|--------------------|------------------------------------|----------------------------------------|
|![](https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2022-2-e3-proj-mov-t2-comanda-do-chefe/blob/main/docs/img/personas/milena_martins.jfif)|**Idade:** 40 anos - **Ocupação:** Trabalha em uma multinacional da área de siderurgia.   |**Aplicativos:**  Facebook, Whatsapp, LinkedIn, Instagram, Jornais.|
|**Motivações:**  Milena é vegetariana e não consome bebidas alcoólicas, porém quando vai ao happy hour de sua empresa os pedidos são feitos por uma pessoa apenas. |**Frustrações:** Quando sai com seus amigos acaba tendo que dividir a conta de forma igual, mesmo não consumindo bebidas alcoólicas ou comidas com carne.|**Hobbies, História:** Gosta de sair com os amigos nos finais de semana e tocar violão.|


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Juliana Souza   | fazer meu pedido por app         | que não precise enfrentar filas grandes               |
|Nair Viana       | fazer meu pedido rápido                | que ele seja entregue o mais rápido possível |
|João Marques       | agilizar o atendimento dos meus clientes                | que os clientes saiam satisfeitos do restaurante |
|Clara Lima       | de uma maneira fácil de organizar os pedidos dos clientes                | que ela não se confunda ou atrase os pedidos |
|Milena Martins       | comodidade para fazer o seu próprio pedido                | sua conta fique separada das demais pessoas |
|Clara Lima       | autonomia para que os clientes façam o próprio pedido                | para que proporcione mais comodidade ao cliente |
|Milena Martins     | um cardápio bem organizado                  | consiga encontrar alimentos vegetarianos de forma prática |

## Modelagem do Processo de Negócio 

### Análise da Situação Atual

Apresente aqui os problemas existentes que viabilizam sua proposta. Apresente o modelo do sistema como ele funciona hoje. Caso sua proposta seja inovadora e não existam processos claramente definidos, apresente como as tarefas que o seu sistema pretende implementar são executadas atualmente, mesmo que não se utilize tecnologia computacional. 

### Descrição Geral da Proposta

Apresente aqui uma descrição da sua proposta abordando seus limites e suas ligações com as estratégias e objetivos do negócio. Apresente aqui as oportunidades de melhorias.

### Processo 1 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 1. Em seguida, apresente o modelo do processo 1, descrito no padrão BPMN. 

![Processo 1](img/02-bpmn-proc1.png)

### Processo 2 – NOME DO PROCESSO

Apresente aqui o nome e as oportunidades de melhorias para o processo 2. Em seguida, apresente o modelo do processo 2, descrito no padrão BPMN.

![Processo 2](img/02-bpmn-proc2.png)

## Indicadores de Desempenho

Apresente aqui os principais indicadores de desempenho e algumas metas para o processo. Atenção: as informações necessárias para gerar os indicadores devem estar contempladas no diagrama de classe. Colocar no mínimo 5 indicadores. 

Usar o seguinte modelo: 

![Indicadores de Desempenho](img/02-indic-desemp.png)
Obs.: todas as informações para gerar os indicadores devem estar no diagrama de classe a ser apresentado a posteriori. 

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
   correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
  Lembre-se que cada requisito deve corresponder à uma e somente uma
  característica alvo da sua solução. Além disso, certifique-se de que
  todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

| ID   | Restrição                                                    |
| ---- | ------------------------------------------------------------ |
| 01   | O projeto deverá ser entregue até o final do semestre        |
| 02   | O Projeto deve ser desenvolvido em uma linguagem para uma aplicação móvel |



## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)

# Matriz de Rastreabilidade

A matriz de rastreabilidade é uma ferramenta usada para facilitar a visualização dos relacionamento entre requisitos e outros artefatos ou objetos, permitindo a rastreabilidade entre os requisitos e os objetivos de negócio. 

A matriz deve contemplar todos os elementos relevantes que fazem parte do sistema, conforme a figura meramente ilustrativa apresentada a seguir.

![Exemplo de matriz de rastreabilidade](img/02-matriz-rastreabilidade.png)

> **Links Úteis**:
> - [Artigo Engenharia de Software 13 - Rastreabilidade](https://www.devmedia.com.br/artigo-engenharia-de-software-13-rastreabilidade/12822/)
> - [Verificação da rastreabilidade de requisitos usando a integração do IBM Rational RequisitePro e do IBM ClearQuest Test Manager](https://developer.ibm.com/br/tutorials/requirementstraceabilityverificationusingrrpandcctm/)
> - [IBM Engineering Lifecycle Optimization – Publishing](https://www.ibm.com/br-pt/products/engineering-lifecycle-optimization/publishing/)


# Gerenciamento de Projeto

De acordo com o PMBoK v6 as dez áreas que constituem os pilares para gerenciar projetos, e que caracterizam a multidisciplinaridade envolvida, são: Integração, Escopo, Cronograma (Tempo), Custos, Qualidade, Recursos, Comunicações, Riscos, Aquisições, Partes Interessadas. Para desenvolver projetos um profissional deve se preocupar em gerenciar todas essas dez áreas. Elas se complementam e se relacionam, de tal forma que não se deve apenas examinar uma área de forma estanque. É preciso considerar, por exemplo, que as áreas de Escopo, Cronograma e Custos estão muito relacionadas. Assim, se eu amplio o escopo de um projeto eu posso afetar seu cronograma e seus custos.

## Gerenciamento de Tempo

Com diagramas bem organizados que permitem gerenciar o tempo nos projetos, o gerente de projetos agenda e coordena tarefas dentro de um projeto para estimar o tempo necessário de conclusão.

![Diagrama de rede simplificado notação francesa (método francês)](img/02-diagrama-rede-simplificado.png)

O gráfico de Gantt ou diagrama de Gantt também é uma ferramenta visual utilizada para controlar e gerenciar o cronograma de atividades de um projeto. Com ele, é possível listar tudo que precisa ser feito para colocar o projeto em prática, dividir em atividades e estimar o tempo necessário para executá-las.

![Gráfico de Gantt](img/02-grafico-gantt.png)

## Gerenciamento de Equipe

O gerenciamento adequado de tarefas contribuirá para que o projeto alcance altos níveis de produtividade. Por isso, é fundamental que ocorra a gestão de tarefas e de pessoas, de modo que os times envolvidos no projeto possam ser facilmente gerenciados. 

![Simple Project Timeline](img/02-project-timeline.png)

## Gestão de Orçamento

O processo de determinar o orçamento do projeto é uma tarefa que depende, além dos produtos (saídas) dos processos anteriores do gerenciamento de custos, também de produtos oferecidos por outros processos de gerenciamento, como o escopo e o tempo.

![Orçamento](img/02-orcamento.png)
