📊 Análise de Turnover com Árvore de Decisão
Este projeto tem como objetivo prever o turnover (saída de funcionários) de uma empresa com base em dados de Recursos Humanos. Utilizamos uma árvore de decisão como modelo preditivo e aplicamos técnicas de preparação e análise exploratória de dados.

📁 Estrutura do Projeto
Base de dados: Base_RH.csv

Bibliotecas principais:

pandas, numpy para manipulação de dados

matplotlib, seaborn para visualizações

scikit-learn para modelagem preditiva

aed (Análise Exploratória de Dados personalizada)

🔧 Etapas do Projeto
Importação dos dados

Leitura do arquivo CSV com separador ;

Criação da variável alvo

Coluna Target: recebe 1 se o funcionário saiu da empresa, 0 caso contrário

Análise Exploratória de Dados

Utilização de um módulo chamado aed para calcular o IV (Information Value) das variáveis

Tratamento dos dados

Transformação de variáveis categóricas em variáveis dummy (0 e 1)

Modelagem

Utilização de uma árvore de decisão (DecisionTreeClassifier)

Limitação da profundidade da árvore (max_depth=3) para evitar overfitting

Visualização da Árvore

Exibição da árvore de decisão com os nomes das variáveis e classes

✅ Resultado
O modelo foi treinado e uma árvore de decisão foi gerada para explicar o comportamento do turnover com base nas variáveis disponíveis. A visualização da árvore ajuda a interpretar as decisões que o modelo tomou para classificar os funcionários.
