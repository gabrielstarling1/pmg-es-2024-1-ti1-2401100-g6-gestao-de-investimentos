# Informações do Projeto
`TÍTULO DO PROJETO`  

InvestPro

`CURSO` 

Engenharia de Software

## Participantes
Os membros do grupo são: 
* Gabriel Marcondes Starling Rocha
* João Eduardo Soares
* João Pedro Peres Barbosa
* Lucas José Lopes Ferreira
* Mateus Rodrigues Costa 

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas e Mapas de Empatia](#personas-e-mapas-de-empatia)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

## Problema

Investir no mercado financeiro pode ser complicado e desafiador. Muitas pessoas têm dificuldade em entender como investir, o porquê investir e como gerenciar efetivamente seus investimentos. Além disso, o controle de investimentos pode ser confuso e demorado, especialmente ao lidar com múltiplas contas e instituições financeiras.

InvestPro enfrenta o desafio de simplificar esse processo para investidores de todos os níveis de experiência. A plataforma visa fornecer educação financeira, orientação especializada e ferramentas poderosas para facilitar o gerenciamento e controle de investimentos, permitindo aos usuários tomar decisões mais inteligentes e maximizar seus retornos financeiros.

## Objetivos

Desenvolver um software eficiente e intuitivo para simplificar o processo de investimento, fornecendo educação financeira, orientação especializada e ferramentas de gerenciamento de investimentos, a fim de ajudar investidores de todos os níveis de experiência a tomar decisões informadas e maximizar seus retornos financeiros.

1. **Desenvolvimento de uma Plataforma Educacional:**
   Criar uma seção educacional dentro da plataforma InvestPro, oferecendo recursos como artigos, vídeos e tutoriais interativos para fornecer aos usuários conhecimentos básicos sobre investimentos, estratégias de investimento e gestão de carteiras. O objetivo é capacitar os investidores a entenderem melhor o mercado financeiro e tomarem decisões mais conscientes.

2. **Implementação de Ferramentas de Controle e Comparação de Investimentos:**
   Desenvolver ferramentas que permitam aos usuários acompanhar facilmente o desempenho de seus investimentos, realizar comparações entre diferentes ativos e instituições financeiras, e facilitar a portabilidade de dados entre contas. Isso incluirá a integração de APIs de instituições financeiras para fornecer acesso direto aos dados dos investidores e a criação de algoritmos de análise para gerar insights relevantes sobre o desempenho dos investimentos. O objetivo é simplificar o controle e a gestão das carteiras de investimento, permitindo aos usuários otimizar seus portfólios e maximizar seus resultados financeiros.

## Justificativa

Investir dinheiro é uma atividade crucial para muitas pessoas e empresas, e pode ter um impacto significativo em seu bem-estar financeiro futuro. No entanto, o processo de investimento pode ser complexo e intimidador para aqueles que não têm experiência ou conhecimento adequado. Aqui estão algumas razões pelas quais escolhemos trabalhar com a aplicação InvestPro e definir os objetivos específicos:

1. **Democratização do Conhecimento Financeiro:**
   Muitas pessoas evitam investir simplesmente porque não entendem como funciona o mercado financeiro. Ao desenvolver uma plataforma educacional dentro do InvestPro, podemos ajudar a democratizar o conhecimento financeiro, tornando as informações sobre investimentos acessíveis e compreensíveis para um público mais amplo. Isso pode motivar mais pessoas a começarem a investir e a tomar melhores decisões financeiras para o seu futuro.

2. **Facilitar o Controle e Gerenciamento de Investimentos:**
   Gerenciar investimentos pode ser uma tarefa desafiadora, especialmente para aqueles com múltiplas contas e investimentos em diferentes instituições financeiras. Implementar ferramentas de controle e comparação de investimentos no InvestPro pode simplificar esse processo, fornecendo aos investidores uma visão clara e abrangente de seus portfólios e permitindo que façam ajustes estratégicos com base em dados precisos e atualizados. Isso pode ajudar os investidores a maximizar seus retornos e minimizar seus riscos ao longo do tempo.

3. **Promover a Confiança e Segurança dos Investidores:**
   Muitas vezes, a falta de transparência e controle pode levar os investidores a se sentirem inseguros em relação aos seus investimentos. Ao oferecer ferramentas que simplificam o processo de controle e comparação de investimentos, podemos promover a confiança e segurança dos investidores, permitindo-lhes tomar decisões mais informadas e sentir-se mais no controle de seu futuro financeiro.

## Público-Alvo

## Perfil dos Usuários da Aplicação InvestPro

### Investidores Iniciantes:
- **Conhecimentos Prévios:** Pouca ou nenhuma experiência em investimentos.
- **Relação com a Tecnologia:** Uso básico de dispositivos eletrônicos e aplicativos, mas com pouca familiaridade com plataformas de investimento.
- **Objetivo:** Aprender sobre investimentos, entender os conceitos básicos e começar a construir uma carteira de investimentos.

### Investidores Intermediários:
- **Conhecimentos Prévios:** Alguma experiência em investimentos, familiarizados com conceitos básicos.
- **Relação com a Tecnologia:** Uso regular de dispositivos eletrônicos e aplicativos, confortáveis em explorar novas plataformas.
- **Objetivo:** Aprofundar o conhecimento em investimentos, diversificar a carteira e otimizar o retorno sobre o investimento.

### Investidores Avançados:
- **Conhecimentos Prévios:** Experiência sólida em investimentos, entendimento avançado de conceitos financeiros.
- **Relação com a Tecnologia:** Proficiente no uso de tecnologia, familiarizados com ferramentas de análise financeira e investimento.
- **Objetivo:** Aperfeiçoar estratégias de investimento, maximizar retornos e gerenciar portfólios complexos com eficiência.

### Consultores Financeiros:
- **Conhecimentos Prévios:** Experiência profissional em consultoria financeira, certificações em finanças ou investimentos.
- **Relação com a Tecnologia:** Habilidades avançadas em tecnologia, utilização de softwares especializados em análise financeira.
- **Objetivo:** Prestar assistência aos clientes na tomada de decisões de investimento, utilizar a plataforma para análise de dados e geração de relatórios personalizados.

### Administradores de Instituições Financeiras:
- **Conhecimentos Prévios:** Experiência em gestão financeira e compliance.
- **Relação com a Tecnologia:** Proficiente em ferramentas de software financeiro e sistemas de informação.
- **Objetivo:** Utilizar a plataforma para análise de dados e monitoramento do desempenho dos investimentos sob sua responsabilidade, tomar decisões estratégicas com base nos insights fornecidos pelo InvestPro.

### Empreendedores e Gestores de Pequenas Empresas:
- **Conhecimentos Prévios:** Variedade de conhecimentos, desde básicos até avançados, dependendo da formação acadêmica e experiência profissional.
- **Relação com a Tecnologia:** Uso regular de tecnologia para fins comerciais e financeiros.
- **Objetivo:** Utilizar a plataforma para gerenciar os investimentos pessoais e/ou corporativos, otimizando os recursos financeiros da empresa e maximizando o retorno sobre o capital investido.

### Público Geral:
- **Conhecimentos Prévios:** Diversificados, desde leigos até experientes em investimentos.
- **Relação com a Tecnologia:** Varia de acordo com a faixa etária e experiência individual.
- **Objetivo:** Aprender sobre investimentos, acessar informações financeiras relevantes e tomar decisões informadas sobre suas finanças pessoais.
 
# Especificações do Projeto

Nesta parte do documento, serão detalhadas as especificações do projeto InvestPro, delineando os requisitos funcionais e não funcionais da aplicação. As seguintes técnicas e ferramentas serão utilizadas para realizar as especificações do projeto:

1. **Levantamento de Requisitos:**
   - Utilização de questionários, entrevistas e análise de documentos para identificar as necessidades dos usuários e as funcionalidades desejadas da aplicação.

2. **Prototipagem:**
   - Desenvolvimento de protótipos de baixa e alta fidelidade para visualizar a interface da aplicação e validar o fluxo de navegação e as funcionalidades propostas.

3. **Diagramas de Caso de Uso:**
   - Criação de diagramas de caso de uso para representar as interações entre os diferentes atores e os casos de uso da aplicação.

4. **Mapas Mentais e Diagramas de Fluxo de Dados:**
   - Elaboração de mapas mentais e diagramas de fluxo de dados para visualizar a estrutura da aplicação e o fluxo de informações entre os diferentes componentes do sistema.

5. **Análise de Riscos:**
   - Identificação e avaliação dos riscos potenciais associados ao desenvolvimento e implementação da aplicação, bem como a definição de estratégias para mitigá-los.

6. **Feedback dos Stakeholders:**
   - Coleta de feedback dos stakeholders, incluindo investidores, consultores financeiros, administradores de instituições financeiras e outros usuários relevantes, para garantir que as especificações do projeto atendam às suas expectativas e requisitos.

## Personas e Mapas de Empatia

......  COLOQUE AQUI O SEU TEXTO ......


> Relacione as personas identificadas no seu projeto e os respectivos mapas de empatia. Lembre-se que 
> você deve ser enumerar e descrever precisamente e de forma
> personalizada todos os principais envolvidos com a solução almeja. 
> 
> Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina
> e/ou nos seguintes links:
>
> **Links Úteis**:
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Como fazer um mapa de empatia - Vídeo](https://www.youtube.com/watch?v=JlKHGpVoA2Y)
> 
> 
> **Exemplo de Persona**
> 
> ![Persona01](images/Persona01.png)
> 
> ![Persona02](images/Persona02.jpg)
>
> ![Persona03](images/Persona03.jpg)
> Fonte: [Como criar uma persona para o seu negócio](https://raissaviegas.com.br/como-criar-uma-persona/)


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

| EU COMO... `PERSONA` | QUERO/PRECISO ... `FUNCIONALIDADE` | PARA ... `MOTIVO/VALOR` |
|----------------------|------------------------------------|-------------------------|
| Usuário do sistema   | Registrar minha conta              | Não perder minha organização financeira |
| Usuário do sistema   | Registrar meus investimentos       | Controle e acompanhamento de ganhos e perdas |
| Usuário do sistema   | Cadastrar conta bancária para atualização automática de dados | Não esquecer de fazê-las |
| Usuário do sistema   | Simular ganhos do investimento     | Permitir uma decisão baseada em dados sobre o investimento |
| Usuário do sistema   | Analisar o meu perfil de investidor | Para fazer os cursos e investir de uma forma que me agrade |
| Usuário do sistema   | Visualizar os cursos e meu progresso | Permitir que possam administrar o meu progresso nos cursos |

> Apresente aqui as histórias de usuário que são relevantes para o
> projeto de sua solução. As Histórias de Usuário consistem em uma
> ferramenta poderosa para a compreensão e elicitação dos requisitos
> funcionais e não funcionais da sua aplicação. Se possível, agrupe as
> histórias de usuário por contexto, para facilitar consultas
> recorrentes à essa parte do documento.
>
> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Criar conta                             | ALTA | 
|RF-002| entrar                                  | ALTO |
|RF-003| Cadastrar coretoras e banco             | ALTA | 
|RF-004| simulaçao de investimento               | MÉDIA |
|RF-005| feed de noticias                        | BAIXO | 
|RF-006| geamficação                             | BAIXO |
|RF-007| analize de perfil                       | ALTA | 
|RF-008| plataforma de cursos                    | MÉDIA |
|RF-009| Análise de risco e lucratividade        | ALTA | 
|RF-010| gestão de investimentos                 | MÉDIA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

> Com base nas Histórias de Usuário, enumere os requisitos da sua
> solução. Classifique esses requisitos em dois grupos:
>
> - [Requisitos Funcionais (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
>   correspondem a uma funcionalidade que deve estar presente na
>   plataforma (ex: cadastro de usuário).
>
> - [Requisitos Não Funcionais (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
>   correspondem a uma característica técnica, seja de usabilidade,
>   desempenho, confiabilidade, segurança ou outro (ex: suporte a
>   dispositivos iOS e Android).
>
> Lembre-se que cada requisito deve corresponder à uma e somente uma
> característica alvo da sua solução. Além disso, certifique-se de que
> todos os aspectos capturados nas Histórias de Usuário foram cobertos.
> 
> **Links Úteis**:
> 
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


> Enumere as restrições à sua solução. Lembre-se de que as restrições
> geralmente limitam a solução candidata.
> 
> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)


# Projeto de Interface

......  COLOQUE AQUI O SEU TEXTO DE INTRODUÇÃO ......

> Apresente as principais interfaces da solução. Discuta como 
> foram elaboradas de forma a atender os requisitos funcionais, não
> funcionais e histórias de usuário abordados nas [Especificações do
> Projeto](#especificações-do-projeto).

## User Flow

......  INCLUA AQUI O DIAGRAMA COM O FLUXO DO USUÁRIO NA APLICAÇÃO ......

> Fluxo de usuário (User Flow) é uma técnica que permite ao desenvolvedor
> mapear todo fluxo de telas do site ou app. Essa técnica funciona
> para alinhar os caminhos e as possíveis ações que o usuário pode
> fazer junto com os membros de sua equipe.
>
> **Links Úteis**:
> - [User Flow: O Quê É e Como Fazer?](https://medium.com/7bits/fluxo-de-usu%C3%A1rio-user-flow-o-que-%C3%A9-como-fazer-79d965872534)
> - [User Flow vs Site Maps](http://designr.com.br/sitemap-e-user-flow-quais-as-diferencas-e-quando-usar-cada-um/)
> - [Top 25 User Flow Tools & Templates for Smooth](https://www.mockplus.com/blog/post/user-flow-tools)
>
> **Exemplo**:
> 
> ![Exemplo de UserFlow](images/userflow.jpg)


## Wireframes

......  INCLUA AQUI OS WIREFRAMES DAS TELAS DA APLICAÇÃO COM UM BREVE DESCRITIVO ......

> Wireframes são protótipos das telas da aplicação usados em design de interface para sugerir a
> estrutura de um site web e seu relacionamentos entre suas
> páginas. Um wireframe web é uma ilustração semelhante ao
> layout de elementos fundamentais na interface.
> 
> **Links Úteis**:
> - [Ferramentas de Wireframes](https://rockcontent.com/blog/wireframes/)
> - [Figma](https://www.figma.com/)
> - [Adobe XD](https://www.adobe.com/br/products/xd.html#scroll)
> - [MarvelApp](https://marvelapp.com/developers/documentation/tutorials/)
> 
> **Exemplo**:
> 
> ![Exemplo de Wireframe](images/wireframe-example.png)


# Metodologia

......  COLOQUE AQUI O SEU TEXTO ......

> Nesta parte do documento, você deve apresentar a metodologia 
> adotada pelo grupo, descrevendo o processo de trabalho baseado nas metodologias ágeis, 
> a divisão de papéis e tarefas, as ferramentas empregadas e como foi realizada a
> gestão de configuração do projeto via GitHub.
>
> Coloque detalhes sobre o processo de Design Thinking e a implementação do Framework Scrum seguido
> pelo grupo. O grupo poderá fazer uso de ferramentas on-line para acompanhar
> o andamento do projeto, a execução das tarefas e o status de desenvolvimento
> da solução.
> 
> **Links Úteis**:
> - [Tutorial Trello](https://trello.com/b/8AygzjUA/tutorial-trello)
> - [Gestão ágil de projetos com o Trello](https://www.youtube.com/watch?v=1o9BOMAKBRE)
> - [Gerência de projetos - Trello com Scrum](https://www.youtube.com/watch?v=DHLA8X_ujwo)
> - [Tutorial Slack](https://slack.com/intl/en-br/)

## Divisão de Papéis

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente a divisão de papéis e tarefas entre os membros do grupo.
>
> **Links Úteis**:
> - [11 Passos Essenciais para Implantar Scrum no seu Projeto](https://mindmaster.com.br/scrum-11-passos/)
> - [Scrum em 9 minutos](https://www.youtube.com/watch?v=XfvQWnRgxG0)


## Ferramentas

......  COLOQUE AQUI O SEU TEXTO - SIGA O EXEMPLO DA TABELA ABAIXO  ......

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro |  https://miro.com/XXXXXXX | 
|Repositório de código | GitHub | https://github.com/XXXXXXX | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | MavelApp ou Figma | https://figma.com/XXXXXXX | 

>
> Liste as ferramentas empregadas no desenvolvimento do
> projeto, justificando a escolha delas, sempre que possível.
> 
> As ferramentas empregadas no projeto são:
> 
> - Editor de código.
> - Ferramentas de comunicação
> - Ferramentas de diagramação
> - Plataforma de hospedagem
> 
> O editor de código foi escolhido porque ele possui uma integração com o
> sistema de versão. As ferramentas de comunicação utilizadas possuem
> integração semelhante e por isso foram selecionadas. Por fim, para criar
> diagramas utilizamos essa ferramenta por melhor captar as
> necessidades da nossa solução.
> 
> **Links Úteis - Hospedagem**:
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Crie seu Site com o HostGator](https://www.hostgator.com.br/como-publicar-seu-site)
> - [GoDady](https://br.godaddy.com/how-to)
> - [GitHub Pages](https://pages.github.com/)

## Controle de Versão

......  COLOQUE AQUI O SEU TEXTO ......

> Discuta como a configuração do projeto foi feita na ferramenta de
> versionamento escolhida. Exponha como a gerência de tags, merges,
> commits e branchs é realizada. Discuta como a gerência de issues foi
> realizada.
> A ferramenta de controle de versão adotada no projeto foi o
> [Git](https://git-scm.com/), sendo que o [Github](https://github.com)
> foi utilizado para hospedagem do repositório `upstream`.
> 
> O projeto segue a seguinte convenção para o nome de branchs:
> 
> - `master`: versão estável já testada do software
> - `unstable`: versão já testada do software, porém instável
> - `testing`: versão em testes do software
> - `dev`: versão de desenvolvimento do software
> 
> Quanto à gerência de issues, o projeto adota a seguinte convenção para
> etiquetas:
> 
> - `bugfix`: uma funcionalidade encontra-se com problemas
> - `enhancement`: uma funcionalidade precisa ser melhorada
> - `feature`: uma nova funcionalidade precisa ser introduzida
>
> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
> - [5 Git Workflows & Branching Strategy to deliver better code](https://zepel.io/blog/5-git-workflows-to-improve-development/)
>
> **Exemplo - GitHub Feature Branch Workflow**:
>
> ![Exemplo de Wireframe](images/Github-Workflow.png)

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

......  COLOQUE AQUI O SEU TEXTO ......

## Tecnologias Utilizadas

......  COLOQUE AQUI O SEU TEXTO ......

> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.
> 
> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
