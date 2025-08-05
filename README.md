📊 Análise de Churn de Clientes - Telecom X

Este repositório contém a análise exploratória de dados (EDA) realizada para o projeto "Churn de Clientes" da empresa fictícia Telecom X.

🚀 Desafio

A Telecom X enfrenta um alto índice de cancelamento de clientes (churn) e precisa compreender os fatores que influenciam esse comportamento.

🛠️ Etapas da Análise

O trabalho foi conduzido em Python, utilizando as bibliotecas pandas, matplotlib e seaborn. As etapas incluem:

ETL (Extração, Transformação e Carga) de dados a partir de um arquivo JSON (simulando uma API)
Limpeza e normalização de dados aninhados
Criação de visualizações estratégicas
Análise Exploratória de Dados (EDA)
Geração de insights para o negócio
🔍 Principais Insights

A partir da análise, foram identificados os seguintes padrões que contribuem para o churn:

📅 Tipo de contrato: Clientes com contratos "Month-to-month" têm uma taxa de churn muito maior que aqueles com contratos anuais ou bianuais.
💳 Método de pagamento: Clientes que pagam via "Electronic check" são mais propensos a cancelar.
🌐 Tipo de internet: Usuários de "Fiber optic" apresentaram maior taxa de churn em comparação com os de DSL.
👴 Clientes idosos (Senior Citizens) têm uma taxa de churn significativamente mais alta, especialmente quando combinada com contratos mensais e métodos de pagamento manuais.







📊 Challenge TelecomX_2

Análise Preditiva de Evasão de Clientes


Este repositório contém a solução para o desafio da Telecom X, focado na análise preditiva de evasão de clientes, utilizando técnicas de Machine Learning para identificar fatores que levam ao cancelamento dos serviços.


🎯 Objetivo

A Telecom X enfrenta um alto índice de cancelamentos e busca:

Coletar, tratar e preparar os dados dos clientes.
Analisar e explorar os dados para entender o comportamento dos clientes.
Desenvolver modelos preditivos para identificar clientes com maior risco de evasão.
Oferecer insights estratégicos para reduzir a evasão e melhorar a retenção.

🧹 Limpeza e Tratamento de Dados

Principais etapas realizadas:

✅ Importação e tratamento de dados, incluindo transformação de variáveis categóricas e numéricas.
✅ Remoção de valores ausentes e padronização dos dados.
✅ Análise de correlação para seleção e exclusão de variáveis redundantes.
✅ Preparação dos dados para modelagem preditiva.

🔍 Análise Exploratória e Modelagem Preditiva

Proporção de evasão: cerca de 25,8% dos clientes cancelaram os serviços.
Modelos testados: Regressão Logística, Random Forest e modelo Random.
Melhor modelo: Regressão Logística, com acurácia de 79,96%, precisão de 65,44%, recall de 52,14% e F1-score de 58,04%.
Variáveis mais relevantes para previsão:
Tempo de Contrato (clientes com contratos mais curtos têm maior risco)
Valor Mensal (valores mais altos correlacionam com evasão)
Serviços adicionais como segurança online e backup também influenciam.

✅ Recomendações Estratégicas

Desenvolver ações de retenção personalizadas para clientes com contratos curtos e valores mensais elevados.
Oferecer pacotes promocionais e descontos progressivos para aumentar a fidelização.
Utilizar o modelo de Regressão Logística para monitoramento contínuo, possibilitando intervenções proativas em clientes com maior risco de evasão.

🔧 Tecnologias e Ferramentas

Python 3.10+
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Google Colab / VSCode

✍️ Autor

Projeto desenvolvido por Rayanne Santos como parte de um desafio de análise de dados no setor de telecomunicações.


📝 Licença

Projeto para fins educacionais.







