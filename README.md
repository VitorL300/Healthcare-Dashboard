# 🚑 Healthcare Intelligence Dashboard

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://healthcare-dashboard-vitor.streamlit.app/)

Este projeto é um painel interativo desenvolvido em Python utilizando Streamlit e Pandas para análise de dados hospitalares e financeiros. Ele permite que gestores da área da saúde monitorem métricas cruciais de internação e faturamento de forma dinâmica, cruzando informações de pacientes através de uma interface amigável.

## ✨ Principais Funcionalidades

* **Filtros Avançados:** Segmentação de dados na barra lateral por período de internação, condição médica, tipo de admissão (emergência, eletiva, etc.), plano de saúde, gênero e faixa etária.
* **Indicadores de Desempenho (KPIs):** Cálculo instantâneo do Faturamento Total, Volume de Internações, Faturamento Médio por Admissão e Tempo Médio de Estadia.
* **Análise Comparativa Temporal:** O sistema calcula automaticamente o intervalo de tempo anterior equivalente à seleção do usuário para exibir a variação percentual (crescimento ou queda) de cada indicador em tempo real.
* **Tratamento de Dados:** Script integrado para padronização de strings, tipagem de datas, categorização de idades em grupos (Kids, Adults, Senior) e cálculo exato de dias de internação.

## 🛠️ Tecnologias Utilizadas

* **Python:** Linguagem base do projeto.
* **Streamlit:** Construção do front-end analítico, cache de dados e interatividade.
* **Pandas & Openpyxl:** Leitura da base de dados (Excel) e manipulação estrutural dos DataFrames.
* **Plotly:** Criação dos gráficos interativos para análise demográfica e financeira.

## 🚀 Como Executar Localmente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
   cd NOME_DO_REPOSITORIO
   ```

2. **Instale as dependências necessárias:**
   ```bash
   pip install streamlit pandas openpyxl plotly
   ```

3. **Verifique os dados:**
   Insira sua base de dados `Healthcare.xlsx` na pasta `data/` na raiz do projeto.

4. **Inicie a aplicação:**
   Rode o comando no seu terminal:
   ```bash
   streamlit run app.py
   ```

## ☁️ Deploy

O dashboard está hospedado e em produção na nuvem.

🔗 **[Acesse o Dashboard Online Aqui](https://healthcare-dashboard-vitor.streamlit.app/)**


<img width="1920" height="822" alt="Captura de Tela (305)" src="https://github.com/user-attachments/assets/8c7e5ac7-3e5c-49ce-ac05-06b0f2303104" />

<img width="1920" height="813" alt="Captura de Tela (306)" src="https://github.com/user-attachments/assets/09b79341-fe79-4f97-910c-9d58cb08b20f" />

<img width="1920" height="808" alt="Captura de Tela (307)" src="https://github.com/user-attachments/assets/0b31e2e3-32d8-4cee-9b18-b280710ccf04" />







