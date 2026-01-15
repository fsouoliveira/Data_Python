📊 Dashboard de Salários na Área de Dados

Este projeto consiste em um dashboard interativo desenvolvido com Streamlit, cujo objetivo é analisar e explorar dados salariais da área de Dados (Data Science, Data Analytics, etc.) ao longo dos últimos anos.

O dashboard permite visualizar métricas gerais, aplicar filtros dinâmicos e explorar gráficos interativos para melhor compreensão do mercado de trabalho na área de dados.

🚀 Funcionalidades

📅 Filtros interativos por:

Ano

Senioridade

Tipo de contrato

Tamanho da empresa

📈 Métricas principais (KPIs):

Salário médio anual (USD)

Salário máximo

Total de registros

Cargo mais frequente

📊 Visualizações interativas com Plotly:

Top 10 cargos por salário médio

Distribuição de salários

Proporção de tipos de trabalho (remoto/presencial/híbrido)

Mapa mundial com salário médio de Data Scientists por país

📋 Tabela detalhada com todos os dados filtrados

🛠️ Tecnologias Utilizadas

Python 3

Streamlit

Pandas

Plotly Express

📂 Fonte dos Dados

Os dados são carregados diretamente do GitHub:

https://raw.githubusercontent.com/vqrca/dashboard_salarios_dados/refs/heads/main/dados-imersao-final.csv


Eles contêm informações sobre:

Cargo

Salário anual em USD

Ano

Senioridade

Tipo de contrato

Tamanho da empresa

Modalidade de trabalho

País de residência

▶️ Como Executar o Projeto Localmente
1️⃣ Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

2️⃣ Acesse a pasta do projeto
cd seu-repositorio

3️⃣ Crie e ative um ambiente virtual (opcional, mas recomendado)
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows

4️⃣ Instale as dependências
pip install -r requirements.txt

5️⃣ Execute o aplicativo
streamlit run app.py

📦 Exemplo de requirements.txt
streamlit
pandas
plotly

🎯 Objetivo do Projeto

Este dashboard foi desenvolvido com foco em análise exploratória de dados, visualização interativa e como prática de:

Ciência de Dados

Data Visualization

Desenvolvimento de aplicações com Streamlit
