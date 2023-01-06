# Airbnb

## Esse notebook tem como objetivos apresentar as seguintes análises	 

1. Qual o valor médio do aluguel na cidade de Nova York?
2. Quais os nomes das regiões que existem na cidade de Nova York?
3. Qual o valor do aluguel diário mais caro da cidade de Nova York?
4. Quais são as categorias de imóveis que estão cadastradas dentro da base de dados da cidade de Nova York?
5. Existem quantos usuários (Hosts) únicos cadastrados dentro da base de dados da cidade de Nova York?
6. Como é a variação dos preços dos imóveis em NY?
7. Existem mais imóveis baratos ou caros?
8. Qual a distribuição do número de Reviews? Existem imóveis com muitos e
outro com poucos reviews?

## Informações técnicas 

* id - Identificador do registro na base de dados
* name - Nome do Anúncio na plataforma do Airbnb
* host_id - Identificador do Host (Dono do Imóvel)
* host_name - Nome do Host
* neighbourhood_group - Região da Cidade de Nova York
* neighbourhood - Bairro (Está dentro de uma das Regiões)
* latitude - Ponto Geográfico de Latitude
* longitude - Ponto Geográfico de Longitude
* room_type - Tipo da Locação (Quarto, Casa inteira, etc)
* price - Preço do aluguel (diária)
* minimum_nights - Diárias Mínimas para Locação
* number_of_reviews - Quantidade de Avaliações
* last_review - Data da última avaliação feita
* reviews_per_month - Quantidade de Revisões Mensais
* calculated_host_listings_count - Quantidade de Anúncios do Host do Imóvel

## Conclusão

### 1. Qual o valor médio do aluguel na cidade de Nova York?

O valor médio do aluguel é de  U$142.33

### 2. Quais os nomes das regiões que existem na cidade de Nova York?

Bronx 
Brooklyn 
Manhattan
Queens
Staten Island

### 3. Qual o valor do aluguel diário mais caro da cidade de Nova York?

Valor do aluguel diário mais caro é U$10.000

### 4. Quais são as categorias de imóveis que estão cadastradas dentro da base de dados da cidade de Nova York?

Home/apt, Private room, Shared room

### 5. Existem quantos usuários (Hosts) únicos cadastrados dentro da base de dados da cidade de Nova York?

Existem 30232 usuários (Hosts) únicos cadastrados

### 6. Como é a variação dos preços dos imóveis em NY?

Para analisar a variação dos preços utilizaremos o boxplot, ferramenta gráfica que permite visualizar a distribuição e outliers dos dados.

![image](https://user-images.githubusercontent.com/79377636/211079077-6277aabe-926e-488b-bdeb-2702119c3c45.png)

No gráfico plotado podemos analisar que existem bastante outliers, o que indica valores discrepantes. Isso indica que existem imóveis com preços muito afastados do centro de distribuição, afastados da média e da variância. 

### 7. Existem mais imóveis baratos ou caros?

<img width="352" alt="image" src="https://user-images.githubusercontent.com/79377636/211081152-aa6ccf8e-99a1-432a-ba2a-9b0a2b3df94b.png">

### 8. Qual a distribuição do número de Reviews? Existem imóveis com muitos e outro com poucos reviews?

<img width="347" alt="image" src="https://user-images.githubusercontent.com/79377636/211081346-ee94e618-46a6-40a3-bd33-c579375065e9.png">

