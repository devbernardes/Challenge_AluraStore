# AluraStore Data Science Challenge

Este repositório contém a solução para o **Desafio de Data Science** da Alura Store. O objetivo do desafio foi analisar dados de vendas de diferentes lojas da rede **Alura Store** e identificar padrões geográficos e de vendas que podem influenciar o desempenho das lojas. A análise foi feita utilizando várias técnicas de ciência de dados, incluindo análise exploratória de dados (EDA), visualizações geográficas e mapas interativos.

## Sumário

1. [Introdução](#introdução)
2. [Objetivo](#objetivo)
3. [Tecnologias e Ferramentas Utilizadas](#tecnologias-e-ferramentas-utilizadas)
4. [Estrutura do Projeto](#estrutura-do-projeto)
5. [Passos para Rodar o Projeto](#passos-para-rodar-o-projeto)
6. [Análises Realizadas](#análises-realizadas)
7. [Resultados](#resultados)
8. [Conclusão](#conclusão)
9. [Licença](#licença)

## Introdução

Neste desafio, foi necessário analisar dados geográficos de várias lojas da **Alura Store** para entender como o desempenho das lojas varia conforme a localização geográfica das vendas. O projeto explorou como as variáveis como **faturamento**, **avaliações de clientes**, **produtos vendidos** e **custo de frete** influenciam a performance de cada loja.

## Objetivo

O objetivo principal foi identificar a loja com menor desempenho e recomendar qual delas seria mais adequada para venda, com base nas seguintes variáveis:

- Faturamento total das lojas.
- Categorias de produtos mais e menos vendidas.
- Avaliações dos clientes.
- Produtos mais e menos vendidos.
- Custo médio de frete.

Além disso, foi explorada a **distribuição geográfica** das vendas, com a criação de gráficos interativos e mapas de calor para visualizar onde as vendas acontecem e como isso pode influenciar o desempenho das lojas.

## Tecnologias e Ferramentas Utilizadas

Este projeto foi realizado utilizando as seguintes tecnologias:

- **Python**: A linguagem principal para análise de dados e visualizações.
- **Pandas**: Para manipulação e análise de dados.
- **Matplotlib** e **Seaborn**: Para visualizações gráficas.
- **Cartopy**: Para criação de mapas de dispersão geográfica e de calor.
- **Folium**: Para criação de mapas interativos e mapas de calor.
- **Git**: Para versionamento do código.
- **Jupyter Notebook**: Para desenvolvimento e execução interativa do código.

## Estrutura do Projeto

```bash
/AluraStore
│
├── /notebooks/
│   └── alura_store_data_analysis.ipynb  # Notebook principal com todas as análises
├── /data/
│   └── loja_1.csv  # Dados da Loja 1
│   └── loja_2.csv  # Dados da Loja 2
│   └── loja_3.csv  # Dados da Loja 3
│   └── loja_4.csv  # Dados da Loja 4
├── /images/
│   └── mapa_dispersao_vendas.png  # Imagem do gráfico de dispersão
│   └── mapa_calor_vendas.png  # Imagem do mapa de calor
│   └── regioes_geograficas.png  # Imagem das regiões geográficas
├── README.md  # Este arquivo
├── requirements.txt  # Dependências do projeto
└── LICENSE  # Licença do projeto
Passos para Rodar o Projeto
Pré-requisitos
Antes de rodar o projeto, é necessário instalar as dependências. Você pode usar o arquivo requirements.txt para instalar todas as bibliotecas necessárias.

Clone este repositório:

bash
Copiar
git clone https://github.com/seu_usuario/alura-store.git
Navegue até o diretório do projeto:

bash
Copiar
cd alura-store
Instale as dependências utilizando pip:

bash
Copiar
pip install -r requirements.txt
Executando o Notebook
Após instalar as dependências, você pode executar o Jupyter Notebook para visualizar e executar as análises interativas.

Abra o Jupyter Notebook:

bash
Copiar
jupyter notebook
No navegador, clique no notebook alura_store_data_analysis.ipynb e execute as células para ver as análises.

Análises Realizadas
As seguintes análises foram realizadas durante o projeto:

Faturamento Total: Calculamos o faturamento total de cada loja com base nas vendas, considerando os preços dos produtos.

Categorias de Produtos: Analisamos as categorias mais e menos vendidas para cada loja, utilizando gráficos para visualização.

Média das Avaliações: Calculamos a média das avaliações dos clientes de cada loja e comparamos os resultados.

Produtos Mais e Menos Vendidos: Identificamos os produtos mais vendidos e os menos vendidos de cada loja.

Custo de Frete: Calculamos o custo médio de frete para cada loja e analisamos como isso impacta nas vendas.

Distribuição Geográfica: Criamos mapas de dispersão e mapas de calor para analisar como as vendas variam conforme a localização geográfica.

Resultados
A análise de faturamento indicou que a Loja 1 tem o maior faturamento, seguida pela Loja 2, enquanto a Loja 4 apresentou o menor faturamento.

As categorias mais vendidas em todas as lojas foram eletrônicos e móveis, enquanto as menos vendidas foram instrumentos musicais e livros.

A Loja 3 apresentou as melhores avaliações médias (4,05), seguida pela Loja 2 (4,04).

A Loja 1 teve um desempenho misto, com produtos mais vendidos e também produtos menos vendidos.

O frete médio variou entre as lojas, mas o impacto do custo de frete foi analisado, mostrando que a Loja 3 teve o melhor custo-benefício.

Conclusão
Com base nas análises realizadas, a Loja 3 foi identificada como a melhor opção para ser mantida devido ao seu desempenho superior em avaliações de clientes, faturamento e vendas de produtos. A Loja 4, por outro lado, teve o pior desempenho em termos de faturamento e avaliações, tornando-se a opção mais adequada para ser vendida.

Recomendamos que o Senhor João considere vender a Loja 4 e focar em melhorar a performance das outras lojas, com especial atenção para a Loja 3, que se destacou em praticamente todos os aspectos analisados.

Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.

Contato:
Seu Nome: [Seu Nome]

GitHub: Seu GitHub
