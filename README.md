# Análise de clientes AdventureWorks 2022
Utilizando o banco de dados AdventureWorks, empresa imaginária de fabricação e venda de bicicletas, iniciamos uma análise para entender as principais regioes e países , principalmente entre 2011 e 2014. O objetivo inicial é fazer uma análise exploratória dos grupos territóriais que compraram os produtos da AdventureWorks, entendendo a quantidade de entregas, quanto e o que compram, se houve evolução na base de novos clientes e onde está o maior impacto desta evolução.

Fazendo o download do arquivo AdventureWorksDW2022.bak e anexando-o no SQL Server, é possível visualizar o diagrma de dados, podendo entender as relações entre a tabela fato e as tabelas dimensão.
<br><br>

## Visualisando o diagrama 
<img align="right" width="500"  src="https://github.com/MatheusVDSN/Portifolio_AdventureWorks/blob/main/Imagens/diagrama_dados_Internet_Sales.JPG?raw=true">
Iniciamos o projeto entendendo cada objeto, tabela, campo, tipos de dados e relacionamentos do modelo de dados AdventureWorks. Após identificar a tabela de clientes e vendas, desenvolvemos os scripts em SQL para explorar os dados e extrair os primeiros insights durante a análise exploratória de dados. Como por exemplo: <br><br>
- Groupo Territórial <br>
- Principais Países <br>
- Categoria de Produtos <br>
<br><br>

<br><br>

## Criando tabela Calendário
<img align="left" width="500" height="320" src="https://github.com/MatheusVDSN/Portifolio_AdventureWorks/blob/main/Imagens/power_query_crinando_dimCalendario.JPG?raw=true">
Após a importação dos dados foi necessário criar uma tabela dimensão referente as datas de análise, com o uso de power query foi possível criar uma tabela para o uso de parâmetros internos e um modelagem na demonstração dos dados.


<br><br><br><br>

<br><br><br><br>

## Medidas
<img align="right" width="500" height="320" src="https://github.com/MatheusVDSN/Portifolio_AdventureWorks/blob/main/Imagens/tabela_medidas_AdvW_ed.png?raw=true">
Identificado a necessidade do cliente, as regras de negócio e a aplicação das mesmas no modelo de dados, iniciamos o desenvolvimento.
Principais medidas desenvolvidas;
 - Custos, Receitas, Lucro, Entregas
 -  Medidas de inteligência temporal para comparação de performance e resultados entre períodos distintos ou cumulativos.
Para organizar as medidas, criamos uma tabela contendo todas as medidas, sempre seguindo a padronização dos nomes.

<br><br>

<br><br>

## Conclusão técnica SQL
Com o SQL, podemos analisar, extrair, manipular e exibir os dados de uma base de dados de uma forma simples e rápida, apenas conectando direto na fonte dos dados. Porém, não é uma ferramenta dinâmica em com abordagem visual, pois cada vez que pricisa ver os dados de uma forma diferente, precisa reescrever o comando SQL para extrair os dados da forma que gostaria, porem os dados sempre serão exibidos em formato de tabela, deixando sua análise menos dinamica do que um dashboard, por exemplo.

A minha conclusão é que o SQL é sempre uma linguagem muito importante e deve ser utilizada para analisar um banco de dados antes de escolher outra ferramenta para análise dos dados, como o Power BI por exemplo. Ou seja, valide as informações no SQL e só depois considere outras ferramentas de acordo com a necessidade da empresa ou projeto que estiver atuando.
Não existe uma ferramenta melhor que a outra, existe ferramentas adequadas as necessidades apresentadas em cada projeto de dados.

<br><br>

## Dashboard Power BI
<img align="right" width="500"  src="https://github.com/MatheusVDSN/Portifolio_AdventureWorks/blob/main/Imagens/Adventure_print.JPG?raw=true">
Seguindo a idéia que SQL não é a melhor ferramenta para uma análise dinâmica e visual de informações, desenvolvi um dashboard focado na análise dos clientes novos e recorrentes da mesma base de dados AdventureWorks.
Como o Power BI permite análises dinâmicas e visuais de forma simples, escrevendo menos código DAX e permitindo o usuário total interação com a ferramenta, fiz uma análise exploratória na quantidade e receira entre novos e recoreente.<br>
Com esta análise, chegamos as seguintes conclusões:<br>
 - A maioria dos clientes a partir de 2013 é novo. <br>
 - Além da quantidade de clientes novos, a receita trazida por clientes novos também é a maior fatia do total.<br>
 - Os clientes novos não são a maioria para todos países e períodos. Por isso o Power BI é uma ferramenta de extrema importância, pois permite o usuário final fazer seus filtros e ter análises de forma dinâmica.
<br><br>
<a href=""_blank">Clique aqui</a> e acesse o a solução desenvolvida para a empresa AdventureWorks.
<br>
<a href="https://github.com/MatheusVDSN/Portifolio_AdventureWorks/blob/main/PowerBI/Projeto%20AdventureWorks.pbix" target="_blank">Clique aqui</a> e acesse o arquivo .pbix no Github.
<br><br>

## Ferramentas e linguagens utilizadas
<div style="display: inline_block">
    <img align="center" alt="SQL" height="40" width="40" src="https://github.com/BruceFonseca/ferramentas/blob/main/logo.png?raw=true">
    <img align="center" alt="Power BI" height="40" width="40" src="https://github.com/BruceFonseca/ferramentas/blob/main/1200px-New_Power_BI_Logo.svg.png?raw=true">
</div>
