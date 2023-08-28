# Projeto Aplicado I

![Created Badge](https://badges.pufler.dev/created/ana-vitoria-silva/projeto-Aplicado-I?style=flat)
![Updated Badge](https://badges.pufler.dev/updated/ana-vitoria-silva/projeto-Aplicado-I?style=flat)
![GitHub last commit](https://img.shields.io/github/last-commit/ana-vitoria-silva/projeto-Aplicado-I?style=flat)
![MIT](https://img.shields.io/github/license/ana-vitoria-silva/projeto-Aplicado-I?style=flat)
![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/ana-vitoria-silva/projeto-Aplicado-I?style=flat)

<img src="Imagens/Amazon.png" alt="Exemplo imagem">

# Amazon: Uma análise de performance e de oportunidades

## Sumário

- [📚 Contexto do Estudo](#-contexto-do-estudo)
- [💻 Referências de Aquisição do Dataset](#-referências-de-aquisição-do-dataset)
  - [Sales Product Data](#sales-product-data)
  - [Amazon Consumer Behaviour Dataset](#amazon-consumer-behaviour-dataset)
  - [Amazon Sales Dataset](#amazon-sales-dataset)
- [🌎 Descrição da Origem](#-descrição-da-origem)
- [📊 Descrição do Dataset](#-descrição-do-dataset)
- [🤝 Colaboradores](#-colaboradores)
- [📝 Licença](#-licença)

### Pastas do Projeto

- [Datasets](Datasets)
  - [Sales Product Data](Datasets/Sales%20Product%20Data)
  - [Amazon Consumer Behaviour Dataset](Datasets/Amazon%20Consumer%20Behaviour%20Dataset)
  - [Amazon Sales Dataset](Datasets/Amazon%20Sales%20Dataset)
- [Imagens Utilizadas](Imagens)
- [Cronograma](Cronograma)

# 📚 Contexto do Estudo

> Esse trabalho foi desenvolvido com a finalidade de avaliar quais são os produtos que apresentam melhor desempenho no e-commerce da Amazon e identificar, no mercado em geral, produtos com potencial significativo que podem ser grandes oportunidades para gerar mais receita para a empresa. Outra análise realizada é em relação aos hábitos de consumo dos clientes da Amazon, o que é de grande valia, pois essa análise influencia no processo de determinar quais produtos são pertinentes para serem incluídos no catálogo da empresa.  
>
> Nesse contexto, utilizamos datasets públicos que oferecem dados de grande valia para a análise realizada. Com esse estudo a empresa pode incluir produtos que vão gerar mais receita, fazer ofertas mais assertivas para sua base de clientes e, consequentemente, gerar mais vendas. 

# 💻 Referências de Aquisição do Dataset

>Neste projeto, utilizamos três conjuntos de dados como base para a realização das análises e experimentos. Abaixo estão as informações detalhadas sobre cada um dos datasets:

### Sales Product Data
- Link: [Sales Product Data](https://www.kaggle.com/datasets/knightbearr/sales-product-data)
- Origem dos dados: Kaggle
- Limitação de uso: CC0: Public Domain
- Período da coleta: De abril a setembro de 2019

### Amazon Consumer Behaviour Dataset
- Link: [Amazon Consumer Behaviour Dataset](https://www.kaggle.com/datasets/swathiunnikrishnan/amazon-consumer-behaviour-dataset)
- Origem dos dados: Kaggle
- Limitação de uso: Outra (especificada na descrição)
- Período da coleta: [Informe o período da coleta aqui]

### Amazon Sales Dataset
- Link: [Amazon Sales Dataset](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)
- Origem dos dados: Amazon
- Limitação de uso: CC BY-NC-SA 4.0
- Período da coleta: [Informe o período da coleta aqui]

## 🌎 Descrição da Origem

>Os dados foram retirados da plataforma Kaggle no qual possuí alguns datasets públicos. Como a ideia inicial era avaliar dados de produtos e clientes, encontramos a disponibilização dos dados da Amazon dentro da plataforma, no momento considerados começar por três datasets no qual se relaciona com as vendas de produtos da amazon. 
>  
>Sendo o primeiro dataset (Amazon Sales Dataset) extraído do site oficial da Amazon, por meio de BeautifulSoup e WebDriver usando Python. O segundo dataset (Amazon Consumer Behaviour Dataset), é um conjunto de dados primário auto coletado para analisar o comportamento do consumidor na Amazon, portanto, coletados por meio do Google Forms. E o terceiro encontrado no github, pelo criador que colocou no Kaggle, esse não fica explícito que os dados são da amazon em sua descrição, no entanto em seu metadados a explicação da coluna ID deixa claro que os dados são da amazon (‘‘Um ID de pedido é o sistema numérico que a Amazon usa exclusivamente para rastrear pedidos.’’), importante ressaltar que essas informações são disponibilizadas no próprio Kaggle no link do dataset.


## 📊 Descrição do Dataset

- ###  Amazon consumer Behaviour Dataset

> Conjunto de dados coletados para analisar a análise comportamental dos consumidores da Amazon e consiste em uma coleção abrangente de interações com clientes e padrões de navegação no ecossistema amazônico. Inclui uma ampla gama de variáveis, como dados demográficos do cliente, interação do usuário e avaliações. O conjunto de dados visa fornecer insights sobre as preferências dos clientes, hábitos de compra e processos de tomada de decisão na plataforma Amazon.  
>
>Ao analisar esse conjunto de dados, pesquisadores e analistas podem obter uma compreensão mais profunda do comportamento do consumidor, identificar tendências, otimizar estratégias de marketing e melhorar a experiência geral do cliente na Amazon.  
> 
>Perguntas seguidas dos dados apresentados : 
>- Qual é a sua idade?
>- Qual é o seu gênero?; Com que frequência você faz compras na Amazon?
>- Quais categorias de produtos você normalmente compra na Amazon?
>- Você já fez uma compra com base em recomendações personalizadas de produtos da Amazon?
>- Com que frequência você navega no site ou aplicativo da Amazon?
>- Como você pesquisa produtos na Amazon?
>- Você tende a explorar várias páginas de resultados de pesquisa ou se concentra na primeira página?
>- Qual a importância das avaliações dos clientes no seu processo de tomada de decisão?
>- Você adiciona produtos ao seu carrinho enquanto navega na Amazon?
>- Com que frequência você conclui a compra após adicionar produtos ao carrinho?
>- Quais fatores influenciam sua decisão de abandonar uma compra em seu carrinho?
>- Você usa o recurso "Salvar para mais tarde" da Amazon e, em caso afirmativo, com que frequência?
>- Você já deixou uma avaliação de produto na Amazon?; Quanto você confia nas análises de produtos ao fazer uma compra?
>- Você encontra informações úteis nas avaliações de outros clientes?
>- Com que frequência você recebe recomendações personalizadas de produtos da Amazon?; Você acha as recomendações úteis?
>- Como você avaliaria a relevância e precisão das recomendações recebidas?
>- Qual é seu nível de satisfação com sua experiência geral de compra na Amazon?
>- Quais aspectos dos serviços da Amazon você mais aprecia? Há alguma área onde você acha que a Amazon pode melhorar?

- ###  Amazon Sales Dataset

>Amazon é uma empresa multinacional americana de tecnologia cujos interesses comerciais incluem comércio eletrônico, onde compram e armazenam o estoque e cuidam de tudo, desde envio e preços até atendimento ao cliente e devoluções. O dataset contém informações como: 
>
>- product_id - Product ID
>- product_name - Name of the Product
>- category - Category of the Product
>- discounted_price - Discounted Price of the Product
>- actual_price - Actual Price of the Product
>- discount_percentage - Percentage of Discount for the Product
>- rating - Rating of the Product
>- rating_count - Number of people who voted for the Amazon rating
>- about_product - Description about the Product
>- user_id - ID of the user who wrote review for the Product
>- user_name - Name of the user who wrote review for the Product
>- review_id - ID of the user review
>- review_title - Short review
>- review_content - Long review
>- img_link - Image Link of the Product
>- product_link - Official Website Link of the Product
>
>Portanto, contém dados dos produtos vendidos, preços, descontos, e opiniões dos clientes colocados no review do site da amazon, dessa forma seria interessante para análise de insights, como: impactos da venda de produtos após os reviews, influência das opiniões dos consumidores sobre a venda dos produtos, quais menos avaliados e por quê, quais produtos passar investir mais visto que agradou os clientes, no entanto esse não é possível obter a avaliação do histórico de vendas, já que não possui datas, portanto a análise é restrita ao gosto do consumidor.

- ###  Sales Product Data

>A análise de vendas é a prática de gerar insights a partir de dados, tendências e métricas de vendas para definir metas e prever o desempenho futuro de vendas. A análise de vendas explora seus dados para avaliar o desempenho de sua equipe de vendas em relação às metas. Ele fornece insights sobre os produtos/serviços de melhor e baixo desempenho, os problemas de vendas e oportunidades de mercado, previsão de vendas e atividades de vendas que geram receita.Uma análise de mercado-alvo é uma avaliação de como seu produto ou serviço se enquadra em um mercado específico e onde terá mais ganhos. Informações que contém o Dataset:
>
>- Order ID - Um ID do pedido é o sistema numérico que a Amazon usa exclusivamente para rastrear pedidos. Cada pedido recebe seu próprio ID de pedido que não será duplicado. Este número pode ser útil para o vendedor ao tentar descobrir certos detalhes sobre um pedido, como data de envio ou status.
>- Product - O produto que foi vendido.
>- Quantity Ordered - Quantidade Encomendada é a quantidade total de itens encomendados no pedido inicial (sem quaisquer alterações). 
>- Price Each - O preço de cada produto. Order Date - Esta é a data em que o cliente está solicitando o envio do pedido. 
>- Purchase Address – O purchase order é preparado pelo comprador, geralmente por meio de um departamento de compras.
>- O purchase order, ou PO, geralmente inclui um número de PO, que é útil para combinar remessas com compras.
>
>Uma data de envio; Endereço de Cobrança; Endereço para envio; e os itens solicitados, quantidades e preço.
Portanto, alguns insights possíveis nesse dataset seriam: 
>- Qual foi o melhor ano em vendas? Quanto foi ganho naquele ano? 
>- Qual foi o melhor mês para vendas? Quanto foi ganho naquele mês? 
>- Qual cidade teve o maior número de vendas? 
>- A que horas devemos exibir o anúncio para maximizar a probabilidade de o cliente comprar o produto? 
>- Quais produtos são vendidos juntos com mais frequência? 
>- Qual produto vendeu mais? 
>- Por que você acha que vendeu mais?


## 🤝 Colaboradores

Pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="Imagens/anachung.jpg" width="100px;" alt="Foto da Ana Carolina Chung"/><br>
        <sub>
          <b>Ana Carolina Chung 

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white</b>)](anachung234@gmail.com)</sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="Imagens/anavitoria.jpg" width="100px;" alt="Foto da Ana Vitória Silva"/><br>
        <sub>
          <b>Ana Vitória Silva

[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](avsantos202@outlook.com)</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://miro.medium.com/max/360/0*1SkS3mSorArvY9kS.jpg" width="100px;" alt="Foto do Steve Jobs"/><br>
        <sub>
          <b>Iasmin Silva

[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](meloiasmin@outlook.com)</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://miro.medium.com/max/360/0*1SkS3mSorArvY9kS.jpg" width="100px;" alt="Foto do Steve Jobs"/><br>
        <sub>
          <b>Maressa Bonassoli

[![Icloud](https://img.shields.io/badge/iCloud-3693F3.svg?style=for-the-badge&logo=iCloud&logoColor=white)](ma.banassoli@icloud.com)</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 📝 Licença

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE) para mais detalhes.