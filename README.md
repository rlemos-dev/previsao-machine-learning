📊 Previsão de Score de Crédito com Machine Learning

Projeto de Machine Learning desenvolvido em Python com o objetivo de prever o score de crédito de clientes (Ruim, Ok ou Bom) com base em seus dados financeiros e comportamentais.

⚠️ Aviso: Este projeto foi desenvolvido exclusivamente para fins educacionais e de aprendizado em Ciência de Dados e Machine Learning.

🚀 Sobre o Projeto

Neste projeto, simulamos um cenário real onde um banco precisa automatizar a análise de crédito dos seus clientes.

Através de técnicas de Ciência de Dados e Machine Learning, criamos um modelo capaz de analisar informações de clientes e prever automaticamente seu nível de crédito.

🧠 Tecnologias Utilizadas
Python
Pandas
Scikit-learn
📁 Estrutura do Projeto
previsao-machine-learning/
│
├── main.ipynb              # Notebook principal com todo o passo a passo
├── clientes.csv           # Base de dados utilizada para treino
├── novos_clientes.csv     # Base de dados para previsão
└── README.md
⚙️ Etapas do Projeto
1. 📥 Importação dos dados

Leitura da base de clientes utilizando Pandas.

2. 🧹 Tratamento de dados

Conversão de dados categóricos em numéricos usando LabelEncoder.

3. 📊 Separação dos dados

Divisão entre:

Variáveis de entrada (X)
Variável alvo (y)

E separação entre treino e teste.

4. 🤖 Criação dos modelos

Foram utilizados dois modelos:

Random Forest Classifier 🌳
K-Nearest Neighbors (KNN)
5. 📈 Avaliação

Comparação dos modelos usando a métrica de acurácia para selecionar o melhor.

6. 🔮 Previsão

Uso do melhor modelo para prever o score de novos clientes.

📌 Resultado

O modelo Random Forest apresentou melhor desempenho e foi utilizado para gerar previsões finais.

▶️ Como Executar
Clone o repositório:
git clone https://github.com/rlemos-dev/previsao-machine-learning.git
Acesse a pasta:
cd previsao-machine-learning
Instale as dependências:
pip install pandas scikit-learn
Execute o notebook:
jupyter notebook

💡 Possíveis Melhorias
Ajuste de hiperparâmetros dos modelos
Uso de mais algoritmos (XGBoost, Logistic Regression)
Engenharia de features
Deploy do modelo em API (Flask/Django)
Interface web para input de dados

👨‍💻 Autor
Desenvolvido por Rafael Lemos
Estudante de Engenharia de Software
