# Análise de Clientes E-commerce Olist

Este projeto apresenta uma análise exploratória e estratégica dos dados de clientes da plataforma Olist, utilizando automação para limpeza de dados e ferramentas de BI para visualização.

## 🛠️ Tecnologias e Metodologia
* **n8n:** Automação de workflow para limpeza de duplicatas (ETL).
* **Google Sheets:** Processamento de 96.096 registros únicos e criação de Tabelas Dinâmicas.
* **Python/Pandas:** Análise exploratória inicial.

## 🤖 Processo de Ingestão e Limpeza
Utilizei o **n8n** para garantir que a análise não contivesse erros por duplicidade. O robô processou a base bruta e entregou apenas dados validados na aba `Dados_Limpos`.

## 📊 Resultados da Tabela Dinâmica
A análise regional revelou os seguintes insights:
* **Volume Total:** 96.096 clientes únicos processados.
* **Market Share por Estado:** **São Paulo (SP)** lidera o mercado com **21,0%** da base total de clientes.
* **Top Regiões:** Além de SP, destacam-se Minas Gerais (MG) com 11,6% e Rio de Janeiro (RJ) com 12,8%.

---
### 📈 Visualização Regional
![Gráfico de Pizza - Distribuição por Estado](grafico_pizza.png)
*(Imagem gerada via Google Sheets)*
