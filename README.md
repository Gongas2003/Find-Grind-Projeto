## **CURSO DE ENGENHARIA INFORMÁTICA**

# **Find&Grind**

**RELATÓRIO - PRIMEIRA ENTREGA**

_Gonçalo Alves 20210544_

_Guilherme Afonso 20211109_

_Rui Esteves 20210958_

**LISBOA**

[_https://github.com/Ruie8/Projeto-mov-l-Find-Grind/projects?query=is%3Aopen_](https://github.com/Ruie8/Projeto-mov-l-Find-Grind/projects?query=is%3Aopen) **OUTUBRO, 2022**

## **Introdução**

Decidimos desenvolver uma aplicação, em que o objetivo principal consiste em dar a conhecer à população as várias Power stations perto de si. Com esta aplicação tencionamos promover o treino ao ar livre de modo a que seja acessível e prático a todos, independentemente da disponibilidade financeira. Para além disso tencionamos também resolver o problema da falta de informação destas zonas de treino. Vamos também criar planos de treino consoante as máquinas existentes na Power station escolhida pelo utilizador. Os treinos para segurança dos utilizadores serão fornecidos com base em sites e aplicações verificadas por profissionais.

**Objetivos e motivação para realizar o trabalho**

Como temos em comum o hábito de praticar desporto decidimos dedicar-nos a este tema. O grande objetivo desta aplicação é facilitar o acesso à localização das Power Stations e a informação das máquinas existentes nas estações.

Pretendemos recolher a informação física dos utilizadores de modo a recomendarmos os exercícios mais apropriados de cada máquina consoante os dados coletados pela aplicação.

**Identificação do nosso publico alvo**

A nossa aplicação é focada no grupo de pessoas que têm como objetivo treinar num ambiente natural independentemente da sua faixa etária e da disponibilidade horária.

**Pesquisa e comparação com o atual mercado**

Através de uma pesquisa aprofundada, entendemos que o mercado que estamos a explorar encontra-se muito vago, sendo que a única aplicação que se aproxima da nossa, Kompan Outdoor Fitness, é devidamente focado na United Kingdom. Apesar das parecenças entre ambas as aplicações, o nosso mercado é focado em encontrar e localizar os espaços ao ar livre, tanto como ajudar a perceber a cada utilizador o que é mais aconselhado em cada treino. Com outros campos a debater, não encontramos qualquer tipo de facilidade ou informação em relação a estes espaços verdes, sendo disponível apenas um site com algumas destas localizações.([https://www.nit.pt/fit/ginasios-e-outdoor/10-ginasios-gratuitos-em-lisboa-para-quem-quer-ficar-em-forma-ao-ar-livre/attachment/859507](https://www.nit.pt/fit/ginasios-e-outdoor/10-ginasios-gratuitos-em-lisboa-para-quem-quer-ficar-em-forma-ao-ar-livre/attachment/859507)). Já existindo muitas aplicações com treinos generalizados e ao ar livre, decidimos também que apenas sugerimos treinos para as máquinas disponíveis em cada estação, sendo muito difícil também encontrar no mercado uma aplicação igualmente disponível. Existindo diversas aplicações com esta função, encontramos a utilidade para cada utilizador já que facilita o desempenho em cada caso.

**Passo a Passo (Mockups)**

Neste tópico temos um protótipo de como a aplicação irá ser

![](RackMultipart20221023-1-nqwbmk_html_3075955cc282805e.png) ![](RackMultipart20221023-1-nqwbmk_html_3aeb05605ab35fee.png)

1- Página de Introdução 2- Registo do Utilizador

![](RackMultipart20221023-1-nqwbmk_html_3df3ec75828f5995.png)

3- Mapa da Aplicação

![](RackMultipart20221023-1-nqwbmk_html_59b80c427ecaadfe.png)

4- Desenvolvimento após pressionar a PowerStation

**Guiões**

1. Um adolescente de 16 anos procura um lugar onde possa treinar com o seu peso corporal e sem gastar dinheiro. Sabendo que existem Power Stations, decide então pesquisar por uma aplicação que identifique os locais exatos das mesmas. Encontra a App Find&Grind na qual após se registar são apresentadas, não só as zonas de treino, como também planos de exercícios adequados para a sua idade, peso e altura. **Parte superior do formulário**
2. Um jovem adulto com 28 anos, com gosto por atividade física ao ar livre quer encontrar uma PowerStation perto da sua casa para poder treinar sem qualquer compromisso financeiro. Por isso abre a aplicação e consegue localizar várias PowerSations na zona onde mora. Escolhe uma estação conforme a sua avaliação e estado das máquinas e tem acesso a uma plano de treino recomendado pela aplicação, que o faz com base nos dados inseridos pelo jovem-adulto. Após realizar o treino poderá deixar a sua avaliação das máquinas que usou e da zona em que se encontra a PowerStation.Parte inferior do formulário
3. Uma idosa de 60 anos decide que quer voltar à atividade física com peso natural, ao ar livre e sem o receio de se magoar. Então abre a aplicação Find&Grind na qual são localizadas as zonas de treino existentes ao seu redor com planos de treino adequados para a sua idade. Será também apresentada a avaliação dos equipamentos nas Power Stations, de forma a assegurar a utilizadora que não se irá magoar devido ao possível mau estado dos equipamentos.

**Enquadramento nas diversas unidades curriculares.**

A nossa aplicação apresenta a necessidade de uma base de dados, que está relacionado com a nossa cadeira base de dados, de forma que todos os dados recolhidos sejam ordenados e armazenados. Sendo uma aplicação mobile, terá de ter uma interface principal seguida das restantes, tudo enquadrado em programação de dispositivos moveis. Também dentro do relatório aplicamos os conteúdos aprendidos em competências comunicacionais, sendo tudo isto possível apenas com a programação dada em programação orientada a objetos.

**Arquitetura da Solução**

A aplicação que estamos a desenvolver irá ter uma larga informação fornecida ao utilizador e para tal acontecer iremos ter como arquitetura as seguintes áreas:

-Base de dados

-Backend Api

-Frontend/Aplicaçao Android

Ligando a base de dados à Backend Api, é necessário que seja uma conexão rápida e com disponibilidade de armazenamento. O armazenamento terá que ser organizado da melhor forma para o backend responder a serviços da Frontend da forma mais rápida e fácil possível.

**Armazenamento**

Vamos precisar de um armazenamento constante visto que a nossa aplicação funciona a base de todos os dados inseridos pelos utilizadores em que esses mesmos dados terão que ser armazenados. Para otimizar a segurança do utilizador a base de dados não terá qualquer ligação com o exterior apenas com o Backend.

**Backend API**

Na backend API vamos desenvolver os pedidos vindos da Frontend para desenvolver uma resposta. Vai ter obrigatoriamente uma conexão constante com a base de dados e possivelmente com outros serviços.

**Frontend/Aplicação Android**

A frontend irá ser onde se desenvolve as partes gráficas e vistas pelo utilizador para além disso vai também ser onde se vai emitir os pedidos de resposta à Backend e consequentemente à base de dados.

**Requisitos Técnicos para desenvolvimento do projeto**

Para o desenvolvimento da nossa aplicação, vamos precisar de utilizar diversas competências aprendidas.

Linguagem Java para desenvolvimento do Backend.

SQL para configuração e manuseamento da nossa Base de Dados

Programação Móvel para o desenvolvimento da aplicação e do Frontend.

**Tecnologias a Usar**

Base de Dados – PostgreSQL

Backend API - SpringBoot

Frontend - Android Studio

Design – Android Studio

**Planeamento e calendarização**

![](RackMultipart20221023-1-nqwbmk_html_52770ee4beb666ea.png)

A calendarização está dividida em 3 fases Base de Dados, Backend e Frontend.

**Bibliografia**

- NIT

[https://www.nit.pt/fit/ginasios-e-outdoor/10-ginasios-gratuitos-em-lisboa-para-quem-quer-ficar-em-forma-ao-ar-livre/attachment/859507](https://www.nit.pt/fit/ginasios-e-outdoor/10-ginasios-gratuitos-em-lisboa-para-quem-quer-ficar-em-forma-ao-ar-livre/attachment/859507)

- KOMPAN

https://www.kompan.com/products/outdoor-fitness

-KHALISTHENICS PARKS

[https://calisthenics-parks.com/cities/386-pt-lisboa](https://calisthenics-parks.com/cities/386-pt-lisboa)

-SAPO LIFE

https://lifestyle.sapo.pt/saude/fitness-e-bem-estar/artigos/3-locais-em-lisboa-para-a-deixar-em-forma
