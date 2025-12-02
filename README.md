Equipe: Ana virgínia Morais e Juliana Marinho Xavier

### **Introdução**

> Este relatório apresenta os resultados de uma análise exploratória e de validação de hipóteses sobre um conjunto de dados de produtos e avaliações da Amazon. O objetivo principal foi investigar a relação entre descontos, popularidade e a qualidade percebida dos produtos.
> 

**Links:**

- **Apresentação:**https://docs.google.com/presentation/d/1z9FMRw8Uh7r-ALzcFmke2FsVNmVD1QkRCeu-M0mREB0/edit?slide=id.p#slide=id.p
- **Google Colab:** https://colab.research.google.com/drive/1iCQgxWGuhup4gdUeKhO9YPAIYr1l6rAQ#scrollTo=DThDoJ6Q30UC
- **Dashboard:**https://lookerstudio.google.com/reporting/c79f26b0-1416-4216-ade1-0e9d1f8ef07b/page/9VKYF

## **1. Ferramentas, Linguagens e Insumos**

### **1.1 Ferramentas e/ou plataformas**

Neste projeto você pode escolher com quais ferramentas de AI irá trabalhar. Porém, recomendamos o uso do Google Colab e Gemini em conjunto, desta forma você poderá revisar e alterar os códigos sugeridos pelo Gemini na mesma tela.

Ferramentas disponíveis:

- Google Colab ou outro notebook
- Apresentações Google
- Como Inteligências Artificiais recomendamos e Gemini ou ChatGPT

### **1.2 Linguagens**

Este projeto será desenvolvido em Python.

### **1.3 Bases de dados**

Neste projeto você poderá escolher qual conjunto de dados analisar. O objetivo da escolha da base de dados é que neste projeto você se sinta mais livre para explorar os dados, definir o objetivo e escolher um conjunto de dados com um tópico que você acha mais interessante para desenvolver o projeto.

É muito importante ter em conta, ao escolher uma base de dados, que cada conjunto possui características e complexidades próprias. Leia atentamente a descrição das variáveis e resumo do conjunto de dados antes de tomar uma decisão.

### **Opção 2: Amazon sales**

Este conjunto de dados contém dados de mais de 1.000 classificações e análises de produtos disponíveis para venda na Amazon.

Amazon é uma empresa americana de tecnologia com operações multinacionais, cujos interesses comerciais incluem comércio eletrônico, para o qual compram e armazenam estoque, e cuidam de todo o processo, desde a precificação até o envio, atendimento ao cliente e devoluções.

Os dados vêm de um repositório no Kaggle.

**Descrição das variáveis:**

**Tabela amazon_product**

- product_id: ID do produto
- product_name: Nome do produto
- category: Categoria do produto
- discounted_price: Preço com desconto do produto
- actual_price: Preço real do produto
- discount_percentage: Porcentagem de desconto do produto
- about_product: Descrição sobre o produto

**Tabela amazon_review**

- user_id: ID do usuário que escreveu a avaliação do produto
- user_name: Nome do usuário que escreveu a avaliação do produto
- Review_id: ID da avaliação do usuário
- Review_title: Breve avaliação do usuário
- Review_content: Avaliação completa do usuário
- Img_link: Link da imagem do produto
- Product_link: Link para o site oficial do produto
- Product_id: ID do produto
- Rating: Classificação do produto
- Rating_count: Número de pessoas que votaram na classificação da Amazon.
