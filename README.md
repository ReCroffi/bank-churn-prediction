# Bank Churn Prediction & Analysis 📊🏦

Este projeto foca em identificar e analisar os principais fatores que levam à evasão de clientes (Churn) no setor bancário. O objetivo é fornecer insights acionáveis e demonstrar a aplicação de técnicas de Ciência de Dados e visualização executiva para otimização de estratégias de retenção.

![Dashboard de Evasão de Clientes](dash.pdf)

## 📌 Contexto do Projeto
A retenção de clientes é um dos maiores desafios estratégicos para instituições financeiras. Compreender o perfil do cliente bancário que cancela seus serviços permite que a equipe de negócios atue de forma preditiva. 

Neste projeto, realizei a exploração de dados, a modelagem de previsão de churn e a construção de um dashboard interativo para monitorar as taxas de evasão com base em dados demográficos, comportamento financeiro, posse de produtos e classificação de risco.

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **Linguagem e Bibliotecas:** Python, Pandas (Limpeza, tratamento e modelagem preditiva)
* **Visualização de Dados:** Power BI (Desenvolvimento de painel executivo e indicadores)
* **Ambiente de Desenvolvimento:** Git, GitHub (Transição de scripts e versionamento entre ambientes Linux/Windows)

## 📈 Principais Insights e Resultados
A análise consolidada foi realizada sobre uma base de **2.000 clientes bancários**, resultando em um total de **393 evasões** (Taxa de Churn global de **19,65%**).

Os principais padrões identificados foram:
* **Eficácia da Segmentação por Risco:** Clientes classificados pelo modelo como "Alto Risco" apresentam uma taxa de churn alarmante de **53%**, enquanto clientes de "Baixo Risco" representam apenas **4%**. 
* **Fator de Atividade:** O status de membro ativo (`active_member`) tem impacto direto na retenção. Clientes inativos ou com pouca movimentação evadem com muito mais frequência da instituição.
* **Impacto Demográfico e de Produto:** A análise por grupo etário (`age_group`) e por grupo de produtos (`product_group`) demonstrou que há perfis específicos com maior propensão ao cancelamento, exigindo campanhas de relacionamento direcionadas.

## 💡 Conclusão
A segmentação de clientes provou ser extremamente eficaz. A combinação da análise exploratória com a visualização de dados permite que a equipe de negócios priorize ações de retenção focadas exclusivamente na parcela de clientes com maior probabilidade de churn (Alto Risco). Isso otimiza o custo de aquisição de clientes (CAC) e aumenta significativamente o Lifetime Value (LTV) da base atual.

## Link do Dataset
![Dataset no Kaggle](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset)

---
*Sinta-se à vontade para explorar os dados, o arquivo `.pbix` e os scripts em Python disponíveis neste repositório.*
