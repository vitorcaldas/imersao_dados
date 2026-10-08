# imersao_dados

O objetivo principal desta etapa é apresentar o fluxo de trabalho de um Cientista de Dados no carregamento, exploração inicial, limpeza, manipulação e visualização de dados reais.   

📌 Visão Geral do Projeto

A análise é baseada em um dataset contendo dados de salários e características de cargos na área de dados (como Data Engineer, Data Scientist, Solutions Engineer, entre outros).

Através do uso da biblioteca Pandas no ambiente Google Colab, realizamos: 

 - Importação e Inspeção Inicial: Leitura de arquivos CSV via URL e verificação da estrutura (linhas, colunas, tipos de dados e estatísticas descritivas). 

 - Padronização e Tradução: Renomeação das colunas do DataFrame para o português.  

 - Mapeamento de Categoria: Tradução dos valores categóricos (níveis de senioridade, tipos de contrato, regimes de trabalho e porte das empresas).  

 - Tratamento de Dados Faltantes (Missing Values): Identificação e estratégias para lidar com valores nulos (remoção, imputação por média/mediana, forward/backward fill ou preenchimento fixo).  

 - Ajuste de Tipos de Dados: Conversão de tipos (ex.: conversão de valores numéricos de ano para números inteiros). 

 - Exportação dos Dados: Salvamento do dataset tratado em formato CSV para etapas futuras.  

 - Visualização Exploratória: Criação de gráficos para comunicação clara dos insights.  

🛠️ Tecnologias Utilizadas

 - Linguagem: Python  

 - Biblioteca Principal: Pandas  

 - Interface / Dashboard: Streamlit

 - Ambiente de Desenvolvimento: Google Colab / Jupyter Notebook   

📂 Estrutura das Aulas / Passos Realizados

1 — Análise Inicial de Dados

 - Importação da biblioteca Pandas.  

 - Carregamento da base de dados a partir do GitHub.   

 - Exploração das dimensões (df.shape) e tipos de dados (df.info(), df.describe()).  

 - Renomeação das colunas para o português  

 - Mapeamento das siglas para termos em português  

2 — Preparação e Limpeza dos Dados

 - Verificação de valores nulos (df.isnull().sum()).  

 - Estudo de técnicas de imputação (média, mediana, ffill, bfill, preenchimento por valor fixo).   

 - Remoção de linhas nulas pontuais (df.dropna()).  

 - Conversão de colunas numéricas (ajuste do campo ano para tipo inteiro Int64).  

 - Salvamento dos dados limpos no arquivo dados-imersao.csv.  

3 — Visualização de Dados e Aplicação Web

 - Criação de gráficos para exploração de variáveis categóricas.   

 - Análise da distribuição dos níveis de experiência e formatos de trabalho através de gráficos de barras.  

 - Desenvolvimento da aplicação com Streamlit para exibição interativa das análises e filtros de dados.

🚀 Como Executar o Projeto

 - Abra o arquivo do notebook (.ipynb) no Google Colab ou no Jupyter Notebook.  

 - Certifique-se de ter a biblioteca pandas instalada

📊 Principais Insights Mapeados

 - Senioridade: A maior proporção dos profissionais da base ocupa o nível sênior.  

 - Tipo de Contrato: O modelo integral (Full-time) domina a amostra.   

 - Regime de Trabalho: Grande parte das oportunidades registradas opera no formato presencial, seguida pelo modelo remoto.   

Cargo Mais Frequente: O cargo com maior ocorrência na amostragem é o de Data Scientist.   
