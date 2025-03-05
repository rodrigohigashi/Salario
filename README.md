💼 Salário dos Colaboradores 💰
📜 Descrição
Este projeto tem como objetivo estimar o salário dos colaboradores com base em características como idade, experiência, cargo, entre outras variáveis relevantes. Utilizando uma árvore de decisão para regressão 🌳💻, o modelo é treinado a partir de um conjunto de dados para prever salários de colaboradores.

🎯 Objetivo
Estimativa do salário dos colaboradores com base em outras características deles, utilizando técnicas de machine learning 🤖, especificamente uma árvore de decisão para regressão.

🛠️ Tecnologias Usadas
Python 3.10.11 🐍
pandas 🐼
numpy 🔢
matplotlib 📈
seaborn 🌊
dtreeviz 🌳📊
sklearn 📊
ipython 💻
ydata_profiling 📊
sweetviz 🎨
⚙️ Pré-requisitos
Python 3.10.11 🔧
As bibliotecas listadas em requirements.txt 📑 (que inclui todas as dependências necessárias para rodar o projeto).
📥 Instalação
Clone este repositório:

git clone https://github.com/rodrigohigashi/Salario
cd salario_colab
Instale as dependências com o comando:

pip install -r requirements.txt
📂 Estrutura de Diretórios

├── code/
│   └── decision_tree_regression.py  # Código principal para treinar e avaliar o modelo
│   └── aed.py                      # Código para gerar relatórios sobre variáveis, análise de IV e Sweetviz
├── datasets/
│   └── base_funcionarios_v4.csv  # Conjunto de dados utilizado
├── requirements.txt  # Dependências do projeto
└── README.md  # Este arquivo
🚀 Como Usar
Para treinar o modelo de árvore de decisão com o conjunto de dados fornecido, execute o seguinte comando:


python code/decision_tree_regression.py
Gerar Relatórios
Para gerar relatórios de análise exploratória das variáveis, análise de IV e visualização com o sweetviz, execute o código paralelo:


python code/aed.py
📝 Exemplos
Após rodar o código, o modelo será treinado com base nos dados presentes em datasets/base_funcionarios_v4.csv. O script gerará uma previsão de salário de colaboradores com base nas características fornecidas. Além disso, ao executar o código aed.py, serão gerados relatórios sobre a distribuição das variáveis, insights de análise de IV e um relatório interativo com sweetviz.

📊 Resultados Esperados
O modelo de árvore de decisão será treinado com o conjunto de dados, e você verá o desempenho do modelo com os seguintes indicadores de erro e desempenho:

R² (Coeficiente de Determinação): Mede a proporção da variabilidade da variável dependente explicada pelo modelo.
R² Ajustado: Uma versão do R² que leva em consideração o número de variáveis no modelo, penalizando a inclusão de variáveis irrelevantes.
MAE (Erro Absoluto Médio): A média dos erros absolutos entre as previsões e os valores reais.
MSE (Erro Quadrático Médio): A média dos quadrados dos erros entre as previsões e os valores reais.
RMSE (Raiz do Erro Quadrático Médio): A raiz quadrada do MSE, trazendo o erro para a mesma unidade da variável dependente.
MAPE (Erro Percentual Absoluto Médio): A média dos erros percentuais absolutos entre as previsões e os valores reais.
Além disso, serão gerados relatórios de análise exploratória usando o ydata_profiling e o sweetviz, que fornecem insights adicionais sobre os dados e ajudam a visualizar a distribuição e as relações das variáveis. 📊📈

🤝 Contribuições
Sinta-se à vontade para fazer um fork deste projeto, criar uma branch e enviar um pull request para melhorias!

🔗 Referências
Documentação do scikit-learn
Tutorial de Árvores de Decisão para Regressão
Sweetviz Documentation
