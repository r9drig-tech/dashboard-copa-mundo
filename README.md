# 🏆 Dashboard Histórico das Copas do Mundo (1930 - 2022)

Este projeto foi desenvolvido para analisar o desempenho histórico de todas as seleções em Copas do Mundo. O grande desafio foi consolidar dados onde uma seleção aparece em colunas diferentes (Mandante e Visitante) e garantir que o **Brasil** fosse contabilizado com suas **22 participações** corretas.

---

## 🛠️ Tecnologias Utilizadas

* **Python (Pandas & Requests):** Extração de dados via URL e tratamento (Data Cleaning).
* **Tradução Automática:** Script customizado para traduzir mais de 80 seleções para o Português.
* **Power BI:** Criação de modelo de dados relacional e visualizações.
* **DAX Avançado:** Uso de funções como `CALCULATETABLE`, `UNION` e `REMOVEFILTERS` para métricas precisas.

---

## 📊 Principais Métricas Calculadas

* **Total de Títulos:** Contagem histórica de campeões.
* **Participações Reais:** Lógica para identificar a presença da seleção independente da posição no campo.
* **Ranking de Gols:** Soma de gols marcados como `home_team` e `away_team`.
* **Fases Finais:** Identificação automática de Oitavas, Quartas, Semis e Finais.

---

## 📂 Como executar o projeto

1. Execute o script `gerar_dados_copa.py` para gerar os arquivos CSV tratados.
2. Abra o arquivo `Dashboard_Copas.pbix` no Power BI Desktop.
3. Atualize a fonte de dados para os arquivos CSV gerados na sua máquina.

---

## 📸 Preview do Dashboard
*(Aqui você pode arrastar um print do seu dashboard pronto para dentro do GitHub para as pessoas verem seu talento)*
