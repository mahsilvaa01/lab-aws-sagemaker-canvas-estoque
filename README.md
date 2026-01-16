📦 Previsão de Estoque Inteligente na AWS com SageMaker Canvas

📌 Sobre o Projeto

Este projeto tem como objetivo desenvolver um modelo de previsão de demanda de produtos utilizando o Amazon SageMaker Canvas, explorando técnicas de Time Series Forecasting sem necessidade de programação.

O cenário simula um ambiente real de negócios, onde a empresa precisa prever a demanda futura de produtos, considerando histórico de vendas, variações de preço, localização e categoria do produto.

🎯 Objetivo

Criar um modelo de Machine Learning capaz de:

-Prever a demanda futura de produtos

-Identificar padrões de consumo ao longo do tempo

-Apoiar decisões estratégicas de estoque e precificação

-Reduzir riscos de ruptura ou excesso de estoque

🧠 Tecnologias Utilizadas

-Amazon SageMaker Canvas

-AWS

-Machine Learning (No-Code)

-GitHub

-CSV Dataset

-Dataset

📊 Dataset 

Estrutura do Dataset:

-item_id: Identificador único do produto

-Location: Localização onde o produto é comercializado

-time_stamp: Data e/ou hora do registro

-demand: Quantidade demandada do produto

-price: Preço do produto

-Product_category: Categoria do produto

⚙️ Etapas do Projeto

1️⃣ Seleção e Upload do Dataset

<img width="749" height="430" alt="image" src="https://github.com/user-attachments/assets/15257a44-ca59-4cee-aa22-77b9cba84d6d" />



-O dataset foi preparado no formato CSV.

-Upload realizado diretamente no Amazon SageMaker Canvas.

-Não foram encontrados erros de consistência ou formatação.

2️⃣ Construção e Treinamento do Modelo

<img width="780" height="438" alt="image" src="https://github.com/user-attachments/assets/a08e2227-613a-46f0-8c94-d093efea5f4e" />





Configuração do Modelo:

-Tipo de modelo: Time Series Forecasting

-Variável alvo (Target): demand

-Índice temporal: time_stamp

-Identificador da série: item_id

Treinamento do Modelo:

-Utilização do modo Quick Build

-Aprendizado baseado no histórico temporal da demanda

-Identificação automática de padrões sazonais e tendências

3️⃣ Avaliação

<img width="1234" height="594" alt="image" src="https://github.com/user-attachments/assets/ed619fdf-3870-4509-a6af-4b4855d4b92a" />



Após o treinamento, foram analisadas:

-Métricas de desempenho do modelo

-Comportamento da demanda ao longo do tempo

-Impacto de preço e categoria nas previsões

4️⃣ Previsão de Demanda

<img width="782" height="441" alt="image" src="https://github.com/user-attachments/assets/7a3407da-3f96-4994-8403-703e24d7559e" />



-Geração de previsões para períodos futuros

-Análise dos resultados obtidos

-Apoio à tomada de decisão para planejamento de estoque


📈 Conclusão

O uso do Amazon SageMaker Canvas demonstrou ser uma solução eficiente para previsão de demanda em séries temporais, permitindo a criação de modelos robustos sem a necessidade de codificação.
Este projeto evidencia como dados históricos bem estruturados podem gerar insights valiosos para negócios orientados por dados.

👩‍💻 Autora

Mariana Aparecida da Silva
Estudante de Machine Learning, AWS e Inteligência Artificial
