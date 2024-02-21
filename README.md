# Power BI: Projeto Gatito
# Diagrama do Projeto: 
![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/9723b44d-c163-4398-824f-4821b6c93937)


***O principal objetivo do Business Intelligence (BI) é coletar, integrar e processar dados de várias fontes. Essa atividade permite que a empresa obtenha insights relevantes e valiosos, que podem ser utilizados para embasar decisões estratégicas e impulsionar o desempenho do negócio***
## _Análise detalhado do passo a passo_

***O primeiro passo quando precisamos desenvolver algum projeto ou construir um dashboard para um(a) cliente ou empresa para a qual trabalhamos é: entender o que essa pessoa quer visualizar.
Para isso, precisamos de dois elementos:
Base de dados: para extrair métricas e fazer cálculos para construir os visuais;
Prioridades da empresa: entender o que é mais relevante e o que a empresa quer visualizar.***

***Portanto, ao questionar a Cliente sobre esses pontos em relação a empresa, ela disse que era muito importante saber sobre o faturamento do negócio.
A Cliente quer fazer um controle do faturamento dos últimos anos para entender se o negócio está crescendo ou se precisa fazer algum tipo de ajuste.
Além de visualizar o faturamento total do negócio, ela quer que seja disponibilizado o faturamento filtrado por marca. Dessa forma, ela pode saber quais são as marcas que mais vendem dentro do Petshop.
Ela também quer visualizar os produtos disponíveis, ou seja, fazer um controle de estoque. Assim, evita-se que falte determinado produto para a clientela do Gatito enquanto outro produto tem um estoque excessivo.
Além disso, a Cliente quer saber o gênero que mais compra na loja, porque quer fazer algumas campanhas de marketing mais direcionadas. Assim, ela vai saber como está a divisão. Será que tem um gênero que compra mais que outro?
Ela quer descobrir qual a média de pets da clientela. Será que essas pessoas têm 1, 2 ou mais animais de estimação? Isso impacta na quantidade de produto que a Gatito vai comprar.
Base de dados***

***A Cliente quer fazer esse levantamento, pois pretende abrir novas lojas e crescer seu negócio. Para isso, ela precisa tomar decisões baseadas nesses dados.
Portanto, a Cliente vai nos disponibilizar algumas bases de dados da Gatito sobre:***

+ ***Clientes: arquivo no formato txt (texto);*** 
+ ***Produtos: arquivo no formato do Google Sheets (Google Planilhas);*** 
+ ***Vendas: arquivos em uma pasta de trabalho do Excel.***

## _Importando a primeira base: arquivo TXT._

## _A primeira base foi importada através da fonte de TEXTO/CSV_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/bd17f13a-f48d-4144-92df-7527c47257cb)


## _Através dessa conexão, foi importado o arquivo de Clientes:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/b53cefb6-5d17-4577-82de-5751f52bdb77)


## _Ao selecionar os arquivos, uma janela contendo a prévia dos dados apareceu e clicamos em Transformar Dados:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/385a8d26-e6f5-4e81-b83b-2888f017293f)


## _Ao clicar em Transformar Dados, fomos direcionados para o Editor do Power Query:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/2cb0b86b-1afc-4616-99e4-196bd840bff0)


# _Importando a segunda base: planilha online_

## _A segunda base foi importada através da conexão do tipo Web:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/8ee7ae0b-474e-4572-b984-32cb559552d8)


## _Ao clicar em Conectar, fomos direcionados para uma janela onde devemos inserir o link da planilha compartilhada:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/42f8d946-65f5-44cf-ade5-bd076a49f8be)


## _Após adicionarmos o link, fomos direcionados para a janela com a prévia da tabela, onde escolhemos a primeira opção e clicamos em Transformar Dados:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/9c5044e7-fa5a-43ed-a95e-e0a814060598)


# _Importando a terceira base: pasta_

## _Por fim, realizamos a importação da terceira base através da conexão do tipo Pasta:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/3a803cea-e1ac-4d23-9604-902d5068fa38)

## _Ao clicar em conectar, escolhemos a pasta de Vendas no nosso computador e, em seguida, fomos direcionados para a prévia da pasta e clicamos em Combinar e Transformar Dados:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/87f7d2ad-2848-4331-b5dd-ba64098ecdf5)


## ***Após clicar em Combinar e Transformar Dados, fomos direcionados para a prévia da tabela completa, onde escolhemos a primeira opção:***


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/5e9bdbb8-09da-4540-b180-cb0796c5c86c)


### _Com isso, finalizamos as importações dos dados para o projeto do pet shop Gatito no Powerw BI_

### _Nessa etapa foi feito os seguintes pontos:_

+ ***Compreender o que é business intelligence e a sua importância;***
+ ***Compreender o que é o Power BI Desktop;***
+ ***Realizar uma conexão com o arquivo do tipo Texto/CSV;*** 
+ ***Realizar uma conexão de um arquivo do Google Sheets;*** 
+ ***Realizar uma conexão de um arquivo do Excel;*** 
+ ***Fazer uma conexão de uma pasta com vários arquivos do Excel.*** 

## ***Ao relacionar as tabelas de Clientes e de Vendas, encontramos o seguinte aviso:***


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/08265629-2393-41b6-be3f-b8200081249b)


## _Como a tabela de Clientes possui campos nulos, não foi possível realizar o relacionamento. Para isso, tivemos que acessar o Editor do Power Query para remover os valores nulos:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/3f6a68aa-3b75-4cc9-ba02-0671c2c1df1b)


## _Após realizar esse tratamento, foi possível relacionar as tabelas de Clientes e Vendas:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/f07e5f74-92d2-46ba-9e9f-8ccb21173ac8)


# _Adicionando colunas_

## _Após realizarmos o relacionamento entre as tabelas, utilizando a linguagem DAX, adicionamos mais duas colunas à tabela de Vendas, sendo a primeira a coluna de Valor, como podemos verificar abaixo:_ 


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/0865eceb-8a9c-4019-8cfa-20dce3bb5636)


### _A seguir temos o código em DAX para criar a coluna Valor:_

## *Valor = LOOKUPVALUE(Produtos[Valor],Produtos[ID Produto],Vendas[ID Produto])*


## _A segunda coluna criada foi a de Faturamento:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/af539a4a-f2a9-42f1-842a-ff90b5ad8639)


### _A seguir temos o código em DAX para criar a coluna Faturamento:_

## *Faturamento = Vendas[Quantidade]*Vendas[Valor]* 


## _Após adicionarmos as duas colunas, realizamos a criação da medida Total faturamento, como podemos verificar abaixo:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/4a14860f-39a5-4e18-a410-0032980fde0e)


### _A seguir temos o código em DAX para criar a coluna Faturamento:_

## *Faturamento total = SUM(Vendas[Faturamento])* 


### _Com isso, finalizamos as áreas, realizando o relacionamento entre as tabelas, e criando colunas e medidas._

### _Nessa etapa foi feito os seguintes pontos:_

+ ***Identificar as áreas do Power BI;***
+ ***Relacionar tabelas;***
+ ***Remover espaços vazios;***
+ ***Conhecer a linguagem DAX;***
+ ***Adicionar colunas;***
+ ***Criar medidas.***


***A primeira pergunta feita pele Cliente foi a seguinte:***

***Qual é o faturamento total do Petshop? E assim dando continuação na montagem da visualização do gráfico***

## _Criando cartões e gráficos:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/92ddf7b3-181d-4c25-828b-6af17e4964b8)


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/e4ad6585-f352-4eb3-b792-f92dd79fff89)


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/22fdb8f7-5ae9-4620-a96b-759d2866c516)


## _Para possibilitarmos a pesquisa pela Data de compra e pela Marca, utilizamos a segmentação de dados:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/9adfa7c7-2a07-48a6-8d5b-20be95c94e49)


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/3c2e2d4c-46c7-4481-90fc-f024557e1e74)


## _Para visualizar a métrica de Faturamento total por Gênero, criamos um gráfico de pizza:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/010c16b9-f34b-4d93-90f5-e327e7a138b9)


## _Para a métrica de Faturamento total por Bairro, usamos o gráfico de barras clusterizado:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/acd730d8-275f-48e6-87b3-1d5d77798580)


## _Para visualizarmos as imagens contidas nas URL’s dos produtos, fizemos uso do image grid :_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/2e9a8be9-9e64-4115-adbd-81e62ee44952)


## _Para habilitarmos a pesquisa por nome do produto, usamos o text filter:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/5dcded87-75e8-4152-8da3-22cdc2e4ae93)


## _Por fim, para visualizarmos a métrica de Faturamento em relação ao tempo, utilizamos o gráfico de área:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/6f25d1e0-7a13-4ac4-b73d-bcc7a71207e6)


### _Nessa etapa foi feito os seguintes pontos:_

+ ***Criar cartões;***
+ ***Criar os gráficos de pizza, linha e barras;***
+ ***Identificar quais visuais melhor se adequam aos dados.***


## _Chegou o momento de estilizarmos o dashboard!_

> [!WARNING]
> + Podemos fazer isso tanto criando um layout diretamente no Power BI quanto importando uma versão já pronta para a ferramenta.
> + A segunda opção é muito utilizada por empresas. Os designers constroem esse material e depois o Power BI é utilizado para adequar o projeto conforme a identidade visual da empresa.
> + Nesse caso, será utilizado um layout pronto, criado por um designer contratado pela Cliente. 
> + Para a elaboração de um dashboard, considere que irá apresentar para a pessoa que demandou essa tarefa. Assim, facilita em definir como quer que seu dashboard transmita as informações solicitadas.
> + Tem que ter muita atenção nas perguntas que precisa responder no dashboard e priorize os achados no momento em que for apresentar o projeto. A narrativa que será constituída ao dashboard pode facilitar a compreensão das pessoas e engajar as partes interessadas nas suas análises.

## _Para estruturar uma apresentação de impacto, é preciso responder algumas perguntas sobre o dashboard:_
> [!NOTE]
> + O que a pessoa que vai consumir os dados desse dashboard precisa saber?
> + O que você gostaria que as pessoas lembrassem ao final da sua apresentação?
> + A linguagem utilizada é simples e apropriada para o público alvo?


### _Trouxe primeiro as principais métricas que a Cliente precisa visualizar , porem esta meio bagunçado._
## _Próximo passo será organizar essa visualização e finalizar o projeto.


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/7870e5c6-5187-4960-aec8-91cab5c0f3a8)


## _Estilização dos cartões_

## _Nesse caso, será utilizado um _layout pronto,_ criado por um designer contratado pela Cliente. 


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/dd826e43-74fb-42ee-9c11-bfa4f6babae0)


## _Abaixo, podemos verificar o dashboard após as estilizações aplicadas:_


![image](https://github.com/MatiasMoraes/Projeto-Gatito/assets/141168863/9db59ee9-bcac-46d0-8ebb-1ed70b52ae1f)


### _Assim, foi feito a estilização de cada um dos visuais e no dashboard como um todo para a Cliente da Gatito Petshop. Com isso, foi finalizado o Dashboard.


### _Nessa etapa foi feito os seguintes pontos:_

+ ***Estilizar os visuais;***
+ ***Inserir plano de fundo;***
+ ***Importar novos visuais.***





> [!IMPORTANT]
> *Mini projeto feito para prática e estudo, toda dica será sempre bem vinda!*
