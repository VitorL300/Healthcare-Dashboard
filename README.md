# Healthcare Intelligence Dashboard

Este projeto é um painel interativo desenvolvido em Python utilizando Streamlit e Pandas para análise de dados hospitalares e financeiros. Ele permite que gestores da área da saúde monitorem métricas cruciais de internação e faturamento de forma dinâmica, cruzando informações de pacientes através de uma interface amigável.

Principais Funcionalidades

Filtros Avançados: Segmentação de dados na barra lateral por período de internação, condição médica, tipo de admissão (emergência, eletiva, etc.), plano de saúde, gênero e faixa etária.

Indicadores de Desempenho (KPIs): Cálculo instantâneo do Faturamento Total, Volume de Internações, Faturamento Médio por Admissão e Tempo Médio de Estadia.

Análise Comparativa Temporal: O sistema calcula automaticamente o intervalo de tempo anterior equivalente à seleção do usuário para exibir a variação percentual (crescimento ou queda) de cada indicador em tempo real.

Tratamento de Dados: Script integrado para padronização de strings, tipagem de datas, categorização de idades em grupos (Kids, Adults, Senior) e cálculo exato de dias de internação.

Tecnologias Utilizadas

Python: Linguagem base do projeto.

Streamlit: Construção do front-end analítico, cache de dados e interatividade.

Pandas: Leitura da base de dados (Excel) e manipulação estrutural dos DataFrames.

Como Executar

Clone o repositório.

Instale as dependências necessárias (pip install streamlit pandas openpyxl).

Insira sua base de dados Healthcare.xlsx na pasta data/.

Rode o comando streamlit run app.py (ou o nome do seu arquivo) no terminal.

<img width="1920" height="819" alt="Captura de Tela (256)" src="https://github.com/user-attachments/assets/15554b09-4bff-41af-a60b-22849aebfdac" />
<img width="1920" height="808" alt="Captura de Tela (257)" src="https://github.com/user-attachments/assets/ab0ae0ce-3b8c-43b1-923c-41f6eb51e46c" />


