# DSA - Fundamentos de Engenharia de Dados

## O que é Engenharia de Dados?

![whats-data-engineering](https://github.com/Vinicius999/DSA-Fundamentos-de-Engenharia-de-Dados/blob/main/images/whats-data-engineering.png)

**Engenharia de Dados** é um conjunto de técnicas e procedimentos para tornar os dados disponíveis para uso em um formato utilizável.


## Perfil do Engenheiro de Dados

- Os  Engenheiros  de  Dados  devem  entender  os  conceitos  fundamentais  em  ciência  da computação e devem ser bem versados na construção e concepção de aplicações em grande escala; de ponta a ponta.

- Eles devem entender os prós e os contras da utilização de bancos de dados relacionais e NoSQL, eles devem saber como projetar soluções para casos de uso com dados em lote (Batch) e fluxo contínuo (Streaming de Dados), eles devem saber o que é preciso para operacionalizar um  modelo  preditivo  e  como  ajudar  a  publicar  esses  modelos  criados  no  “laboratório” (treinamento e validação) para aplicações em tempo real.

- Eles  devem  entender  a  computação  distribuída  e  ambientes  em  cluster  e  devem  ser capazes de trabalhar com o Cientista de Dados e Engenheiro de IA para ajudar a construir a infraestrutura de armazenamento e processamento de dados.

- Eles  devem  saber  quando  definir  esquemas  para  o  aplicativo  a  fim  de  implementar projetos de “Data Lakes” que ajudem na análise em grande escala, mas ainda atendam aplicativos específicos dedomínio.

- Eles devem ainda conhecer sobre governança e segurança de dados e eles devem estar muito familiarizados com as principais tecnologias que são usadas para construir esses sistemas.

- Para  trabalhar  como Engenheiro  de  Dados é  preciso  ter  perfil  técnico,  gostar  de computação,  dominar  o  uso  de  sistemas  operacionais  (especialmente  Linux)  e  desenvolver habilidades nas técnicas, procedimentos e ferramentas usados em engenharia de dados.


## Engenheiro de Dados x Cientista de Dados

Antes de mais nada, compreenda que Cientistas de Dados e Engenheiros de Dados são profissionais  diferentes,  com  perfis  diferentes  e  que  usam  essencialmente  ferramentas diferentes.

É claro que nada impede que um único profissional tenha habilidades para exercer as duas funções e em empresas menores ou Startupsisso será uma realidade.Mas compreender as diferenças ajuda a definir o perfil adequado de cada profissional.

O  Cientista  de  Dados  desenvolve  modelos  e  realiza  análises  usando  Matemática, Estatística, Programação e Machine Learning para explicar e prever comportamentos complexos, resolvendo problemas das áreas de negócio, no mundo real.

Um  Engenheiro  de  Dados  projeta  e  constrói  arquiteturas  de  dados  e  pipelines  para ingestão, armazenamento, processamento e execução de aplicações de grande escala com Big Data.“Ciência de Dados” e “Machine Learning” (ML) são disciplinas relacionadas a projetos que tendem a ser concluídos por indivíduos com títulos como “Cientista de Dados”.

Os Cientistas de Dados geralmente estão acostumados a trabalhar com todos os tipos de dados e podem usar os mesmos Data Lakes e várias ferramentas de preparação de dados que os Engenheiros de Dados usam.

No entanto, os Cientistas de Dados geralmente transformam seus dados com o objetivo final de lidar com a Ciência de Dados ou problemas de ML, enquanto os Engenheiros de Dados estão mais interessados em criar processos de engenharia para dar suporte a outras partes da empresa.

Embora possam usar as mesmasferramentas os propósitos são diferentes. Engenheiros de Dados estão preocupados com o fluxo de dados. Cientistas de Dados estão preocupados com o processo científico de análise dos dados e Machine Learning.

Os Engenheiros de Dados geralmente coletam dados de diferentes fontes, transformam os  dados  em  diferentes  formatos  e,  em  seguida,  entregam  os  dados  aAnalistas  de  Dados,Cientistas de Dados ou Engenheiros de IA. Essa “entrega” pode se dar por meio de repositórios de  dados  como  Data  Warehouses  e  Data  Lakes,  por  meio  de  APIs  de  acesso,  por  meio  de containers, por meio de pipelines ou outras opções.


## Engenheiro de Dados x Arquiteto de Dados

De acordo com o Data Management Body of Knowledge da DAMA International, um Arquiteto de Dados “fornece um vocabulário de negócios comum padrão, expressa requisitos estratégicos, descreve projetos integrados de alto nível para atender a esses requisitos e se alinha com a estratégia corporativa e a arquitetura de negócios de uma empresa”.

Um Arquiteto de Dados entende as necessidades de negócios, explora a estrutura de dados existente e cria um projeto para construir uma estrutura integrada de dados segurose facilmente acessíveis, alinhados com a estratégia de negócios.

O Arquiteto de Dados também define  os  processos  envolvidos  no  teste  e  manutenção  de  bancos  de  dados  e  sistemas  de armazenamento.

As funções de Arquiteto de Dados e Engenheiro de Dados são comumente confundidas e, pior, usadas de forma intercambiável. 

Mas o papel de um Arquiteto de Dados é diferente do papel de um Engenheiro de Dados (embora existam algumas similaridades).

Neste debate entre Arquiteto de Dados e Engenheiro de Dados, enquanto o primeiro projeta e planeja a estrutura de dados, o segundo coloca esse projeto em ação para construir a infraestrutura de dados de uma empresa.

Um Arquiteto de Dados leva em conta todas as fontes de dados relativas às operações de negócios e descreve um projeto para integrar, centralizar e manter os dados. 

Por outro lado, um Engenheiro de Dados é responsável por construir e testar arquiteturas de dados sustentáveis para  a  organizaçãopara  facilitar  a  busca  e  recuperação  de  dados. 

Os  Arquitetos  de  Dados trabalham em estreita colaboração com os Engenheiros de Dados para criar uma arquitetura de dados sólida.

De forma simples e resumida: O Arquiteto de Dados projeta e o Engenheiro de Dados executa.

Se  uma  empresa  não  tem  um  Arquiteto  de  Dados é  comum  o  Engenheiro  de  Dados realizar o trabalho de projetar e planejar a solução de dados.



## O que é um Pipeline de Dados?

<img src="https://9013214.fs1.hubspotusercontent-na1.net/hubfs/9013214/imagem-pt-Artigo-de-Blog--Pipeline-de-dados.jpg"></img>

**Pipeline de Dados** é um meio de mover os dados de uma origem até o seu destino. Ao longo do caminho, são aplicadas transformações nesses dados com o objetivo de deixar os dados no formato ideal para para o seu destino.


## O que é CI/CD (Integração Contínua / Entrega Contínua) ?

CI/CD (integração contínua e entrega contínua) é uma abordagem de desenvolvimento de  software  em  que  todos  os  desenvolvedores  trabalham  juntos  em  um  repositório compartilhado de código e, à medida que as alterações são feitas, há um processo de build automatizado  para  detectar  problemas  de  código.  O  resultado  é  um  ciclo  de  vida  de desenvolvimento mais rápido e uma taxa de erro menor.

Um pipeline de CI/CD automatiza os dois processos a seguir para um processo de entrega de software de ponta a ponta:

**Integração contínua para criação e teste de código automatizado.** A CI permite que os desenvolvedores enviem várias alterações para um repositório compartilhado ou repositório de código  principal,  mantendo  o  controle  de  versão.  Muitas  equipes  de  desenvolvimento  de software estão geograficamente dispersas ou isoladas, mas a CI permite um desenvolvimento rápido, evitando conflitos de mesclagem, bugs e duplicação. A CI sempre mantém o repositório. principal  atualizado,  mas  também  pode  facilitar repositóriosisolados  de  curto  prazo  ou  de recursos  para  alterações  menores  que  podem  eventualmente  ser  mescladas  no repositórioprincipal.

**Entrega contínua (ou implantação contínua) para lançamentos de código.** O CD permite o desenvolvimento incremental de ciclo curto e permite que as equipes de desenvolvimento criem e liberem software a qualquer momento. Também ajuda as equipes devops a reduzir custos e acelerar a implantação de novos lançamentos. O CD requer uma estrutura altamente repetível e é frequentemente considerado uma extensão do CI.

Um pipeline de CI/CD combina criação, teste e implantação de código em um processo contínuo,  garantindo  que  todas  as  alterações  no  código  do repositório principal  possam  ser liberadas para produção. Um pipeline automatizado de CI/CD evita erros manuais, fornece loops de feedback padronizados para desenvolvedores e permite iterações rápidas de software. O conceito de CI/CD está cada vez mais sendoaplicadoem Engenharia de Dados criando o que hoje chamamos de DataOps, com a operaçãocontínua da plataforma de dados.

## Pipeline ETL x Pipeline de Dados x Pipeline de Machine Learning

![Pipeline de Dados x Pipeline ETL x Pipeline de Machine Learning](https://github.com/Vinicius999/DSA-Fundamentos-de-Engenharia-de-Dados/blob/main/images/pipelies.png)

## A importância da Arquitetura de Pipelines de Dados

Sempre iniciamos um projeto de pipeline de dados pela **compreensão dos requisitos de negócio** e o que se esperado uso de dados no dia a dia.

## Comece a Arquitetura de Pipelines de Dados por essas Perguntas

1. Quais são os requisitos de negócios?
2. Quais os resultados finais são necessários?
3. Os dados estão disponíveis? Quais são as fontes?
4. Quais tipos de formatos de dados estão disponíveis?
5. Qual o crescimento esperado do volume de dados?
6. Quanto de armazenamento será necessário?
7. Quanto de capacidade computacional será necessário?
8. Usaremos em batch, em streaming ou ambos?




