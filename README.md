<h1>Projeto de Introdução à Ciência de Dados - CCF 425</h1>

<h2>Introdução</h2>

<p>Neste projeto, realizaremos um estudo baseado no conjunto de dados BrStats, disponibilizado pelo Prof. Fabrício e pelo monitor João Marcos, além de quatro outros conjuntos de dados selecionados pelo grupo (casos_2020, casos_2021, casos_2022 e casos_2023). O objetivo é analisar os impactos da pandemia de Covid-19 no Brasil e investigar possíveis relações entre as características socioeconômicas das cidades e o nível de impacto da pandemia.
  <p>O primeiro conjunto de dados, "BrStats: A Socioeconomic Statistics Dataset of the Brazilian Cities", contém informações estatísticas sobre cidades brasileiras, compiladas a partir de fontes como IBGE, IPEA e DATASUS. Entre os indicadores disponíveis, destacam-se o PIB, a população, as receitas municipais, além de dados sobre nascimentos e óbitos infantis, entre outros fatores que ajudam a compreender o desenvolvimento dessas localidades.
  <p>Diante da pandemia global da Covid-19, que impactou todas as regiões do mundo, este estudo busca explorar como diferentes cidades brasileiras foram afetadas. Com base nos dados coletados, investigaremos se há correlação entre as características socioeconômicas das cidades e a severidade dos impactos causados pela pandemia, contribuindo para uma melhor compreensão dos fatores que influenciaram a propagação e os efeitos da doença no Brasil.
  <p>Os dados podem ser obtidos no link do Google Drive a seguir (devido o tamanho dos DataSets, até o presente momento não conseguimos realizar o upload destes no GitHub) - <a href="https://drive.google.com/drive/folders/1reVgUutym0oAZyLWJj-xaypdwteC4XuW?usp=drive_link">Clique Aqui</a></p>

<h2>Divisão das Tarefas entre os Membros da Equipe</h2>
<h3>Entrega 01:</h3>

- Henrique Alves: Elaboração de algumas perguntas;
- Marcos Biscotto: Elaboração de algumas perguntas e Análises Inicias;
- Matheus Nogueira: Elaboração de algumas perguntas;
- Matheus Peixoto: Obtenção dos Dados, Análises Iniciais e Organização do GitHub;

<h3>Entrega 02:</h3>

 - Henrique Alves: Elaboração de alguns gráficos;
 - Marcos Biscotto: Reorganização de parte do Notebook conforme as observações passadas à equipe, Elaboração de alguns gráficos e Reformulação de Perguntas;
 - Matheus Nogueira: Elaboração de alguns gráficos;
 - Matheus Peixoto: Reorganização de parte do Notebook conforme as observações passadas à equipe e GitHub;

<h3>Entrega 03:</h3>

- Henrique Alves: Análises referente à terceira entrega 
- Marcos Biscotto: Melhoria da formatação do texto e correção do Markdown, reorganização da estrutura do notebook, melhoria na legibilidade e refatoração de alguns gráficos.
- Matheus Nogueira: Análises referentes à terceira entrega
- Matheus Peixoto: Organização do notebook, alguns testes pra análises dessa terceira entrega como inferências e outras estatísticas

<h3>Entrega 04: </h3>

- Henrique Alves: Análises referentes à quarta entrega <br>
- Marcos Biscotto: Organização do notebook e análises referentes à quarta entrega <br>
- Matheus Nogueira: Análises referentes à quarta entrega <br>
- Matheus Peixoto: Completa revisão e reorganização do notebook entre terceira e quarta entrega; correções quanto ao tratamento de algumas colunas dos datasets extras referentes à COVID; "Análise da Relação entre População e Número de Nascimentos nas Cidades Brasileiras por meio de Regressão Linear" <br>

<h2>Perguntas a serem respondidas</h2>

<p>Nessa seção apresentaremos algumas perguntas que foram elaboradas pelo grupo e serão analisadas no decorrer do Projeto.
<p>Como explicitado na introdução, muitas dessas perguntas tentarão responder e encontrar uma correlação entre as características das cidades e o impacto que a pandemia de COVID-19 gerou nestas.
<p>Além das perguntas voltadas a esta temática, algumas outras serão apresentadas, que representam mais algumas curiosidades dos integrantes do grupo, como algumas envolvendo as cidades-natal destes (Caratinga, Itaúna, Pará de Minas e Ubá, todas de Minas Gerais).


01.   Quais cidades registraram os maiores números absolutos de óbitos infantis e as maiores razões de óbito/nascimento infantil durante a pandemia (2020-2021)?

02.   Qual foi a variação no número total de empresas entre o período pré-pandemia (2016-2019) e o período pandêmico (2020-2021)? Que conclusões podemos extrair dessa análise?

03.   Qual a soma dos maiores valores de produção agrícola por cidade no período pré-pandêmico (2016-2019) comparado ao período pandêmico (2020-2021)?

04.   Quais cidades apresentaram a menor eficiência agrícola (razão entre área colhida e área plantada) durante a pandemia (2020-2021) e como isso se compara ao período anterior (2016-2019)?

05.   Considerando as 10 cidades com maior produção pecuária no período pré-pandêmico, qual foi a variação na produção dessas cidades durante a pandemia?

06.   Como o crescimento do PIB dos municípios brasileiros entre 2018 e 2019 se comportou em relação a 2020 e 2021, período pandêmico?

07.   Existe correlação entre receitas municipais e indicadores de qualidade de vida, como mortalidade infantil?

08.   Há relação direta entre área plantada/colhida e valor total da produção agrícola?

09.   Municípios com maior volume de exportações apresentam melhores indicadores econômicos?

10.   Qual foi o impacto da pandemia nos fluxos de importação e exportação por região?

11.   Quais foram os valores extremos (máximos e mínimos) de PIB, importações e exportações nas cidades de Caratinga, Itaúna, Pará de Minas e Ubá durante a pandemia (2020-2021)?

12.   Como se comparam as taxas de letalidade (deaths_by_totalCases) nas cidades-natal dos integrantes do grupo em relação aos seus PIBs?

13.   Qual porcentagem da população foi infectada por COVID-19 anualmente nas cidades-natal dos integrantes?

14.   Qual a mortalidade por COVID-19 nas 10 cidades com maior e menor PIB? Existe correlação entre PIB e mortalidade?

<h2>Desenvolvimento</h2>

<p>Por meio de reuniões realizadas com a equipe, utilizando o Google Colab como ferramenta de desenvolvimento e GoogleMeet e WhatsApp para comunicações, realizamos o desenvolvimento dessa primeira entrega do Projeto de Introdução à Ciência de Dados (CCF425).</p>
<p>Nessa primeira entrega nos dividimos entre obtenção e tratamento inicial dos dados, organização e criação das perguntas</p>

<h2>Conclusões</h2>

<p>Os conjuntos de dados que temos acesso são bastante ricos, permitindo explorá-los de diferentes modos.</p>
<p>Com o andamento do Projeto poderemos realizar muitas análises, visando responder essas perguntas iniciais que desenvolvemos.</p>

<h2>Integrantes do Projeto</h2>

<h3>Alunos</h3>

 - [Matheus Peixoto - 4662](https://github.com/MatheusPxt21)
 - [Matheus Nogueira - 4668](https://github.com/MatheusNogueiraUfv)
 - [Marcos Biscotto - 4236](https://github.com/Kamagori)
 - [Henrique Alves - 4231](https://github.com/alveshenriique)

<h3>Monitor do Projeto</h3>

 - [João Marcos A. M. Ramos](https://github.com/raitocan)

<h3>Professor da Disciplina</h3>

 - [Fabricio Aguiar Silva](https://github.com/fabaguiarsilva)
